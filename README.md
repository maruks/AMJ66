# AMJ66
AMJ66 Keyboard tmk firmware

## dependencies

* brew tap osx-cross/avr
* brew install avr-libc
* brew install dfu-programmer

### build and download to device

* make clean
* make all
* make dfu

Press LShift+RShift+PAUS to enable programming mode.

PAUS is FN0+P. It was FN0+RBRC (right bracket) in orignal keymap.