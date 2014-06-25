Unreleased
==========
  * Fixed a litte bug in request queue remaining slots calculation
  * Started adding unit tests using `wru`

0.3.0 / 2014-06-24
==================
  * Added automatic request throttle of 1 request per second queueing up to 10 requests
  * Exposed the request queueing functions in `util.queue`

0.2.1 / 2014-06-20
==================
  * Fixed data encoding bug for gzipped response from `0.2.0`
  * First implementation of generic error handling using custom `Error` objects containing the HTTP status code

0.2.0 / 2014-06-19
==================
  * Implemented/fixed broken `database.image` function from `0.1.1`
  * Added rate limiting header info to the callback params

0.1.1 / 2014-06-18
==================
  * Added `HISTORY.md`
  * Fixed some object reference bugs 
  * Compacted the `DiscogsClient` constructor
  * Added the collection folder functions
  * Added the `image` function to the `database` namespace

0.1.0 / 2014-06-18
==================
  * Initial public release