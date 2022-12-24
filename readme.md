# readme

## function

spidev lookback selftest

## build require

OS：Linux

Compiler：gcc

## build flow：

gcc spi_test.c -o spi_test

## Test：

sudo modprobe spidev

./spi_test -D /dev/spidev0.0