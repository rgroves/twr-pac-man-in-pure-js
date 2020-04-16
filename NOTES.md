Here's a list of the tweaks/additions I can think about making to this project:

- [x] Update usage of KeyboardEvent.keyCode to use KeyboardEvent.code instead.
  - References:
    - https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent/keyCode
    - https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent/code
- [ ] Simplify PAC-MAN movement logic
- [ ] Give ghosts a +1 to INT (increase their smarts just a bit for now)
- [ ] Fix ghost eats PAC-MAN game over condition
  - Currently only when PAC-MAN moves into a ghost does the game end.
- [ ] Keep PAC-MAN moving like the joystick version
- [ ] Give the ghosts more of a ghost look
