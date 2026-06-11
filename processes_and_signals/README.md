# processes_and_signals

ALU Bash scripting project covering processes and signals.

## Description

Scripts in this directory work with Linux PIDs, processes, and signals
using `ps`, `pgrep`, `pkill`, `kill`, and `trap`.

All scripts:
- Start with `#!/usr/bin/env bash`
- Are executable
- Pass shellcheck (0.7.0) without errors

## Files

| File | Description |
| ---- | ----------- |
| 0-what-is-my-pid | Displays its own PID |
| 1-list_your_processes | Lists running processes (all users, hierarchy) |
| 2-show_your_bash_pid | Shows lines from process list containing "bash" |
| 3-show_your_bash_pid_made_easy | PID + name of processes matching "bash" (no ps) |
| 4-to_infinity_and_beyond | Prints "To infinity and beyond" indefinitely |
| 5-dont_stop_me_now | Stops 4-to_infinity_and_beyond using kill |
| 6-stop_me_if_you_can | Stops 4-to_infinity_and_beyond without kill/killall |
| 7-highlander | Loops forever; ignores SIGTERM with a witty reply |
| 67-stop_me_if_you_can | Stops the 7-highlander process |
| 8-beheaded_process | Force-kills the 7-highlander process |
| 10-process_and_pid_file | PID file + traps for SIGINT/SIGTERM/SIGQUIT |
| 11-manage_my_process | Init-style start/stop/restart wrapper |
| manage_my_process | Worker that writes "I am alive!" every 2s |

## Author

ALU Software Engineering Student
