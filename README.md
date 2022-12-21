Bashe - Simple Shell

bashe is a simple UNIX command language interpreter that reads commands from either a file or standard input and executes them.

Usage: bashe [filename]

To invoke bashe, compile all .c files in the repository and run the resulting executable:

gcc *.c -o bashe
./shellby

Shellby can be invoked both interactively and non-interactively. If bashe is invoked with standard input not connected to a terminal, it reads and executes received commands in order.
