# Tiny and cross-device compatible CCITT CRC16 Bit Per Bit or Byte Per Byte calculator library - uCRC16BPBLib #

Master status:   [![Build Status](https://travis-ci.org/Naguissa/uCRC16BPBLib.svg?branch=master)](https://travis-ci.org/Naguissa/uCRC16BPBLib)

## What is this repository for? ##

Tiny and cross-device compatible CCITT CRC16 Bit Per Bit or Byte Per Byte calculation.

Supports any microcontroller.



## Usage ##

This library is used with only static methods, you don't need to (and can't) initialize any class object.

You have these methods:
 - *uCRC16BPBLibObject->reset()* : Resets internal state
 - *uCRC16BPBLibObject->feedBit(bool)* : Feeds a bit
 - *uCRC16BPBLibObject->feedByte(char)* : Feeds a byte
 - *uCRC16BPBLibObject->getResult()* : Gets CRC16 in a uint16_t

## How do I get set up? ##

You can get it from Arduino libraries directly, searching by uCRC16BPBLib.

For manual installation:

 * Get the ZIP from releases link: https://github.com/Naguissa/uCRC16BPBLib/releases
 * Rename to uCRC16BPBLib.zip
 * Install library on Arduino

## Examples ##

Included on example folder, available on Arduino IDE.



## Who do I talk to? ##

 * [Naguissa](https://github.com/Naguissa)
 * https://www.foroelectro.net/librerias-arduino-ide-f29/ucrc16bpblib-pequena-libreria-para-calcular-el-cci-t215.html

## Contribute ##

Any code contribution, report or comment are always welcome. Don't hesitate to use GitHub for that.


You can make a donation via PayPal: https://paypal.me/foroelectro


Thanks for your support.


Contributors hall of fame: https://www.foroelectro.net/hall-of-fame-f32/contributors-contribuyentes-t271.html
