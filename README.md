# customLint
Backend engine for applying custom Lint rules to plane text configuration files

## Goals
The goals of customLint is to provide a software solution for linting custom formated and generated configuration files using a rule driven approach. A yaml file will be provided to the program that defines the rule's and actions that need to be taken based on the outcome.

## Initial Rule Ideas
- Each line starts with some specific regex
- Another rule is that each line in the file has to be unique
- Another rule is that the start of each line needs to be unique
- Max amount of characters in a line