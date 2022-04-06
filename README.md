# pacman.tracy.zig

Demonstrating client setup and client markup for [Tracy Profiler](https://github.com/wolfpld/tracy) in Zig by profiling [floooh's pacman.zig](https://github.com/floooh/pacman.zig). Find more details [here](https://www.abhirag.com/blog/tracy/).

## Build

```$ zig build -Dtracy=./tracy -Dtracy-allocation -Dtracy-callstack```

## Disable Tracy

Building without the options specified above will disable Tracy
