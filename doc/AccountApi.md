# openapi.api.AccountApi

## Load the API package
```dart
import 'package:openapi/api.dart';
```

All URIs are relative to *http://localhost/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**login**](AccountApi.md#login) | **POST** /login | Log in
[**register**](AccountApi.md#register) | **POST** /register | Registers User


# **login**
> login(inlineObject)

Log in

Attempts to log a user in

### Example 
```dart
import 'package:openapi/api.dart';

var api_instance = AccountApi();
var inlineObject = InlineObject(); // InlineObject | 

try { 
    api_instance.login(inlineObject);
} catch (e) {
    print("Exception when calling AccountApi->login: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inlineObject** | [**InlineObject**](InlineObject.md)|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **register**
> register(inlineObject)

Registers User

Attempts to register a new user

### Example 
```dart
import 'package:openapi/api.dart';

var api_instance = AccountApi();
var inlineObject = InlineObject(); // InlineObject | 

try { 
    api_instance.register(inlineObject);
} catch (e) {
    print("Exception when calling AccountApi->register: $e\n");
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inlineObject** | [**InlineObject**](InlineObject.md)|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

