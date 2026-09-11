# ocaml-c-bindings-rules

A set of [OpenGrep] rules for right-hand interfacing C and OCaml.

Rules:
1. `ocaml-c-bindings-properly-values-saving`
2. `ocaml-c-bindings-unrooted-local-value`
3. `ocaml-c-bindings-unrooted-params-value`
4. `ocaml-c-bindings-unbalanced-runtime-blocking-section`
5. `ocaml-c-bindings-runtime-use-in-blocking-section`
6. `ocaml-c-bindings-invalid-value-conversion`

### Usage

```console
$ opengrep scan --config rules/ocaml-c-bindings-rules.yml .
```

[OpenGrep]: https://www.opengrep.dev
