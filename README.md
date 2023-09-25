# TD-SuperDirt
 
This is a tox file to work with SuperDirt using TouchDesigner.
SuperDirt runs on SuperCollider as an OSC-based synthesizer.
So you can use TouchDesigner and this tox to send OSCs and play sounds with the protocol for SuperDirt directly.

## Test Environment
* TouchDesigner 2023.10130 (Mac/Win)
* SuperCollider 3.13.0(Mac/Win)

## Way to use the sample

1. Open "SuperDirtStartUp.scd"
2. Place the cursor on the line that says "SuperDirt.start" and press Shift+Enter.
3. Open "OscOutSuerDirt.toe"
4. Turn on the button marked "Play".

In a Windows environment, SuperDirt may take a little longer to start up due to Windows Defender.

## Way to Setup
1. Install [SuperCollider](https://supercollider.github.io/)
2. Install [SuperDirt](https://github.com/musikinformatik/SuperDirt)
3. Install [TouchDesigner]https://derivative.ca/)

## About OSC Protocol of SuperDirt
SuperDirt does not have OSC documentation, so there are parts of it where it is not clear how it works.