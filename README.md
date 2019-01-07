 # OCaml-Portmidi

 `ocaml-portmidi` is a set of thin bindings to the Portmidi library.

 Portmidi provides cross-platform, low-level MIDI support.

 Portmidi can connect to MIDI ports (devices) and then read/write MIDI data from/to the port.

 ## Dependencies

 * Portmidi C library
 * OPAM

 ## Install

 * `opam pin https://github.com/aplusbi/ocaml-portmidi.git`

 ## Documentation

 Clone repo then build with:

 * `dune build @doc`

 ## Test Executable

 Clone repo then build with:

* `dune build test/test.exe`
