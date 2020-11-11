#Improved Git integration in GNU nano
A bunch of macros I wrote because manually using Git with the execute command kind of sucks and having to exit GNU nano just to use Git is kind of inefficent.

##What are the macros?

- `M-?` opens up a new buffer
- `M-!` shows you the git status in a new buffer
- `M-@` shows you the git log in a new buffer
- `M-1` initializes Git
- `M-2` uses the contents of a buffer as file names and adds them
- `M-3` uses the contents of a buffer as a message and runs `git commit`
- `M-4` uses the contents of a buffer as the commit ID and runs `git revert`

##How to install

Just replace your nanorc with this one.
