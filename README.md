# countdown

## Description

Simple lowtech shell script that can be used as a countdown during a seminar, a conference etc. to indicate to the orator how much time is left.
Once the countdown has reached 10% of the time left, it will be displayed in yellow/red.
Once the time is up, "STOP" will start blinking.

## How to use this

wget https://raw.githubusercontent.com/virgilejarrige/countdown/main/countdown
chmod+x countdown
./countdown number_of_minutes

ctrl+c to stop the coundown.

## Examples

./countdown 10

./countdown 666

## Dependencies
  - lolcat
  - fidget
