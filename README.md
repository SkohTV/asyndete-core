# Asyndete Core
Can be used both as a library or a standalone binary<br>
The library can be used to extend or integrate the project<br>
The binary can be used for your own, or to be queried by other apps

## Building
*For NixOS users, just run `nix develop`*

### Manual
You will need `zig` and the `sqlite3` lib for C<br>
Installing Zig : https://github.com/ziglang/zig/wiki/Install-Zig-from-a-Package-Manager<br>
Installing sqlite3 : **[TODO]**

`zig build run` -> Run the binary as a standalone<br>
`zig build test` -> Test that the binary works on your machine

### Docker
**WIP**

## Schema
<img src="./assets/schema.png">