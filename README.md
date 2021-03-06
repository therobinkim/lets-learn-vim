# lets-learn-vim



## Introduction



### Background

`vim` is a text editor that is built into many operating systems and henceforth built into terminals. It's rather plain and can be intimidating at first, but can be a lot of fun to learn, and when mastered, significantly improve your ability to edit text.



### Use Case 

An advanced use case might arise when you're only able to access a different computer from your terminal (eg, a server located somewhere in the middle of the ocean), and you need to edit some text files on it. With no other "regular" text editor like Sublime Text, Atom, or Visual Studio Code available, you'll have to use `vim` or a similar alternative.

A use case you may be more familiar is writing a `git commit` message when you haven't yet (or can't) [associate a non-default text editor with Git]. Trying to use `vim` without a proper introduction can be a psychological barrier and a distraction from what whatever we're trying to do. Fortunately, there are many resources out there (like the document you're reading right now) that can help guide us.


[associate a non-default text editor with Git]: https://help.github.com/articles/associating-text-editors-with-git/



### Modes

When you enter a `vim` session, your cursor will be on the first character of the document in *normal mode*. You can navigate (eg, move your cursor up/down/left/right) and manipulate text (eg, copy/paste). You can usually return to normal mode by pressing `ESC`.

*Insert mode* is designed to insert new text. You can enter insert mode from normal mode by pressing `i`, and return to normal mode by pressing `ESC`.

*Command Mode* allows us to enter commands that save the file, quit out of `vim`, etc. Type `:` from normal mode (press `ESC` to get to normal mode), and you'll see a single line at the bottom of your terminal where you can type in commands like:

* `:q` to quit*
* `:q!` to quit and discard any changes
* `:w` to write (aka save) the file
* `:wq` to write (aka save) the file and quit 

\* If you've made changes and attempt to exit with `:q`, `vim` will alert you with an error that can be avoided with `:q!` or `:wq`.

Read more about 3 new modes that `vim` introduced [here].

[here]: https://en.wikibooks.org/wiki/Learning_the_vi_Editor/Vim/Modes



### Your First Time

`vim` is often set as the default editors for many computers. Chances are, you'll accidentally stumble across it when you're prompted to write some text after running `git commit`.

If you find yourself in `vim`, I highly recommend typing the following command: `:set showmode`; when you type `:`, you will enter command mode at the very bottom of `vim`; `:set showmode` should be the entirety of the command, so there is no need to press `:` twice. Double check that your `Caps Lock` is off as `vim` is case sensitive!

To get started with writing in what's essentially a blank text file, press `i` on your keyboard to enter insert mode, and type out whatever you wanted to. Try using the up, down, left, and right keys to see if you can move your cursor while you're in insert mode. When you're done, push `:` to enable command mode ([see above]), type `wq` to write (aka save) your file and quit, and push `enter` to submit your command. You did it!

[see above]: #mode



## Learn More

To learn more about `vim` so you can thoroughly impress your friends, family, and coworkers, look up the myriad of resources available online. Remember, one of the best ways to learn something new is to *fully commit to it*! Don't be afraid to use `vim` as your text editor of choice. Below are a few I found that you can use to ease your journey into the `vim` world:



### Cheat Sheets

* https://vim.rtorr.com/
* http://vimsheet.com/
* http://www.lagmonster.org/docs/vi.html
* http://www.lagmonster.org/docs/vi2.html
* http://ryanstutorials.net/linuxtutorial/cheatsheetvi.php



### Interactive Learning Tools

* [VIM Adventures](http://vim-adventures.com/) *VIM Adventures is an online game based on VIM's keyboard shortcuts. It's the "Zelda meets text editing" game. So come have some fun and learn some VIM!*
* [Interactive Vim tutorial](http://www.openvim.com/)
* [ShortcutFoo](https://www.shortcutfoo.com/) *Learn shortcuts and commands*
* Type `vimtutor` into your terminal



## Closing

Thanks for reading this compilation of resources. Have fun learning `vim`, and please send in pull requests for any suggestions for improvements!
