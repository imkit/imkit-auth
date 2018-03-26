# Sample Micro Auth Service

![Architecture](Auth2.1.png)

## Must implement API:
### Verify
Method: POST
Request Format: JSON
```javascript
{"token": "Client Access Token"}
```
Response Format: JSON
```javascript
{"id": "user-id", "nickname": "Nickname", "avatarUrl", "Avatar URL"}
```
