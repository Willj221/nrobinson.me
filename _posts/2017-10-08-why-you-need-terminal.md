---
layout: post
title: "Why You Need Terminal"
date: "2017-10-08 10:32:37 -0400"
---

<center><img src="/images/terminal/title.png"></center>

**The Terminal,** also known as the command line or a Terminal emulator, is an essential component of any useful operating system. It is by far one of the most important applications on Mac and Linux. The Terminal provides an efficient interface to access the true power of a computer better than any graphical interface.

**When opening a terminal** you are presented with a shell. On Mac and Linux this shell is Bash, but other shells can be used. (I'll be using Terminal and Bash interchangeably from now on.)

<br>
<center><img src="/images/terminal/bash.svg"></center>
<br>

**The interactive prompt** is one of the primary methods of using a shell. The most convenient feature of a shell is that it operates with a working directory, which means you can navigate your file system and the shell will keep track of where you are. Bash can create directories (folders) and files with ease, and it is more straightforward than using a graphical file manager.

**You can use Bash to** run many programs and execute many many files. Often executable files are called commands. Commands can take input in the form of arguments or interactively, and can perform operations and print output. Bash is powerful because of the methods it has to link and chain commands together.

**Bash is also** a scripting language, which means you can create executable files called scripts that can run multiple commands, support control structures, variables and much more. Scripts are useful for automating processes or creating an easy way to perform many tasks with a single command.

<center><img src="/images/terminal/bashrc.png"></center>

**Bash can be used** to do amazing things but at the cost of responsibility. If you command it to do an undesired command sequence it will proceed and execute without hesitation, which may lead to unintentional or damaging effects. When using Bash you are executing the power you have over the computer. Use Bash responsibly, and if you are unsure what something does, don't paste it into your terminal. Be smart and google it, or read the manual for the command. **Use caution. The last thing you want to do is compromise your computer.**

**The Terminal is a tool,** not an application, meaning that it can be regarded as a lifestyle. I always have a terminal or two open in the directory of a project. I navigate to the project in a terminal, and then use the terminal to launch graphical applications with the project as the current directory. This is much quicker and less cumbersome than the reverse, which can take much longer. Imagine the time that is wasted and the clicks that are used to open a graphical code editor, click File->Open, navigate to the project, click Open, wait for the folder to be opened, and then finally open a terminal and jump to the project directory so you can run your code. With my method, I can run `atom .` in my terminal to launch [Atom](https://atom.io). My terminal remains in the background, and I can come back to it to run the code and debug.

<center><img src="/images/terminal/atom_1200px.png"></center>
<br>

**Terminal fluency** is an essential skill that no developer should go without. Using a computer without using terminal is like driving a car without using the steering wheel. (I hate it when people use vehicles to make computer analogies but they're an efficient way to get a point across.) Every developer should take the time to familiarize themself with terminal if they haven't done so already, as it is a truly rewarding skill. You'll amaze yourself with what you can achieve and the time you can save by creating scripts and commands to automate or expedite tasks in your workflow.

**Using terminal** puts you in full control of your computer and your workflow, and I highly recommend using it whenever possible. I use it every day and I love it.

---------

## Why Bash is important to me

<center><img src="/images/terminal/po.png"></center>

My most popular open source project is a Bash script, and has over 70 unique users. It's called po-util, and provides an easy method for installing and using the [local Particle toolchain](https://github.com/spark/firmware/) to compile code for Particle's entire suite of [Wi-Fi](https://www.particle.io/products/hardware/photon-wifi-dev-kit), and [cellular](https://www.particle.io/products/hardware/electron-cellular-dev-kit) IoT development boards. It includes many features for project, library, and device management, and can be installed on Mac and Linux by running the following command:

{% highlight bash %}
$ bash <(curl -sL master.po-util.com/install)
{% endhighlight %}

Check it out on [GitHub](https://github.com/nrobinson2000/po-util), or on [po-util.com](https://po-util.com).
