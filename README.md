# CS 442 — Mobile Application Development

## Week 1 Lab Task: Enhance the Counter App

**Name:** Huzaifa Qayyum  
**Roll Number:** 048

## Lab Task

This project is an enhanced version of the Flutter Counter App.

The app includes:

- A counter that increases when the `+` button is pressed.
- A Reset button using the refresh icon.
- A personalized threshold of `17`.
- A `"You're on a roll!"` message when the counter goes above 17.
- A counter that tracks how many times the Reset button has been used.
- A personalized theme color.
- An About line showing my name and roll number.

## Screenshot

The screenshot below shows the counter above the personal threshold and at least one reset performed.

![Running App](screenshot.png)

## Personal Parameters

- **myThreshold:** 17
- **mySeedColor:** Colors.purple

The threshold was calculated from the last three digits of my roll number:

`0 + 4 + 8 + 5 = 17`

## Reflection

`setState()` tells Flutter that the state of the widget has changed. When `setState()` is called, Flutter rebuilds the widget and displays the updated value on the screen. Without `setState()`, changing a variable does not tell Flutter that the UI needs to be updated.
