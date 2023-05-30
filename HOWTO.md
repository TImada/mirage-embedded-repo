# How to register this repository with opam

```bash
# Add this repository to opam (repository name: "embedded")
$ opam repo add embedded https://github.com/TImada/mirage-embedded-repo
$ opam update -R

# Specify a Solo5 frt-ready version of related packages
$ opam pin add -n functoria 4.3.0
$ opam pin add -n functoria-runtime 4.3.0
$ opam pin add -n mirage-clock 4.2.0
$ opam pin add -n mirage-clock-solo5 4.2.0
$ opam pin add -n mirage-console-solo5 0.8.0
$ opam pin add -n mirage-net-solo5 0.8.0
$ opam pin add -n mirage 4.3.0
$ opam pin add -n mirage-runtime 4.3.0
$ opam pin add -n mirage-solo5 0.9.0
$ opam pin add -n mirage-crypto 0.10.7
$ opam pin add -n mirage-crypto-ec 0.10.7
$ opam pin add -n mirage-crypto-pk 0.10.7
$ opam pin add -n mirage-crypto-rng 0.10.7
$ opam pin add -n mirage-crypto-rng-async 0.10.7
$ opam pin add -n mirage-crypto-rng-eio.0 10.7
$ opam pin add -n mirage-crypto-rng-mirage 0.10.7
```

Do not forget to install 32-bit version of OCaml 4.14.1 if you are now using a 64-bit Linux distribution for cross compilation. You must use the "4.14.1-32bit" switch below to build your MirageOS application running on top of 32-bit processors.

```bash
$ opam switch create 4.14.1-32bit ocaml-variants.4.14.1+options ocaml-option-32bit
```
