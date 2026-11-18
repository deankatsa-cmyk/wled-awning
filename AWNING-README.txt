WLED-MM 14.7.3 (MoonModules, source of 21 Oct 2026) with the awning changes already made:
  wled00/FX.h        effect numbers 230-233, MODE_COUNT 234
  wled00/FX.cpp      PacMan Chase (230), PacMan 3 Arms (231), PacMan Arms (232), Fade On (233)
  wled00/remote.cpp  ON -> preset 10, OFF -> preset 11 (wipe-off, then off), moon -> preset 8
  wled00/json.cpp    PacMan stage button restarts at stage 1 after any other preset
  wled00/FX_fcn.cpp  frame hook (PacMan finale afterglow, Fade On fading from the last frame)
Search for "awning" to see every change.
Build: open this folder in VS Code with PlatformIO, choose awning_4MB or awning_16MB, Build / Upload.
