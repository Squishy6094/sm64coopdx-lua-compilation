# Lua Compilation for Super Mario 64 Coop Deluxe
A full tutorial on how to compile Lua files to 64-bit for sm64coopdx

Although this is a resource specifically for compiling for sm64coopdx, it should work for any other games that use lua files.

## Initial Compilation

 1. Download and Extract [`lua-compiler.zip`](https://github.com/Squishy6094/sm64ex-coop-lua-compilation/raw/main/lua-compiler.zip) into any folder.
 2. (Optional) To remove debugging data, create a shortcut the extracted `luac.exe` with the flag `-s` at the end of the shortcut properties
 3. Drag and Drop your Lua file of choice onto `luac.exe` (or it's shortcut)
 4. In the directory you dragged the Lua file from, you should see `luac.out`. Rename `luac.out` to it's original filename (`[file-name].lua`)

## 32-bit Compatibility (Optional)

**Note that 32-bit is no longer standard and is likely depricated on most machines, only compile if you know you require it**

 5. Go to https://lua-bytecode.github.io/ and insert your compiled file (`[file-name]-64.lua`)
 6. In the Dropdown labeled "Convert to another EnBi", Select "L4488 (x86 default)"
 7. Save/Rename the Outputted file to `[file-name]-32.lua`
