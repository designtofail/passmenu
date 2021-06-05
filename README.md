# passmenu

`passmenu` is a [dmenu][]-based interface to [pass][], the standard Unix
password manager. This design allows you to quickly copy a password to the
clipboard without having to open up a terminal window if you don't already have
one open. If `--type` is specified, the password is typed using [xdotool][]
instead of copied to the clipboard.

# Usage

    passmenu [--type] [dmenu arguments...]

 http://tools.suckless.org/dmenu/
 http://www.semicomplete.com/projects/xdotool/
 http://www.zx2c4.com/projects/password-store/
