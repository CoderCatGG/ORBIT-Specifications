End goal: Replace kerboscript

Procedural and some functional elements (similar to rust)

Strict typing

Medium abstraction

loop
while
Iterative for (for ... in ...)

No truthness

Entry function with optional arguments (args)

Structs
Enumerations (tagged unions)
Member functions (the Rust way, not the Java way)
Tuples
Interface
Homogenous arrays (_mainly_ runtime (lists) and comptime sized)

Algebraic data types

No (maybe) anonymous structs/enums

Bitwise operations

Error handling with algebraic data types (Rust ::core::result::Result)

Runtime array indexing may crash on OOB access

namespaces/modules and file seperation (probably via `import`)

kOS cross functionality by praying it exists and calling `call`

Visibile to outside code only by explicitely exporting

Name mangling put on hold indefinetly (until ABI?)

Reexporting the kerboscript standard library to seperate library, ORBIT should be interpretable WITHOUT kOS
(Physic type for kOS library)

Annotating pure/impure (side-effects) functions
