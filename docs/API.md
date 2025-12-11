# API Documentation

## Authentication
Use OAuth2 for authentication. See the AuthModule for implementation details.

## Endpoints
- POST /api/auth/login - Authenticate user
- GET /api/auth/status - Check authentication status

## Examples
```javascript
const auth = new AuthModule(config);
await auth.authenticate(credentials);
```
