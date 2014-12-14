asm.lua
=======

A low-level, extraordinarily optimizable subset of Lua.

Why asm.lua?
------------

Because I wanted [OpenComputers](https://github.com/MightyPirates/OpenComputers) to support LPeg.

What's in a name?
-----------------

asm.js ripoff.

What's the target version?
--------------------------

For now Lua 5.2, but once it's out, Lua 5.3, as it has 64-bit integers.

Why not target LuaJIT?
----------------------

I could, and it would definitely work, (LuaJIT is great at JITting) but I wanna target Lua 5.2+ and especially Lua 5.3. Hey, maybe we can even get LuaJIT to JIT 5.3 soon!
