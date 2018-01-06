# Trivial Wrapper Around $EDITOR for Use with cscope(1) inside tmux/screen sessions

## Usage:

1. Start a tmux or screen session

2. Set `CSCOPE_EDITOR`

```
$ export CSCOPE_EDITOR=$HOME/bin/cscope_editor
```

3. Start cscope

```
$ cscope -Rqk
```

4. When you choose to edit a file in the cscope UI you'll get $EDITOR in
   a new window in your tmux/screen session.

