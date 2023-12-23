# Lua Compilation for Super Mario 64 EX Coop
A full tutorial on how to compile Lua files for both 32/64-bit for sm64ex-coop

Although this is a resource specifically for compiling for sm64ex-coop, it should work for any other games that use lua files.

## Initial Compilation

 1. Download and Extract [`lua-compiler.zip`](https://github.com/Squishy6094/sm64ex-coop-lua-compilation/raw/main/lua-compiler.zip) into any folder.
 2. Drag and Drop your Lua file of choice onto `luac.exe`
 3. In the directory you dragged the Lua file from, you should see `luac.out`. Rename `luac.out` to `[file-name]-64.lua`

## 32-bit Compatibility

 4. Go to https://lua-bytecode.github.io/ and insert your compiled file (`[file-name]-64.lua`)
 5. In the Dropdown labeled "Convert to another EnBi", Select "L4488 (x86 default)"
 6. Save/Rename the Outputted file to `[file-name]-32.lua`