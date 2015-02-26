---
title: Overview
sectionName: API Reference
template: api.jade
menuIndex: 3
---

This pages contains general documentation about the API. Use the links on the
right to navigate to specific resources.

### Content-type

The API uses the JSON format. Unless specified otherwise, all requests and
response should have the `Content-Type: application/json` header.

### HTTP verbs

The API uses the standard HTTP verbs to perform CRUD operations (**C**reate,
**R**etrieve, **U**pdate, **D**elete) on resources, following standard RESTful
API practices.

Find below a quick summary of how HTTP verbs are used in the API:

| Verb     | Description |
|----------|--------
| `GET`    | Used for retrieving a resource or a collection of resources.
| `POST`   | Used for creating a new resource or performing a non-CRUD operation on a resource.
| `PUT`    | Used to perform a full update of a resource (replacing the resource by the JSON data provided in the request).
| `DELETE` | Used for deleting resources.

`HEAD` and `PATCH` are not currently used.

### Errors

The errors are not properly handled at the moment. Do not try to have errors!
