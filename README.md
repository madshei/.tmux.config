# tmux.config
My favorate tmux config

## After clone
rename files to .tmux.conf & .tmux.conf.local and move to $HOME
### tmux cheatsheet

```bash"
tmux                                # run tmux in terminal

tmux new -s blah                    # make new tmux session

tmux att -t blah                    # attach to tmux session

tmux ls                             # list of tmux session if exist


<Ctrl> + <b>  <d>                   # detach tmux session but run in bg!

<Ctrl> + <b>  <$>                   # rename current session

<Ctrl> + <b>  <%>                   # split pane Horizentaly

<Ctrl> + <b>  <">                   # split pane Verticaly

<Ctrl> + <b>  <z>                   # zoom current pane # press again to exit from zoom!

<Ctrl> + <b> [arrow key]            # move betwin panes

<Ctrl> + <b>  [Ctrl + arrows]       # resize panes

<Ctrl> + <b>  <c>                   # create new window

<Ctrl> + <b>  <                   # rename window

<Ctrl> + <b>  [0 - 9]               # switch to window if exist

<Ctrl> + <b>  <t>                   # show time :)
```
