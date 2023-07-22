# Dock

The program dock component of LongOS, which relies on LongUI

## Dependencies

```shell
sudo pacman -S gcc cmake qt5-base qt5-quickcontrols2 kwindowsystem
```

You also need [`LongUI`](https://github.com/Longos-system/LongUI) (In fact, LongUI is an upgraded version of CuteUI, and the internal CuteUI elements have not been modified) and [`liblong`](https://github.com/Longos-system/liblong).

## Build and Install

```
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
sudo make install
```

## License

This project has been licensed by GPLv3.
