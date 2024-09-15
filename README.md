Kaal - A Lightweight Version Control System

Kaal is a minimalistic, custom-built version control system inspired by Git, written in Node.js. It allows users to track file changes, create commits, and log the history of their project in a simple, user-friendly manner.

Features:
Init: Initializes a .kaal folder in your project directory to track files and commits.

Add: Stages files for the next commit by hashing the file content and storing it in the .kaal/objects directory.

Commit: Commits the staged files with a message and creates a unique commit hash, updating the .kaal/HEAD.

Log: Shows the commit history, displaying commit hashes, timestamps, and messages.

Show: Displays the differences between a specified commit and its parent using a diffing algorithm.
