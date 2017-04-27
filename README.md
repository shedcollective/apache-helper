# Apache Helper

A simple tool for managing Apache; works out the fiddly bits so you don't need to remember where things live.

## Installation

### Using Homebrew
1. Tap Nails using `brew tap shedcollective/utilities`
2. Install using `brew install apache`
3. Update as normal using `brew update && brew upgrade`

### Manually

1. Clone this repository
2. Create a symlink of the executable
3. Place the symlink somewhere in your PATH
4. To update, simply `git pull origin master`

## Usage
```
apache config  - Opens Apache's configuration file in your default editor
apache test    - Tests Apache's config
apache restart - Restarts Apache (using -k)
apache error   - Opens the error log (using tail -f)
apache access  - Opens the access log (using tail -f)
apache help    - Prints this help screen
apache .*      - Passed directly through to sudo apachectl
```
