# Blackmagic Timecode Tools

This is a collection of simple tools for generating or reading timecode with Blackmagic Design Decklink cards

## TimecodeReader

This is a simple tool that reads timecode from one or more decklinks, and outputs it to the console. 

## TimecodeWriter

This is a slightly modified version of the RP188VitcOutput sample from the Blackmagic SDK

## TimecodeLatencyChecker

This will output a blue video over one decklink, take an input on another and report the delay in the timecode. An internal offset is applied to account for the delay due to internal buffering on the card.

It has only been tested with 1080i50.