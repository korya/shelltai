# ShelltAI

An AI wrapper for a Unix shell, https://en.wikipedia.org/wiki/Unix_shell, assisting developers.

TODO:

- Shallow integration:
    - Smart autocomplete of shell commands
    - Chat mode: a developer can start a dialogue to for generating the right command to achieve what they need
    - Detect and fix common mistakes; e.g. `sl` instead of `ls`
    - Interactive tool to configure a cool prompt
    - Interactive tutor to teach basic of command lines
- Deeper integration:
    - Augment output of run commands;
        - provide additional context
        - add links to files for search results; e.g. `easea` experience for grep
    - Explain the error of the last command
- Integration with other tools:
    - Convert an interactive session into a script (optionally, add “CLI” wrapping logic: flags, help messages, run linter, format code, etc.)
    - Convert an interactive session into a Docker image
    - Create an active shell session into a reproducible python environment (e.g. conda env)