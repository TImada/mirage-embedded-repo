# mirage-embedded-repo

This repository provides additional opam pakcages required to try MirageOS/Solo5 porting to embedded MCUs.

## Porting details

- New binding/tender named 'frt' in Solo5 is introduced 
- Check [this document](https://github.com/TImada/solo5-embedded)

## Supported MCUs

- ARM Cortex(r)-R5F core on TI AM64x series

## Supported peripheral devices

- Debug console

## How to use

- Available soon!

## Added packages in this repository

- [ocaml](https://github.com/TImada/ocaml/tree/embedded) (with ARMv7-R support)
- [mirage, mirage-runtime, functoria, functoria-runtime](https://github.com/TImada/mirage/tree/frt) (with Solo5 frt support)
- [mirage-clock, mirage-clock-solo5](https://github.com/TImada/mirage-clock/tree/frt) (with Solo5 frt support)
- [mirage-solo5](https://github.com/TImada/mirage-solo5/tree/frt) (with Solo5 frt support)
- [mirage-console-solo5](https://github.com/TImada/mirage-console-solo5/tree/frt) (with Solo5 frt support)
- [ocaml-solo5](https://github.com/TImada/ocaml-solo5/tree/frt) (with Solo5 frt support)
- [solo5](https://github.com/TImada/solo5/tree/frt) (with Solo5 frt support)
- [solo5-frt-am64x-r5](https://github.com/TImada/solo5-frt-am64x-r5) (TI AM64x/Cortex(r)-R5F specific files for Solo5 frt)
- [conf-frt](https://github.com/TImada/mirage-embedded-repo/tree/main/packages/conf-frt) (MCU selection functionality for Solo5 frt)