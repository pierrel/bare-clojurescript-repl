## Prerequisites

You will need [Leiningen][1] 1.7.0 or above installed.

[1]: https://github.com/technomancy/leiningen

## Running

Compile the cljs:

    lein cljsbuild auto

Start the repl:

    lein trampoline cljsbuild repl-listen

To start a web server for the application, run:

    lein ring server

Then you can go back to the repl session and do stuff

## License

Do whatever the hell you want with it
