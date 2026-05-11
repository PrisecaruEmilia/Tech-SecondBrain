# HTTP Headers

## What
HTTP headers contain metadata about requests and responses.
They provide additional information needed for communication between client and server.
## Why it matters
Headers help:  
- authentication  
- caching  
- content negotiation  
- security  
- communication standards

## Mental Model
> [!note]
> 
## Example:
## Common Request Headers  
  
### Authorization  
Defines who is making the request.  
  
Example:  
```http  
Authorization: Bearer token  
```  
  
### Content-Type  
Defines the format of the request body.  
  
Examples:  
- application/json  
- text/html  
- multipart/form-data  
  
### Accept  
Defines which response formats the client can handle.  
  
Example:  
```http  
Accept: application/json  
```  
  
## Common Response Headers  
  
### Content-Type  
Defines the format of the response body.  
  
### Content-Length  
Defines the size of the response body.  
  
### Expires  
Defines when the response becomes invalid.

## Common Problems
> [!note]
> 
## Related
- [[HTTP Request Structure]]  
- [[HTTP Response Structure]]  
- [[JWT Authentication]]