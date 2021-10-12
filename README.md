# zipcleaner

Removes unwanted files from ZIP files:

## Why?

Because macOS decided that it's a good idea to create these unwanted files:

- `__MACOSX`
- `.DS_Store`

## How to use

1. Save `zipcleaner.sh` somewhere into your computer (e.g., `~/00blair/gitrepos/zipcleaner/zipcleaner.sh`)
2. Give it the ability to execute (chmod +x ~/00blair/gitrepos/zipcleaner/zipcleaner.sh)
3. Symlink it along the lines of `ln -s ~/00blair/gitrepos/zipcleaner/zipcleaner.sh ~/zipcleaner`
4. Now you can run in your Terminal: `~/zipcleaner <path to ZIP file>`
