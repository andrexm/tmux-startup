# Tmux Startup
This is a startup configuration for Tmux, which starts the panes I use and some tools.
Refer to the [Tmux documentation](https://github.com/tmux/tmux/wiki) to learn about Tmux.

## How to use
First, make sure you have Tmux installed on your system. See the [Tmux installation guide](https://github.com/tmux/tmux/wiki/Installing) for installation instructions for your system. Then, after clone this repository, you need to give permissions to run the _start_ file as an executable:
```bash
chmod u+x start
```
After this, you can run it whenever you need:
```bash
tmux
./start
```

## What it does
It starts 4 Tmux panes, Helix editor and, if you are inside a Laravel project, it also starts the Lampp stack and the Laravel artisan serve. On the last pane, it opens the Ranger file manager.
