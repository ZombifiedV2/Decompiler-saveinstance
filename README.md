# Luau Decompiler

I wrote this over the span of 2-3 days, and as of right now it ONLY produces disassembly output (psuedo-decompilation), so it's not entirely a decompiler yet.

It features bulletin for reference + clear identification of jumps, and for statements.
Instructions also include jump references.
Although it does not have scope control, it does support function scopes.

Credits are much appreciated, though I don't include them in the script.
I ONLY require that you don't claim originality, or say that it was written by yourself.

Before I move onto scope/flow control, it's important that I make a disassembler that is fully capable first, supporting all opcodes, with full readability, so that even if the decompiler does not produce the expected output, there will be an option for disassembly. Because, decompilers will always be far from perfect and should never be expected to produce perfect output.

This script produces 2 local functions, disassemble and decompile.
As of right now, decompile is set to disassemble.

If you want to include luau opcodes in the output, pass "true" as the second argument to the disassemble function.

Enjoy! This is a free/public project for use in any executor.
(my decompiler will remain private for some time)
