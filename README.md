# hangman8086

<p align="center">
  <img src="screenshots/hello.png">
</p>

## First things first
You must have [emu8086](http://www.emu8086.com/) and [DOSBox](https://www.dosbox.com/) installed.

## Understanding its crazy and messy code
We admit it: this won't be the prettiest code you'll see. But if you're not familiarized with`8086 instruction set`, here's a [guide](http://www.electronics.dit.ie/staff/tscarff/8086_instruction_set/8086_instruction_set.html) for you. And, if you like a little bit of history, this [book](https://github.com/gurugio/book_assembly_8086) is very nice too.

## Compiling and running it
To compile it, you don't even need to understand assembly. To make things *easy* for you, we really recommend that you create a directory inside **C:\\** partition. In this example, let's call it *"temp"*. Then, just open `main.asm`  using `emu8086` and click in that nice button called "compile". After that, you just need to wait a little bit and a window will pop up. Choose the directory you created and ~~be happy~~ save inside of it. 

Since this game is **graphics mode only**, you'll need to run it using `DOSBox` - but you can also execute it on `Command Prompt (CMD)`, for example. It won't run in any version after `Microsoft Windows XP`, though. Considering you're using `DOSBox`, follow the next steps accordingly:

- **Mounting `C:\` partition**
```shell
Z:\> mount c: c:\temp
```
- **Entering `C:\`**
```shell
Z:\> c:
```
- **Running the game**
```shell
Z:\> main
```

That's it!

## License
Released under the [GPLv3](LICENSE) license.
