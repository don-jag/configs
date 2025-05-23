Tmux config based on fork from "Dream of Code" repo.

https://github.com/dreamsofcode-io/tmux/blob/main/tmux.conf

source tmux config without exiting tmux.

```tmux source-file ~/.config/tmux/tmux.conf```

Reload tmux config
```
tmux bind -r r source-file ~/.config/tmux/tmux.conf
```