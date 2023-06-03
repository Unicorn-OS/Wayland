sch: https://www.google.com/search?q=wayland+xvfb, https://www.google.com/search?q=wayland+headless

# Discuss:
- https://unix.stackexchange.com/questions/653672/virtual-wayland-display-server-possible
- https://www.reddit.com/r/swaywm/comments/fye83y/xvfb/

# Source:
- https://www.reddit.com/r/gnome/comments/xpadym/how_to_running_headless_mode_on_wayland/

systemctl --user start gnome-remote-desktop

gnome-shell --wayland --display-server --headless --virtual-monitor 1280x720

