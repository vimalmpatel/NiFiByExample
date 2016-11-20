# NiFi by Example

## Custom Processors
|  Description | Source Code |
| ------------- | ------------- |
| HTTP POST with JSON body | [PostHTTPWithJsonBody.java](nifi-processors/src/main/java/org/zezutom/processors/nifi/example/PostHTTPWithJsonBody.java) |

## NiFi Templates
### HTTP Post
|  Description | Template |
| ------------- | ------------- |
| Post JSON using the InvokeHTTP processor.  | [POST_via_InvokeHTTP.xml](templates/http_post/POST_via_InvokeHTTP.xml)  |
| Post JSON using the PostHTTP processor.  | [POST_via_PostHTTP.xml](templates/http_post/POST_via_PostHTTP.xml)  |
| Post a dynamically built JSON.  | [POST_with_a_Dynamic_Body.xml](templates/http_post/POST_with_a_Dynamic_Body.xml)  |
| Post a dynamically built JSON using regex text replacement.  | [POST_with_a_Dynamic_Body_using_ReplaceText.xml](templates/http_post/POST_with_a_Dynamic_Body_using_ReplaceText.xml)  |
| Download all examples as a single package.  | [HTTP_POST_Examples.xml](templates/http_post/HTTP_POST_Examples.xml)  |

### SSL
| Description  | Template |
| ------------- | ------------- |
| SSLContextService config (key store, trust store)  | [SSL_Service_Config.xml](templates/http_post/SSL_Service_Config.xml)  |