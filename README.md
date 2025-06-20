This project is just the result of following these instructions: https://microzig.tech/docs/getting-started/ as the intention is just to grab stuff from here to copy onto other projects

Steps:
mkdir using-microzig

cd using-microzig

zig init

zig fetch --save https://github.com/ZigEmbeddedGroup/microzig/releases/download/0.14.1/microzig.tar.gz


Now we can build the thing and copy the .uf2 file to the mcu:

zig build

cd ./zig-out/firmware

Now the xiao's pin should start blinking
