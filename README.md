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

press LShift+RShift+FN0+RBRC (right bracket) to enable programming mode