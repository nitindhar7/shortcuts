Shortcuts
=========

A plug-and-play bashrc-like script that can be sourced on linux startup shells. Download the file to a location you want curl or your [browser](https://raw.github.com/nitindhar7/shortcuts/master/shortcuts):

    curl -O https://raw.github.com/nitindhar7/shortcuts/master/shortcuts

Source this in your `.bash_profile` or `.bashrc` or `/etc/bashrc` like so:

    [[ -s /path/to/shortcuts ]] && source /path/to/shortcuts

* * *

### Extending

An example use case is to extend the `shortcuts` script by adding internal commands that your team uses for day-to-day redundant tasks and having it sourced as part of their dev environment setup!

### Contributing

Fork the repo, add more shortcuts and send me a pull request. I'll try my best to put them in on time. Make sure you update the README with comments about the shortcut(s) you add [below ▼](https://github.com/nitindhar7/shortcuts#list-of-shortcuts)

### List of Shortcuts

##### Function shortcuts

- `function parse_git_branch()`: *Parses current git branch*
- `function proml()`: *Sets up the prompt to display current git branch and adds coloring*

##### Command aliases

- `alias ll`: *List files with details*. Usage: `$ ll`
- `alias la`: *List files with details including hidden files*. Usage: `$ la`
- `alias reload`: *Sources ~/.bashrc*. Usage: `$ reload`
- `alias bashrc`: *Opens ~/.bashrc in nano*. Usage: `$ bashrc`
- `alias catbashrc`: *cat ~/.bashrc to stdout*. Usage: `$ catbashrc`
- `alias lessbashrc`: *less ~/.bashrc*. Usage: `$ lessbashrc`
- `alias grep_search`: *Run a case-insensitive pattern grep recursively and show file numbers*. Usage: `$ grep_search "mypattern" ./`
- `alias gitl`: *Show graph of git logs with short commit hash, message, date, tags, etc*. Usage: `$ gitl`
- `alias gitfo`: *Fetch origin from a git repo*. Usage: `$ gitfo`
- `alias gitpom`: *Pull origin master from a git repo*. Usage: `$ gitpom`
- `alias gitfopom`: *Fetch origin and then pull origin master from a git repo*. Usage: `$ gitfopom`
- `alias gitfopo`: *Fetch origin and then pull whatever branch is given from the origin of a git repo*. Usage: `$ gitfopo otherbranch`
- `alias pp`: *Run the [Python Json.tool](http://docs.python.org/2/library/json.html)*. Usage: `$ curl "http://my-json-resource.com/" | pp`
- `alias build`: *Quietly clean and install a Maven project*. Usage: `$ build`
- `alias pbuild`: *Clean, compile and setup Intellij Idea files for a [Play Framework](http://www.playframework.com/) project*. Usage: `$ pbuild`

* * *

### License

Released by [Nitin Dhar](http://nitindhar.com/), © 2014, under the [MIT-LICENSE](https://raw.github.com/nitindhar7/shortcuts/master/MIT-LICENSE).