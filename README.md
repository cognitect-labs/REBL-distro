# NOTE: REBL has been superseded by Morse

Instead use: https://github.com/nubank/morse

# `REBL`

REBL is a graphical, interactive tool for browsing Clojure data. REBL is extracted from Datomic tools developed by the [Datomic Team](https://www.datomic.com/) at [Cognitect](https://cognitect.com), and is available for non-commercial use (per the EULA) free of charge. We hope that many Clojure developers will find it useful. 

## Features

* A two-pane browser/viewer system for viewing collections and their contents
* Navigation into and back out of nested collections
* A structured editor pane for entering expressions to be evaluated
* A root browse of a history of expression evaluations
* The ability to 'wrap' a stdio based REPL (e.g. Clojure's native REPL) so that it can monitor and display the interactions therein, while still allowing them to flow back to the host (e.g. the editor)
* When used with non-stdio repls (e.g. nREPL), can be launched a la carte and accepts values to inspect via an API call
* The ability to capture nested values as defs in the user namespace
* The ability to run multiple independent UI windows
* Metadata viewing
* Datafy support
* Extensibility to new browsers and viewers
* Full keyboard control via [hotkeys](https://docs.datomic.com/cloud/other-tools/REBL.html#keybindings)

REBL runs in your application JVM process, and can be used at dev-time without adding any runtime deps. The UI is written in JavaFX.

# [Documentation](https://docs.datomic.com/cloud/other-tools/REBL.html)

[REBL Documentation](https://docs.datomic.com/cloud/other-tools/REBL.html)
