### Concept flow 


# 🧠 **COMPLETE PROFESSIONAL CONCEPT MAP (MODULE-WISE)**

---

## 🔐 **MODULE 1: Authentication & Authorization**

### 🔹 JavaScript / TypeScript Concepts

* Closures (JWT verify middleware)
* Async / Await
* Promises
* Error handling with try–catch
* ES6 imports/exports

### 🔹 Backend & Security Concepts

* JWT Access Token
* Refresh Token flow
* Password hashing (bcrypt)
* Token expiration & rotation
* Secure HTTP headers (basic)
* Auth middleware chaining

### 🔹 TypeScript (Interview Gold)

* Interfaces (UserPayload, LoginDTO)
* Enums (UserRole)
* Optional properties
* Readonly fields

### 🔹 Architecture

* Auth controller vs service separation
* Middleware-based authorization
* Reusable guards (role-based)

✅ **Interview line:**

> “Authentication is handled using JWT with refresh tokens and role-based middleware.”


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
