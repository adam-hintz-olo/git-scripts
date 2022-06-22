## git-scripts

### git-wt

A shortcut for working with `git worktree` in a more ergonomic way. Inspired by
my `tm` shortcut for `tmux` ([here](https://github.com/adam000/dotfiles/blob/master/tmux/autocomplete)).

Place this file into a directory covered by your PATH environment variable, relaunch your terminal, et voila! Invoke by typing `git wt`

In Windows, I recommend creating `~\bin`, adding that to your PATH, and sticking this file there. Three ways to do this:

* In your Powershell profile, append to the path: `$env:path += ';C:\Program Files\Git\usr\bin\'` (thanks @adam-c-anderson)
* Press the `win` key, type "Environment Variables", select "Edit the system environment variables" then click "Environment Variables..." and edit the user variable named Path.
* Paste `rundll32.exe sysdm.cpl,EditEnvironmentVariables` into a cmd / Powershell terminal to get to the same window
