Shortcuts
=========

A plug-and-play bashrc-like script that can be sourced on linux startup shells. The expectation is to source this in your `.bash_profile` or `.bashrc` or `/etc/bashrc` like so:

    [[ -s /path/to/shortcuts ]] && source /path/to/shortcuts

### Extending

A good use case is to extend the `shortcuts` script by adding internal commands used by your team and having it sourced as part of your dev environment setup!

### Contributing

Fork the repo, add more shortcuts and send me a pull request. I'll try my best to put them in on time. Make sure you update the README with comments about the shortcut(s) you add [below ▼](https://github.com/nitindhar7/shortcuts#list-of-shortcuts)

### License

Released by [Nitin Dhar](http://nitindhar.com/), © 2014, under the [MIT-LICENSE](https://raw.github.com/nitindhar7/shortcuts/master/MIT-LICENSE).

* * *

### List of Shortcuts

Features you get from this are:

##### Function shortcuts

- `function parse_git_branch()`: Parses current git branch
- `function proml()`: Sets up the prompt to display current git branch and adds coloring

##### Command aliases

- `alias ll`: List files with details
- `alias la`: List files with details including hidden files
- `alias reload`: Sources ~/.bashrc
- `alias bashrc`: Opens ~/.bashrc in `nano`
- `alias catbashrc`: `cat`s ~/.bashrc to `stdout`
- `alias lessbashrc`: `less`s ~/.bashrc
- `alias grep_search`: Run a case-insensitive pattern grep recursively and show file numbers
- `alias gitl`: Show graph of git logs with short commit hash, message, date, tags, etc
- `alias gitfo`: Fetch origin from a git repo
- `alias gitpom`: Pull `origin master` from a git repo
- `alias gitfopom`: Fetch origin and then pull `origin master` from a git repo
- `alias gitfopo`: Fetch origin and then pull whatever branch is given from the origin of a git repo
- `alias pp`: Run the [Python Json.tool](http://docs.python.org/2/library/json.html)
- `alias build`: Quietly clean and install a Maven project
- `alias pbuild`: Clean, compile and setup Intellij Idea files for a [Play Framework](http://www.playframework.com/) project