**date:** 18-Apr-2025
**type:** concept
**source:** [[llm-static-vs-dynamic-linked.md]]

static linked libraries (`.lib` windows, `.a` unix) gets linked at compile time
and is baked into the consumer's executable.

a dynamic library (`.dll` windows, `.so` unix) gets linked at runtime and is
shared between all processes that consume it.

both dynamic and static libs must be pre-compiled before use.
