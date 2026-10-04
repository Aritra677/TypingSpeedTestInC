✨ Features

    60-second timed typing test
    Live stopwatch
    Real-time WPM calculation
    Real-time accuracy tracking
    Colored correct and incorrect characters
    Progress bar
    Backspace support
    Ctrl+C to quit
    Calm custom typing passage
    Stats-only results screen
    Play again loop
    No external libraries
    
🛠 Technical Details

    Language: C
    Standard: C11 / POSIX
    UI: ANSI escape codes
    Input: raw terminal input using termios
    Timing: clock_gettime with CLOCK_MONOTONIC
    Input loop: select() + read()
    Dependencies: none beyond the C standard library and POSIX APIs

How To Compile & Run??
Open terminal in your linux/mac machine or cmd in windows and check gcc version if installed by typing
gcc --version and then type [[[ gcc typing_speed_test.c -o typing_speed_test && ./typing_speed_test ]]] .

Thanks ......
