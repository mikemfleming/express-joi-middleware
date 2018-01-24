# express-joi-middleware

Example use:
```
const validateSchema = require('express-joi-middleware');

app.post('/api/v1/claims', validateSchema(schema.claims.create, { convert: true }), Claims.create);
```
