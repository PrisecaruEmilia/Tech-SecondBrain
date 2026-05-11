# Learned Today

part 1 - API fundamentals; validations and DTOs in API; EF core in API; DI; Authentication and authorization in API; API versioning; consuming API with authentication endpoints
part 2 - restructure with best practices; filter, sorting and pagination; handle image/file uploading in API; refresh tokens and invalidating token chain; consuming refresh tokens; deploying API
# Questions
> [!note]
# Problems
> [!note]

# Ideas
API - is a way of multiple applications to communicate with each other
- person (client) -> waitress (API) -> order (request) -> chef (server) -> cooked food (response) -> waitress (API) -> person (client)
- request - basically a document that contains 3 pieces of information:
	- verb - defines what is the action that server has to take
	- headers - have information about the request itself
	- content - optional
- response - a piece of data; another text document
	- status code - defines the type of the response (successful/failed)
	- headers - it can be the content type - the type/format of data that the server is sending back (text)
	- content
Request object:

1) HTTP verbs/actions
- GET: fetches/requests resource
- POST: creates/inserts resource
- PUT: updates/modifies resource
- PATCH: updates/modifies partial resource
- DELETE: deletes/removes resource
- ... more verbs
2) Request's Metadata
- Content Type: Content's Format
- Content Length: Size of the Content
- Authorization: Who is making the request
- Accept: What are the accepted type(s)
- ... more headers
3) Request's Content
- HTML, CSS, XML, JSON
- information for the request
- blobs 
- etc

Response object:

1) Status Code
- 100-199: informational
- 200-299: success
	- 200 - ok
	- 201 - created
	- 204 - no content
- 300-399: redirection
- 400-499: client errors
	- 400 - bad request
	- 404 - not found
	- 409 - conflict
- 500-599: server errors
	- 500 - internal server error
2) Response's Metadata
- content type: content's format
- content length: size of the content
- expires: when is this valid
- ... more headers
1) Content
- HTML, CSS, CML, JSON
- blobs
- etc
