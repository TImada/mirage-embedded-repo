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
$ opam pin add -n mirage 4.3.0
$ opam pin add -n mirage-runtime 4.3.0
$ opam pin add -n mirage-solo5 0.9.0
```
