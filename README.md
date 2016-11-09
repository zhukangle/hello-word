# hello-word
jast another description

# Build

For Linux, install autoconf first for jemalloc:

git clone https://github.com/youlan-game/server-youlan.git
cd server-skynet
make 'PLATFORM'  # PLATFORM can be linux, macosx, freebsd now
Or you can:

export PLAT=linux
make

# Run

Run these in different consoles:

./skynet servers/*/config.* # Launch skynet servers(*: simpledb|mongo|normal|login|center|battle)
./3rd/lua/lua servers/client/client.lua     # Launch a client.
