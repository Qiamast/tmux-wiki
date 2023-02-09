# Tmux Wiki
**TMUX** is a terminal multiplexer that allows users to run multiple terminal sessions in a single terminal window, each with its own shell instance. This provides a number of benefits, including the ability to keep long-running processes running even if the user disconnects from the terminal, the ability to split the terminal window into multiple panes, and the ability to switch between different terminal sessions.

#### Getting Started with TMUX
To start using TMUX, simply open a terminal window and type the following command:
```bash
tmux
```

You should now be inside a TMUX session. To exit the TMUX session, type `Control-b` followed by `d`. To attach to an existing TMUX session, use the following command:

```bash
tmux attach
```

#### Creating and Switching Between TMUX Windows
- TMUX allows you to create multiple windows within a single TMUX session.
- To create a new window, press `Control-b `followed by `c`. 
- To switch between windows, press `Control-b` followed by `n` to switch to the **next** window,
- `Control-b` followed by `p` to switch to the **previous** window.

#### Splitting TMUX Windows into Panes
TMUX also allows you to split a single window into multiple **panes**, each of which can contain a different terminal session. To split the current window **horizontally**, press `Control-b `followed by `%`. 
To split the current window **vertically**, press `Control-b` followed by `"`. 
To **switch** between panes, press **Control-b** followed by an` arrow key` (e.g. `Control-b` followed by the** right arrow **key to switch to the **pane to the right**).

#### Conclusion
TMUX is a powerful tool for managing multiple terminal sessions, and provides a number of benefits over traditional terminal emulators. By using TMUX, you can keep long-running processes running, switch between different terminal sessions, and split your terminal window into multiple panes for a more organized and efficient workflow.


