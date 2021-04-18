## The Terminal

One of the best tools for development.

### Why?
- You can do everything!
- Composition via pipe (|)
- Lots of applications (and easy to install depending on the system)
- You can create your own apps!

### CLI Applications: Unix
Some useful apps are:
- **grep**: file pattern searcher.
- **curl**: client for URLs. (`curl cheat.sh/<pattern>` is a good tool).
- **find**: find files.
- **xargs**: manipulate a list and use each element in other apps.
- **man**: manual for any application (that actually has documentation...)

### Other apps (not installed by default)
- **fzf**: amazing fuzzy finder.
- **ripgrep**: faster grep alternative written in Rust.

### Example
```bash
grep --color=auto 'export default' **/*.tsx -n | awk -F : '{ print $1" -H "$2 }' | xargs -n 3 bat
```

### TUI Applications
TODO: Work on this...

