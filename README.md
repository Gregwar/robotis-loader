# Robotis loader (for OpenCM9.04 and CM900)

This is an unofficial python script to send a binary program on a robotis 
board (works with OpenCM9.04 and CM900).

Here is the usage:

```
python robotis-loader.py <port> <binary file>
```

Here is an example:

```
$ python robotis-loader.py /dev/ttyACM0 firmware.bin
~~ Robotis programmer ~~

* Opening /home/gregwar/Spidey/firmware/spidey.bin, size=67148
* Resetting the board
* Connecting...
* Download signal transmitted, waiting...
* Board ready, sending data
[ ################################################################# ] 
* Checksum: 148
* Firmware was sent
* Success, running the code
```

## License

This is under MIT license
