# 6900-autotest
To use, run `autotest-6900` in your current directory.

## Assumptions
Your dir structure and build files must be able to run from `build/`:
build/
    output-elf64

Under the hood, this tool simply runs your `output-elf64` with a bunch of different inputs
Your mark usually depends on how many of the inputs succeed in matching the output.

IF YOU HARDCODE YOUR LOGIC, YOU TECHNICALLY GET ZERO! YES YOU GET ZERO
SO DONT DO SOMETHING STUPID
