# reset-volume-balance-on-wake

Resets MacOS volume balance to middle, when it wakes up.
It is a simple shell one line command that is run when OS wakes up with help of sleepwatcher daemon.

## Installation
### Wakeup script
By default sleepwatcher will look for `~/.wakeup` file which is run on OS wake up, and `~/.sleep` file, to be run, when OS goes to sleep. For more information run `sleepwatcher`, when it is installed (See Requirements).

To install the needed `~/.wakeup` script, all you need to do is to run following commands.
`TODO`

## Requirements
- sleepwatcher

How to install sleepwatcher
1. Install Homebrew, if you do not have it already. Follow instructions at https://brew.sh
2. Install sleepwatcher with homebrew. `brew install sleepwatcher`
3. Start sleepwatcher. `brew services start sleepwatcher`

# Uninstall
- Removal of sleepwatcher `brew services start sleepwatcher && brew uninstall sleepwatcher`
- Removal of wakeup script `rm ~/.wakeup`
