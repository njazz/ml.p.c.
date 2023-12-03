# ml. P.C.

This is a set of max4live devices to enable MIDI track input switching with Program Change messages

---

#### quick start

* add program_change_controller to one MIDI track
* add program_change_router to all other MIDI tracks

#### details

* This set of devices will route MIDI Note On messages to the active track (selected by MIDI Program Change message; default is the first available MIDI track). 
* "controller" device sets all tracks' monitoring to "In" and changes record arm state for the active track for visual feedback.
* When you change the PC value but the notes are still on, the current track will be still on until it receives the appropriate Note Off messages. This is different from the default Ableton MIDI record arm feature and probably the sole purpose of these two simple devices.

---
© 2023 Alex Nadzharov\
BSD-2 license
