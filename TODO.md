## 0.3.0
Changes:
* event handler continue to work after disconnect (is it a really good idea?)
* Drab.Server to receive messages from the outside world (and broadcast them to the clients)

## 0.4.0
Changes:

## Future
Changes:
* tests, tests, tests
* benchmarks
* debuggin console
* timeout for event handlers
* timeout for Drab.Query and Drab.Modal functions
* specify on which pages drab broadcasts, with wildcard
* dependencies for modules (for ex. Modal depends on Query)
* before_handler callback (to run before each handler), if return anything else than Socket, do not proceed
* Store is lost when navigate back and forward (Drab.run() launches every time)
* handling event handler crashes without disconnect the whole socket (spawn instead of spawn_link)
