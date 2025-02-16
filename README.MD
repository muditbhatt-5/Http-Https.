# HTTP Status Codes

A reference guide for HTTP status codes with brief descriptions.

<style>
table th {
  background-color: #07a2fe;
  color: white;
}

table tr.code-2xx td {
  background-color: #d4edda;
}

table tr.code-3xx td {
  background-color: #d1ecf1;
}

table tr.code-4xx td {
  background-color: #f8d7da;
}

table tr.code-5xx td {
  background-color: #f5c6cb;
}
</style>

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

This `README.md` file provides a quick reference for commonly used HTTP status codes. Adjust the table or descriptions as needed.
