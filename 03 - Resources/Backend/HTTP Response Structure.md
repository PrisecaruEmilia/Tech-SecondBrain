# HTTP Response Structure

## What
An HTTP response is the server's answer to a client's request.

## Why it matters
> [!note]
## Mental Model
The response is like the finished food returned to the customer.

## Example:
It usually contains:  
1. Status code  
2. Headers  
3. Body/content  
  
## Structure  

### Status Code  
Indicates the result of the request.  
  
Examples:  
- 200 OK  
- 201 Created  
- 400 Bad Request  
- 404 Not Found  
- 500 Internal Server Error  
  
### Headers  
Metadata about the response.  
  
Examples:  
- Content-Type  
- Content-Length  
- Expires  
  
### Body  
The actual returned data.  
  
Usually:  
- JSON  
- HTML  
- files/blobs

## Common Problems
> [!note]
## Related
- [[HTTP Status Codes]]  
- [[HTTP Headers]]  
- [[HTTP Request Structure]]