# tmux Cheet Sheet

## Session

create new session
```
$ tmux
```

show all sessions
```
$ tmux ls
```

attach to session
```
# last session
$ tmux a

# session with name
$ tmux a -t mysession
```

detach from session
```
$ ctrl+b d
```

rename session
```
$ ctrl+b $
```

kill session
```
# all but current session
tmux kill-session -a

# kill session with name
tmux kill-session -t mysession
```

## Windows

create window
```
$ ctrl+b c
```

rename window
```
$ ctrl+b ,
```

close current window
```
$ ctrl+b &
```

switch window
```
# next window
$ ctrl+b n

# previous window
$ ctrl+b p

# by number
$ ctrl_b 0...9
```
