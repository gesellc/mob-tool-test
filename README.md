https://github.com/jlangr/pubmob

https://github.com/remotemobprogramming/mob

## How does it work?

- `mob start` creates branch `mob-session` and pulls from `origin/mob-session`
- `mob next` pushes all changes to `origin/mob-session`in a `mob next [ci-skip]` commit
- `mob done` squashes all changes in `mob-session` into staging of `master` and removes `mob-session` and `origin/mob-session`

- `mob start 10` and creates a ten minute timer
- `mob start 10 share` and activates screenshare in zoom (macOS or Linux with xdotool, requires zoom configuration)
- `mob status` display the mob session status and all the created WIP commits
- `mob reset` deletes `mob-session` and `origin/mob-session`
- `mob share` start screenshare with zoom (macOS or Linux with xdotool, requires configuration in zoom to work)

### Zoom Screenshare

The `mob share` feature only works if you activate make the screenshare hotkey in zoom globally available, and keep the default shortcut at CMD+SHIFT+S (macOS)/ ALT+S (Linux).


# Custom branch

- making the change easy
- making the change

- making another thing easy

