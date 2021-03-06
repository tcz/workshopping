Workshopping
============

Workshopping is a useful little tool for code workshops saving your students from typing the code.

## Usage

    ./workshopping repository_path

## Requirements

- Linux box to run
- PHP installed and available at `/usr/bin/php`

## How it works

1. Prepare your workshop as a git repo. Add small steps (not bigger diff than a screen) as commits with descriptive commit messages. Try to stick to the master branch.

2. Ask students to clone your repository.

3. Ask them to get and execute `workshopping` with the repository path as parameter.

4. They can now navigate in your repo with UP and DOWN buttons seeing the diffs between commits and the messages. ESC exists the view and leaves the repository with the last selected commit, allowing to try the code in that state and return to `workshopping` after that.

