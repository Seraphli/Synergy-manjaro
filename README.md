# Synergy-manjaro

## How to compile on manjaro

1. Clone [Synergy](https://github.com/symless/synergy-core)
2. `cd synergy-core`
3. Checkout tag
4. Compile
```
mkdir build
cd build
cmake -D CMAKE_BUILD_TYPE=Release -D SYNERGY_ENTERPRISE=ON ..
cmake --build . --parallel
```
5. cd bin and run synergy
