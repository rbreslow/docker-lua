# docker-lua

This repository contains a templated `Dockerfile` for image variants of the [Lua](https://www.lua.org) programming language, as well as the [LuaRocks](https://luarocks.org) package manager.

## Usage

### Template Variables

- `LUA_VERSION` - Lua version
- `LUAROCKS_VERSION` - LuaRocks version

### Testing

An example of how to use `cibuild` to build and test an image:

```bash
$ CI=1 LUA_VERSION=5.3 LUAROCKS_VERSION=3.2.0 ./scripts/cibuild
```
