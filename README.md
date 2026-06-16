# Plugns
https://github.com/tmux-plugins/tpm

Nord theme - https://www.nordtheme.com/docs/ports/tmux/installation

Add powerline fonts - https://swetankraj.github.io/ubuntu-terminal-powelinego/

Managing tmux plugins - https://github.com/tmux-plugins/tpm

Utility for splitting panes

```sh
     neditor() {
         $(tmux splitw -p 30)
         $(tmux splitw -h)
     }
    
     nterm() {
         $(tmux splitw -h)
         $(tmux splitw -f)
         $(tmux splitw -h)
     }
```
