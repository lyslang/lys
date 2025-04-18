<!--
SPDX-FileCopyrightText: 2025 Aljebriq <143266740+aljebriq@users.noreply.github.com>

SPDX-License-Identifier: CC-BY-SA-4.0
-->

# Running from source

You will need to have [OCaml](https://ocaml.org/) version 5.0.0 or later [installed on your system](https://ocaml.org/docs/installing-ocaml) along side [opam](https://opam.ocaml.org/) (which is the preferred install method).

You will then be able to run the following commands:

```sh
git clone https://github.com/lyxlang/lyx.git
cd lyx
opam install --deps-only .
dune exec lyx -- …
```

You can also just use [Nix](https://nixos.org/) without the above requirements:

```sh
nix run github:lyxlang/lyx …
```
