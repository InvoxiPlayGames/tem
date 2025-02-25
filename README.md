# Tron: Evolution Mod (TEM)

[![build](https://github.com/NeKzor/tem/actions/workflows/build.yml/badge.svg)](https://github.com/NeKzor/tem/actions/workflows/build.yml)
[![test](https://github.com/NeKzor/tem/actions/workflows/test.yml/badge.svg)](https://github.com/NeKzor/tem/actions/workflows/test.yml)
[![doc](https://github.com/NeKzor/tem/actions/workflows/doc.yml/badge.svg)](https://github.com/NeKzor/tem/actions/workflows/doc.yml)

![tem.gif](/doc/src/images/tem.gif)

## Motivation

- Internals of Unreal Engine 3
- Internals of Games for Windows Live
- Internals of SecuROM
- Open Source
- Keeping abandonware alive :^)

## Features

- Removal of Forced Window Minimize
- Superuser
	- Unlimited Health
	- Unlimited Energy
	- High Damage Multiplier
- RGB Suit
- Anti-Anti-Debugger
- HUD
	- Timer
	- Position
	- Angle
	- Velocity
	- Health
	- In-Game Inputs
- Level Selector

## Limitations

- International retail version 1.01 only
- Offline only

## Building

Requires Visual Studio 2022 with MSVC Build Toolset v143.

## Dependencies

Included in `src/lib`.

|Dependency|Version|Description|
|---|---|---|
|[minhook][]|1.3.3|Hooking|
|[imgui][]|1.89.1|UI|
|[json][]|3.11.2|Engine Data Dumping|

## Documentation

- [Roadmap][]
- [tem.nekz.me][]

## Credits

- XLiveLessNess (GFWL IAT definitions)
- TheFeckless (UE3 engine insights)
- Propaganda Games :^)
- ~~Disney and Sony for making the game unplayable after 9 years!~~
- ~~SecuROM for insanely slow game launches!~~
- ~~Microsoft for useless anti-reversing tricks that only hurt performance!~~

[minhook]: https://github.com/TsudaKageyu/minhook
[imgui]: https://github.com/ocornut/imgui
[json]: https://github.com/nlohmann/json
[Roadmap]: https://github.com/users/NeKzor/projects/1/views/1
[tem.nekz.me]: https://tem.nekz.me
