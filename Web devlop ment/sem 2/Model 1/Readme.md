### Concept flow 
---
```
Register
 → Password Hash
 → Default Role (MEMBER)

Login
 → Password Compare
 → JWT generate (userId + role)

Request API
 → Auth Middleware (JWT)
 → Role Middleware (ADMIN / MEMBER)
 → Controller
 ```
