# 01. Browser, Editor, and Terminal Setup

## Web Browsers

One important tool for JavaScript development (and, web development in general ) is the web browser. You probably know enough about them, but if you don't, here are the top 5 web browsers best suited for developers. You can pick up any of these to start, as you will be dealing with the others, eventually. My personal choice, Firefox Developer Edition (most of the time), although I also use Chrome a lot, and lately, Microsoft Edge too.

1. [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/). A web browser built for the open web. It offers you access to a next-generation CSS engine, an inactive CSS system that grays out CSS declarations that don’t impact the page, and more. You can also access a great JavaScript debugger, a Master CSS Grid, and various other features too.

2. [Google Chrome Dev](https://www.google.com/chrome/dev/). By far, the most used web browser. Created for the open web, Google Chrome for Developers helps developers to design websites that are specifically optimized for the next version of the digital world.

3. [Microsoft Edge](https://www.microsoft.com/en-us/edge). A good option since now it's based on Chromium (Google's open-source engine, same as Chrome). Make you sure you download and install it manually rather than upgrading through Windows Update.

4. [Opera](https://www.opera.com/). Sharing much of Chrome's DNA, Opera results in a similar user experience. A good browser.

5. [Safari for Developers](https://developer.apple.com/safari/). It might be hard to believe, but this is a very powerful tool – depending on what kind of websites and online experiences you want to build. In any case, it's the best way to ensure that your sites are going to perform good on Apple devices.

6. Bonus: 

    - [Brave](https://brave.com/). Arguably, the fastest browser around since it blocks all ads on all web pages by default. Unusual but good.

Notice that most of the these browsers offer multiple editions (Beta, Developer, etc.), which may include additional or early additions, features, etc.

## Browser Developer Tools

Developer tools are used for developing and debugging local and remote webpages. Today's browsers integrate built-in powerful developer tools, which help us build better websites, faster. These tools enable us to do a myriad of things, like inspecting and editing DOM elements (from currently-loaded HTML, CSS, and JavaScript), executing (and debugging) JavaScript pieces of code, analyzing CSS performance, monitoring real-time network traffic as your website loads, simulating mobile device rendering, and much more.

![Chrome's Developer Tools window](../images/chrome-devtools.png)

### How to open the Developer Tools in your browser

Opening the Developer Tools in your web browser is a matter of a shortcut or a couple of steps. In any case, it's a simple yet browser-dependent task. Here are three different ways to find the Developer Tools in the browser of your preference:

1. Keyboard Shortcut

    - Open the `Elements` panel

        - Windows, Linux: `Ctrl + Shift + C`

        - macOS: `⌘ + ⌥ + C` (`Command + Option + C`)


    - Open the `Console` panel (to view logged messages or run JavaScript)

        - Windows, Linux: `Ctrl + Shift + J`

        - macOS: `⌘ + ⌥ + J` (`Command + Option + J`)

    - Open the last panel you had open

        - Windows, Linux: `Ctrl + Shift + I`

        - macOS: `⌘ + ⌥ + I` (`Command + Option + I`)

    - Internet Explorer: `F12`

    > If you’ve never used the Developer Tools in **Safari** before, you will need to enable them first. You can do this by going to `Safari > Preferences > Advanced`, and check the `Show Develop menu in menu bar` checkbox. Now when you right click, Inspect Element should appear.

You can find all keyboard shortcuts at [MDN](https://developer.mozilla.org/en-US/docs/Tools/Keyboard_shortcuts).

2. **Browser Main/Menu bar**

    - Chrome, Edge:
        - Select the browser's main menu (`Alt + F`), and then select `More Tools > Developer Tools`.

    - Firefox:
        - Select the browser's main menu, and then select `Web Developer > Toggle Tools`.

    - Opera:
        - Select the browser's main menu, and then select `Developer > Developer Tools`.

    - Safari:
        - Select the browser's main menu, and then select `Develop > Show Web Inspector`.

3. **Context Menu**

    Right-click an element on a webpage (Ctrl-click on the Mac), and choose **Inspect Element** from the context menu that appears. This method straight-away highlights the code of the element you right-clicked.

### Browser's Developer Tools Official Documentation Links

- [Google Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)

- [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools)

- [Microsoft Edge DevTools](https://docs.microsoft.com/en-us/microsoft-edge/devtools-guide-chromium/open)

- [Safari Developer Tools](https://developer.apple.com/safari/tools/)

## Node.js

**[Node.js](https://nodejs.org/en/)** is a free, open-sourced, cross-platform JavaScript runtime environment that allows developers write command-line tools and server-side scripts outside of a browser. It is built on [Chrome's V8 JavaScript engine](https://v8.dev/).

You can check whether you have it already installed on your machine by running the command `node -v` from your Command Line Interface of preference.

In case you don't, you can download and install it in different ways:

- Download the [macOS/Windows Installer](https://nodejs.org/en/download/) directly from the nodejs.org website.

- For macOS, use Homebrew: `brew install node`

- For Windows, use Chocolatey: `cinst nodejs`

## npm

**[npm](https://www.npmjs.com/)** (short for **Node Package Manager**) is a package manager for the JavaScript programming language. It is the default package manager for the JavaScript runtime environment Node.js. It consists of a command-line client, also called npm, and an online database of public and paid-for private packages called the npm registry. The registry is accessed via the client, and the available packages can be browsed and searched via the npm website.

    Once you install Node.js, you will automatically get npm.

You can check whether it is already installed by running the command `npm -v`.

As Wes mentions, these technologies will be used to handle modules, dependencies, and other required processes to successfully execute the JavaScript projects for the course.

## Command Line Interface (CLI)

The **command-line interface** is a text interface to your computer. Often referred to as the *shell*, *terminal*, *console*, or *prompt*; it processes commands to a computer program in the form of lines of text. The program which handles the interface is called a **command-line interpreter** or **command-line processor**. Operating systems implement a command-line interface in a [shell](https://en.wikipedia.org/wiki/Shell_(computing)) for interactive access to operating system functions or services. So, at its core, a shell is a program that receives commands from the user and communicates them to the OS to process, and it shows the output.

You can either use your computer's integrated shell / CLI or install the one you like. With a plethora of options out there, here are a few of the most popular ones:

- **macOS:** Terminal (default zsh shell). On your Mac, do one of the following:

    - Click the Launchpad icon in the Dock, type `Terminal` in the search field, then click `Terminal`.

    - In the Finder, open the `/Applications/Utilities` folder, then double-click `Terminal`.

- **Windows:** Command Prompt. There are several ways of launching this tool on Windows.

    - Press `Windows + X` to open the *Power Users* menu, and then click *Command Prompt* or *Command Prompt (Admin)*.

    - Press `Windows + R`  to open the *Run* box. Then, type `cmd`, and click *OK* to open a regular Command Prompt. Alternatively, type `cmd`, and press `Ctrl + Shift + Enter` to open an administrator Command Prompt.

- **Linux:**

    - To open the terminal, press `Ctrl + Alt + T` in Ubuntu, or press `Alt + F2`, then type in `gnome-terminal`, and press `Enter`.

    - You can also click on the Activities item at the top left of the screen, then type the first few letters of `terminal`, `command`, `prompt`, or `shell`.

    - Other versions of Linux, or other flavors of Ubuntu, will usually have a terminal launcher located in the same place as your other application launchers. It might be hidden away in a submenu or you might have to search for it from within your launcher, but it’s likely to be there somewhere.

- **[Cmder](https://cmder.net/)** is a console emulator for Windows. It is based on amazing software, and spiced up with the Monokai color scheme and a custom prompt layout, looking sexy from the start.

- **[iTerm2](https://www.iterm2.com/)** is a great terminal emulator for macOS.

- **[Hyper](https://hyper.is/)** is a free, open-sourced, customizable terminal emulator, written in JavaScript, with the aim of providing users with a beautiful and extensible command-line interface. My personal recommendation.

### Basic CLI Commands

- **Print Working Directory:** `pwd` – Use this command to see what directory you are currently working in.

- **Change Directories:** `cd` – Use this command to navigate to a specific directory.

    - This command takes a directory path you wish to navigate to as an argument – `cd main-folder/subfolder`. Most of the time, you won't need to type the whole name of the folder you would like to navigate to; just by typing the first three characters and pressing the `TAB` key, the shell will autocomplete it for you.

    - To go one directory back – `cd ..`

    - To navigate back to your home directory, use it with no arguments.

- **List Files and Directories:** `ls` – You can know what files are in the directory you are in by using this command.

    - You can also pass in a specific directory as an argument to see all files and folders within that specific directory, like so: `ls main-folder/subfolder`.

    - You can also see all the hidden files by using the command `ls -a`.

    - You can also see all contents of a directory in long format by using the command `ls -l`.

- **Create Directories:** `mkdir` – You can use this command whenever you need to create a new folder or directory. Just pass in the name of the to-be-created folder as an argument, and it will create a new folder with that name inside whatever directory you are in.

    - 🔥 Pro Tip: Usually, you would like to create a new file/directory and move inside of it right away. You can do this in one single command by typing `mkdir newFolderName && cd $_`.

- **Create Files:** `touch` – You can use this command whenever you need to create a new file. Just pass in the name of the to-be-created file (file extension included) as an argument, and it will create a new yet empty file with that name inside whatever directory you are in.

- **Delete Files and Directories:** `rm` – This command accepts a file or directory name as an argument, and it will delete that file. Note that deleting a file via this method is an irreversible action that cannot be undone, so be cautious when using it.

    - If the directory you want to remove contains any file (is not empty), you will have to use `rm -r`. Otherwise, you could also use the `rmdir` command.

- **Move/Rename Files and Directories:** `mv` – This command accepts a file or directory name as an argument, and it will delete that file. Note that deleting a file via this method is an irreversible action that cannot be undone, so be cautious when using it.

    - Use this command to rename a file from the CLI; pass two arguments: first, the file you would like to rename, and then, the new name:  `mv oldName.txt newName.txt`. Please note that if a file with the same name as the new name you are using already existed at the moment of running the command, it will be overwritten.

    - Similarly, you can use this command to move a file from one directory to another. Just pass two arguments, the source file as the first argument and the destination directory path as the second argument: `mv contact.html /pages`.

- **Copy Files and Directories:** `cp` – You can use this command to copy a file or directory. Just pass two arguments: the file you would like to copy alongside the destination directory path: `cp boilerplate.html /pages`.

    - You can also copy multiple files at once, as long as you pass the destination directory as the last argument.

- **Clear the CLI:** `clear` – After using it for some time, your CLI might get cluttered. In that case, you can clear it all out by using this command.

- **View the Content of a File:** `cat` – Use this command followed by a file name to view the contents of that file.

- **View Manual Pages and Help for Commands:** `man` / `--help` – You can use this command to add content to a file.

    - To get more in-depth information about a command and how to use it, use the `man` command, followed by the command name. It will show the manual pages of the command. For example, `man ls` shows the manual pages of the `ls` command. To exit the manual at any given time, type `q` to quit.

    - You can also type a command name, followed by the directive `--help`, which will show you the ways in which a command can be used.

- **[Bonus] Alias (Custom Commands):** `alias` – This command allows you to create keyboard shortcuts, or aliases, for commonly used commands, like so: `alias pd="pwd"`.

## Code Editors

According [to Wikipedia](https://en.wikipedia.org/wiki/Source-code_editor), "a source-code editor is a text editor program designed specifically for editing source code of computer programs. It may be a standalone application, or it may be built into an integrated development environment (IDE), or web browser. Source-code editors are a fundamental programming tool, as the primary job of programmers is to write and edit source code. Hence, you will use the code editor daily when developing JavaScript applications."

You can use a plain-text editor, like [Notepad](https://www.microsoft.com/en-us/p/notepads-app/9nhl4nsc67wm) (for Windows) or [TextEdit](https://support.apple.com/en-me/guide/textedit/welcome/mac) (for macOS), but there exist better options out there. With tons of integrated features and extensions, these code editors will make of your coding sessions, a more productive and enjoyable experience.

### Most Popular Code Editors

- [**Visual Studio Code**](https://code.visualstudio.com/) – Commonly referred to as VS code, it is the best code editor in the market. VS code is a product of Microsoft. You can use this amazing tool either on Windows, Linux, and macOS.

- [**Atom Editor**](https://atom.io/) – Atom is a cross-platform code editor. It enables collaboration (to share your project progress) right from your editor.

- [**Sublime Text**](https://www.sublimetext.com/) – A very lightweight yet robust code editor. It is cross-platform.

- [**Brackets**](http://brackets.io/) – Brackets is a powerful yet lightweight and modern text editor.

- [**Notepad++**](https://notepad-plus-plus.org/) – Notepad++ is a free and open-source code editor governed by the GPL License. Being written in C++, it offers a smaller program size and a higher execution speed of programs.

> You can use any of these code editors either on Windows, Linux, and macOS. Except for Notepad++, which is not available for macOS.

 ### Personal Recommendations

    - VS Code + Ace Dark (Theme) + Code Saver (Font)

![Chrome's Developer Tools window](../images/vs-code-ace-dark.png)

    For Italic fans: VS Code + React Italic Theme + Cartograph CF v2 (Font).

![Chrome's Developer Tools window](../images/vs-code-react-italic-theme.png)