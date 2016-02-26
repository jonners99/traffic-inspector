# Traffic Inspector

This package works with the other traffic repositories to create a system allowing the tracking of requests to APIs and their responses.

Using an existing box, requests will be stored, the request will then be forwarded to its final destination. The response that is received from this destination will also be stored.

Currently this inspector is built in PHP with a MySQL backend, the goal, however, is to research the fastest method of performing these secondary requests and storing the data so that the API user does not notice slowdown.
