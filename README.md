# MultiTimer
A simple tool for running multiple concurrent timers in a web browser.

### Purpose

This tool provides a way to quickly and easily maintain multiple concurrent timers with potentially different stop times. The impetus for this project was a make-up session for a standardized test, in which multiple students were working concurrently on different sections of the test with different durations. This tool allows timers to be created, paused, resumed, or removed at will.

### Characteristics

<ins>Count Down</ins> - This is the "normal" mode of operation, in which the user specifies a length of time in H:M:S and the timer counts down to zero. This mode is limited to 100 hours minus 1 second because only two digits are allowed in the hours field.

<ins>Designated Stop Time</ins> - The user enters a clock time (such as 22:45:00) and when the timer is started the remaining time until the designated moment is calculated and loaded into a regular Count Down ("normal") timer. If the clock time for the current day has already passed then the clock time for tomorrow is used.

<ins>Count Up</ins> - In this mode the timer counts up indefinitely. There is no limit. The largest displayed unit of time is hours. When timers are sorted by time remaining, timers counting up are always considered last.

This tool was designed as a single file (instead of using separate .html, .css, and .js files) to make it user-friendly for users not familiar or comfortable with web applications. This singular file can be dropped anywhere and executed in-place by itself.
