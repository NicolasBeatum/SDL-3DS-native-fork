# Custom Nintendo 3DS SDL fork

This private repository is a narrowly modified copy of
[libsdl-org/SDL](https://github.com/libsdl-org/SDL). It is used as a submodule
of the private `sm-3ds-metroidarch` integration and is not an official SDL
release.

The custom Nintendo 3DS change preserves an application CPU-time budget when
placing the SDL audio thread on the system core instead of reducing an already
granted budget.

This custom change and its documentation were developed with OpenAI Codex
assistance, under human direction and testing by Nicolás Andrés Hernández
Vargas. SDL's original license and copyright notices remain in effect.
