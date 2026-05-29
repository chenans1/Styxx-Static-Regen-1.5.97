Attempt at porting [styxxus's static regen](https://codeberg.org/Styyx/static-regen) to 1.5.97. 
## Quick start

```bash
git clone https://github.com/<you>/SKSE-Plugin-Template
cd SKSE-Plugin-Template
git submodule add -b ng https://github.com/alandtse/CommonLibVR.git extern/CommonLibVR-ng
git submodule update --init --recursive
cmake -B build -S .
cmake --build build --config Release
