## assembly hello world

I was curious to know a little about Assembly because it is a low-level language, and I did the traditional "hello world" program.<br>
I learned it takes several lines of code to print a message on the screen.

In order to create an object file, use the following command:

```bash
  $ nasm -f elf32 -o hello_world.o hello_world.asm
```

Make the hello_world.o executable:
```bash
  $ ld -m elf_i386 -o hello_world hello_world.o
```

Run the hello_world program:
```bash
  $ ./hello_world
```

Credits to [John Hammond](https://www.youtube.com/watch?v=HgEGAaYdABA&ab_channel=JohnHammond).
