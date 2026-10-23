# Toggle Dialogue Camera

Mod page: https://www.nexusmods.com/skyrimspecialedition/mods/97280

Started out using the template of mrowr purr: https://github.com/SkyrimScripting/SKSE_Template_HelloWorld

Build with an x64 Visual Studio developer shell, CMake, Ninja and vcpkg (`VCPKG_ROOT`):

```text
git submodule update --init --recursive
cmake --preset relwithdebuginfo
cmake --build build/relwithdebuginfo --target DialogueCameraToggle
```
