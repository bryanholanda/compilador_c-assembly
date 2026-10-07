# C Subset to IJVM — Academic Compiler

**Historical academic project · Compiler construction · C**

An educational compiler project exploring lexical and syntactic analysis, symbol tables, and translation of a limited C-like language to stack-based IJVM assembly. This is not a complete or standards-conforming C compiler.

## What this repository explores

The preserved implementation and development notes cover a lexer/parser, symbol-table diagnostics, assignments, arithmetic, and conditional/control-flow constructs. The emphasis is on translating source-language constructs into the semantics of a stack machine.

The [original development notes](src/comentarios%20sobre%20o%20programa) record important limitations, including restricted arithmetic expressions, incomplete type handling, and unfinished features. They are preserved as written and should be read alongside the source rather than treated as a current test report.

## Explore the code

| Path | Contents |
| --- | --- |
| [`src/`](src/) | Compiler sources and development notes, including the grammar in [`langC.y`](src/langC.y). |
| [`arquivosTeste/`](arquivosTeste/) | Historical input examples and test files. |
| [`compilador_c-assembly/`](compilador_c-assembly/) | Additional preserved project files. |

The original directory layout and Git history are retained. Example files are not evidence of a currently passing automated test suite.

## Maintenance status

Preserved as early academic engineering work and no longer actively maintained. Building or running it with current toolchains has not been verified. This documentation update does not change the compiler, resolve the recorded limitations, or add new language support.
