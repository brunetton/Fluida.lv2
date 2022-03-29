**this is a fork** of Fluida, just to provide downloadable .so file (see https://github.com/brummer10/Fluida.lv2/issues/12)

# Fluida.lv2

Fluidsynth as LV2 plugin 

![Fluida](https://raw.githubusercontent.com/brummer10/Fluida.lv2/master/Fluida.png)


## Dependencys

- libcairo2-dev
- libx11-dev
- lv2-dev
- libfluidsynth-dev


## Build
- git submodule init
- git submodule update
- make
- make install # will install into ~/.lv2 ... AND/OR....
- sudo make install # will install into /usr/lib/lv2

that's it.
