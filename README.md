# C64 Hello World
A hello world written in c64 assembly.
## Tasks
### Build
Builds the game using acme
```bash
nix-shell --run "acme main.a"
```
### Run
Runs the game using vice.
Requires: Build
```bash
nix-shell --run "x64dtv main.o"
```
