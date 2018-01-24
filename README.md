# express-joi-middleware

Example use:
```
app.post('/api/v1/claims', expressJoi(schema.claims.create, { convert: true }), Claims.create);
```
