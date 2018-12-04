# TMUX
##### Install
sudo apt-get install tmux

-----

##### Session commands
command | desc
-----|-----
tmux -V | version
tmux ls | list sessions
tmux kill-server | kill server and all sessions
tmux kill-server -t 0 | kill session 0
tmux new -s \[session-name\] | create and tag
tmux a -t \[session-name\] | attach to session


##### Window commands
command | desc
--------------|-----
Cb w | list windows
Cb n/p | next/previous window



##### Pane commands
command | desc
--------------|-----
Cb d | detach current session
Cb x | kill current pane
Cb % | vertical split
Cb " | horizontal split
Cb b arrow | move to another pane
Cb b C-arrow | resize pane
Cb o | swap panes
Cb - | restore pane
Cb , | name current pane
Cb q | show pane numbers
Cb : | get prompt
Cb [ | scroll mode (q to end)
Cb z | zoom pane
Cb Pg | scroll PgUp/PgDn (q to end)
