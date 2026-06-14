# Instructure Canvas GraphQL API

The Canvas LMS GraphQL API provides a flexible query interface for Canvas LMS data, allowing developers to request exactly the fields they need and reduce over-fetching. It follows the Relay Object Identification spec (node/legacyNode patterns) and supports cursor-based pagination via connections. An interactive GraphiQL browser is accessible by appending `/graphiql` to any Canvas domain URL. Authentication is handled via the same OAuth2 tokens used for the REST API, passed as a Bearer token in the Authorization header.

**Endpoint:** https://{canvas_domain}/api/graphql

**Documentation:** https://developerdocs.instructure.com/services/canvas/basics/file.graphql

**References:**
- Documentation: https://developerdocs.instructure.com/services/canvas/basics/file.graphql
- GettingStarted: https://canvas.instructure.com/doc/api/graphql.html
- GraphiQL: https://{canvas_domain}/graphiql
- Source: https://github.com/instructure/canvas-lms/tree/master/app/graphql
