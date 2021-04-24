```
$ yarn
$ yarn workspaces foreach --all exec sh -c 'basename $(pwd) && yarn tsc --version'
➤ YN0000: yarn-berry-failure
➤ YN0000: Version 4.2.4
➤ YN0000: inner-root
➤ YN0000: Usage Error: Couldn't find the node_modules state file - running an install might help (findPackageLocation)
➤ YN0000:
➤ YN0000: $ yarn run [--inspect] [--inspect-brk] <scriptName> ...
➤ YN0000: package-b
➤ YN0000: Usage Error: Couldn't find the node_modules state file - running an install might help (findPackageLocation)
➤ YN0000:
➤ YN0000: $ yarn run [--inspect] [--inspect-brk] <scriptName> ...
➤ YN0000: package-a
➤ YN0000: Version 4.2.4
➤ YN0000: Done in 2s 23ms
```
