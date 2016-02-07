# CLI Application base, in Clojure

## Usage

* Clone the repo
* Choose a license -> ``project.clj::license``
* Find a project name  -> ``project.clj::defproject``
* Find a package name  -> ``project.clj::main, aot``, ``folders in test, src``
* Change this README.md
* Change the git remote
* Start writing tests
* Execute them with ``lein midje :autotest`` or inside the REPL
* Push (to you new remote)


## Tests

### Testing from the CLI

``lein midje :autotest``

This has the advantage that loads everything, each time.

### Testing inside the REPL

```bash
lein repl
```

```clojure
(use 'midje.repl)
(autotest)
```

This has the advantage that is faster.
