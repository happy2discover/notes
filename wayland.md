### What is wayland?
A new window system with the display server and window manager merged.  
The complete design for the wayland window system is split into several layers.
1. The most basic layer is an implementation of inter process communication functionality, together with a few utilities, like a main loop dispatcher and some data types.
2. The second layer is the window system protocol.
