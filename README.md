## tmux.config
My favorate tmux config
after clone, rename files to .tmux.config & .tmux.config.local
# tmux cheatsheet

```bash"
tmux                                # run tmux in terminal

tmux new -s blah                    # make new tmux session

tmux att -t blah                    # attack to tmux session

tmux ls                             # list of tmux session if exist


<Ctrl> + <b>  <d>                   # detach tmux session but run in bg!

<Ctrl> + <b>  <$>                   # rename current pane

<Ctrl> + <b>  <%>                   # split pane Horizentaly

<Ctrl> + <b>  <">                   # split pane Verticaly

<Ctrl> + <b>  <z>                   # zoom current pane # press again to exit from zoom!

<Ctrl> + <b> [arrow key]            # move betwin panes

<Ctrl> + <b>  [Ctrl + arrows]       # resize panes

<Ctrl> + <b>  <c>                   # create new window

<Ctrl> + <b>  <,>                   # rename window

<Ctrl> + <b>  [0 - 9]               # switch to window if exist

<Ctrl> + <b>  [:setw synchronize-panes]

<Ctrl> + <b>  <t>                   # show time :)

<Ctrl> + <b>  [:set mouse]          # to scrolling window with mouse
```
