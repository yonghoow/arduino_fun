# arduino_fun
## some simple sketches for the Arduino Uno

## compile sketch
$ arduino-cli compile --fqbn arduino:avr:uno helloworld.ino

## Upload sketch
$ arduino-cli upload -p /dev/ttyACM0 --fqbn arduino:avr:uno helloworld.ino
