## Zephyr Game Engine
This Organization is all about the Zephyr Game Engine. It is an engine written in Zig, meant to be fully open-sourced and accessible to any one. 

It is still very early in development and has a long ways to go

### Packages
- Zephyr Runtime: The core game engine library. Powers the entire game engine.
- Zephyr Editor: The editor application of the game engine, allows users to make the game itself.
- Zob(Zephyr Job): A library to easily prioritize background jobs that need to run asynchronously. Very easy to kick of a batch of jobs to run at the same time.
- Zoto(Zephyr Proto): A library to serialize Zig structs into a binary format(protocol buffers). It does not use `.proto` files nor the protoc compiler, but is compatible with them.
