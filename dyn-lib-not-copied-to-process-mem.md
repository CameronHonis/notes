**date:** 18-Apr-2025
**type:** answer
**origin:** [[do-dyn-libs-get-copied-to-process-mem-at-runtime.md]]
**source:** [[llm-dyn-libs-copied-process-mem-runtime.md]]

dynamic libs do not get copied byte-for-byte to process memory. instead,
the operating system loads the dll/so file into memory and creates a reference 
(pointer) from inside the consumer's memory address space.
