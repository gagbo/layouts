<!--
SPDX-FileCopyrightText: 2023 Gerry Agbobada <git@gagbo.net>

SPDX-License-Identifier: CC0-1.0
-->

# Layouts

This repo uses [Kalamine](https://github.com/fabi1cazenave/kalamine) and
github actions to produce version-controlled layouts for my use cases.

## Grenough

This is my own experiment at making a good French/English layout, using
a dead key for the common accented characters, and that can hold within
a smaller amount of keys than the layouts that use éàèêç on the base layer.
It tries to take inspiration from Optimot, Colemak, and Ergol approaches
to make something decent.

## TODO

- [ ] Put generated layouts in repo so I can patch them directly
- [ ] Don't use qwerty location when Ctrl/System is active
- [ ] Make an angle-mod version of the layouts
- [ ] Patch kalamine to allow
  + [ ] Defining our own dead key layers like the predefined ones
  + [ ] Having dead keys behind other dead-keys
    - [x] MacOS: use the <next = ...> config in the action field
    - [ ] Windows:
    - [ ] Linux:
