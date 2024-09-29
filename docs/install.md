# Install

## opam

```bash
sudo apt install opam
```

### Initialise opam

```bash
opam init -y
```

```bash
eval $(opam env --switch=default)
```

```bash
opam update
opam upgrade dune
```

### Listing Switches

```bash
opam switch list

#  switch   compiler     description
→  default  ocaml.5.2.0  default
```

## ocaml

```bash
ocaml --version

The OCaml toplevel, version 4.13.1
```

