# A note on operating systems

Computer tools

# Programming Environments

---

Every personal computer (i.e. laptop and desktop) comes installed with many of the most common programming languages right out of the box. However - and to be honest, this is one of the biggest, most difficult aspects of computer programming - every machine is different, and therefore behaves differently under different circumstances.

This matters because programmers are constantly looking up how to do things online, downloading tools, scripts and packages to build on and reading about how other programmers solved similar problems. Many many **many** hours have been spent stuck because the programmer didn't check that versions were compatible, or specify which operating system they were running, etc. Knowing what to search for and how to interpret results and adapt them to their specific case is probably the single best skill a programmer can have for this reason. 

Though we'd like this course is designed to be as inclusive as possible, in order to get a draft done we will be tailoring our instructions to MacOS. If you don't have a Mac, everything in here is still doable, but you'll find that specific instructions don't make sense - Windows and (less so) Linux operating systems have their own design patterns and quirks. It's not that one is right or wrong, they're just different.

If you're on a Windows machine, we ~~recommend buying a Mac~~ suggest you look into some great courses online to learn. Hopefully we'll incorporate other operating systems soon, but at the moment we want to focus on getting a completed version of the course out ASAP.

Mac users, read on as we do a quick windscreen tour of our computers.

# Graphical User Interface (GUI)

---

The graphical user interface is the way most of us use computers, and the way we all learned how. Put simply, it is the screen, plus the accompanying devices that allow us to interact (or interface) with what we see on the screen. When our computer starts up after a lengthy procession of steps that happens in a matter of seconds the computer launches a program (application) that displays on screen a way to access all the folders on our hard drive. Contained within these folders are our files - `.pdf`, `.jpg`, `.mp3`, `.doc`, `.ai`, `.app` and so on. 

When we launch Finder, for example, our Graphical User Interface (from here out, "GUI") is instructed to display the window with folders, sub-folders and files - by clicking on them we can open them (often by launching another application that is developeed to interpret those specific file types), copy them, move them around, delete them, rename them and so on.

This is not news. Any savvy computer user knows how to access the files on their computer. They know how to launch applications, create new files and save them, and so on. The reason we got into this detail, however, is that the Graphical User Interface is *simply a way to interact with the computer*, just like the **command line interface**.

# Command Line Interface (CLI)

---

The command line interface is another way to interact with your computer, capable of just about everything the GUI is, plus much, much more. On a Mac, the command line interface (from here, "CLI") is accessed using a program called Terminal, which can be found in `Applications / Utilities` in Finder, or by pressing `⌘ - space` to open the search bar, then typing 'term' ... 

> ⚠️ Beware! The Terminal  is a powerful tool, and does not have many of the safety checks the GUI has. Use with care, especially while learning!!

For example, if you delete something with the `rm` command, **it does not move to Trash** and is very difficult to get back. Seemingly innocuous mistakes can have disastrous consequences. We will talk more about the command line later, but  for now think of it as the skeleton key to your computer - the way you access and update files, and execute programs. Any good programmer is at least familiar with terminal.