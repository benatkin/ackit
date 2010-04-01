# Ackit! - the Api Client KIT

Ackit! will be a kit for making clients for RESTful APIs. Planned features:

* A way to design API clients in JSON.
* A way to call an API from JSON.
* A way to generate API client code.
* A way to tie into authentication.
* A way to edit the JSON.

Here's an outline of what a defnition for the twitter API might look like:

Models:

* Base - the base API
* Client - an API client, with authentication
* User - a user, which can have a client associated with it

Calls:

* search - Base
* friends_timeline - User with client
