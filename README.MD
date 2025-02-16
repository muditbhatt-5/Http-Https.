# HTTP Status Codes

A reference guide for HTTP status codes with brief descriptions.


## Status Codes Overview

| Status Code | Description                      |
|-------------|----------------------------------|
| **1xx**     | Informational responses          |

### 2xx Success
| Status Code | Description                      |
|-------------|----------------------------------|
| 200         | OK: The request succeeded.       |
| 201         | Created: Resource created.       |
| 202         | Accepted: Request accepted.      |
| 204         | No Content: No content returned. |

### 3xx Redirection
| Status Code | Description                                |
|-------------|--------------------------------------------|
| 301         | Moved Permanently: Resource moved.         |
| 302         | Found: Resource temporarily moved.         |
| 304         | Not Modified: Cached version used.         |

### 4xx Client Errors
| Status Code | Description                                |
|-------------|--------------------------------------------|
| 400         | Bad Request: Invalid request.              |
| 401         | Unauthorized: Authentication required.     |
| 403         | Forbidden: Access is not allowed.          |
| 404         | Not Found: Resource not found.             |
| 429         | Too Many Requests: Rate limit exceeded.    |

### 5xx Server Errors
| Status Code | Description                                |
|-------------|--------------------------------------------|
| 500         | Internal Server Error: Generic server error. |
| 501         | Not Implemented: Server does not support.  |
| 502         | Bad Gateway: Invalid response from server. |
| 503         | Service Unavailable: Server is overloaded. |


