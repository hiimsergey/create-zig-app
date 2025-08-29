# create-zig-app
A opinionated wizard script inspired by **create-react-app** and **create-tauri-app** that scaffolds a new Zig project in a lean manner.

This should serve as an alternative to `zig init` that puts many unnecessary comments in your code that you have to delete again.

## Usage
```sh
./create-zig-app
```

## Features
- Choose starting point between `src/main.zig` and `<project name>.zig`
- Include a run step in `build.zig` or not
- Include a wrapper struct using `std.heap.DebugAllocator` in Debug mode and `std.heap.c_allocator` otherwise
- Initialize a Git repository
