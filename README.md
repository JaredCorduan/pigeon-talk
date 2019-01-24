# The Amazing Pigeon Hole Principle Slides

Slides for a talk given at the College of Charleston on 1st February 2018

## Building LaTeX Beamer slides

Insinde the directory with this README, run make:

```shell
make
```

This makes `pigeon.pdf`.

If you prefer using [Nix](https://nixos.org/nix/),
the `make` command can be run as via `nix-build`:

```shell
nix-shell --pure --run make
```

For a continuous compilation run:

```shell
nix-shell --pure --run "make watch" 
```
