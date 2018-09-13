# Practice Using Command-Line Style Path Names

## Learning Goals

- Practice Opening Files in Complex Directories
- Become Comfortable Using Single-Line Pathways

## Objective

Using the provided ruby script, add file paths that allow the script to access several `.txt` files across a git project. Once all of the files have been successfully opened, the console will print a new message.

## Why Do I Need to Know This?

As your projects grow and you begin to use external files, knowing how to write a correct file path is essential. Additionally, being able to write a full file path in one line will help you to use the command-line more efficiently. This activity is themed after the world of Winnie the Pooh, but don't worry: you can complete this activity even without knowledge of the books or cartoons!

## Let's Do It!

The only file you should be editing is `lets_find-eyores-tail.rb`. You are going to fill in the string declarations at the top of the file. Each of those paths will lead to a file that ends in `.txt`.

For each character whose `.txt` you navigate to, a new piece of ASCII art will be printed to the terminal. There are four unique characters, and once they have all been "found", a fifth character from Winnie the Pooh will be printed to the console, indicating that you have completed the assignment.

If you want an additional challenge to test your skills, try moving `lets-find-eyores-tail.rb` from the Six-Pines folder to another folder, running it again from the new location.

## What If I can't Find Winnie the Pooh?

You have fallen into the Heffalump Trap. There are two folders in this project called Heffalump-Trap, and one is hidden when you use finder. If you need more information, read about hidden files and folders below.

## Bonus Learning

### Hidden Files and Folders

Sometimes, there are files or folders that you want to include in a project that you don't necessarily want any old user to mess with. Since your application is running on someone else's computer though, you have limited means to deny your customers access.

Enter hidden files and folders! In iOS, any file or folder whose name begins with a `.` is hidden when using the Finder app. They are visible to programs like Atom, but end users don't see them unless they go looking for them.

### The Heck is ASCII

Back when computers were very expensive and mostly existed in universities or military installations, there was no standard way of representing numbers or letters with binary. Over sixty different methods of encoding were used by different institutions, and learning the encoding for other machines made portable programs a practical impossibility. By request, the American National Standards Institute put together a committee to create a convention that could be used in all computers in the United States.

What they came up with was called ASCII (usually pronounced 'ask-y'), short for American Standard Code for Information Interchange. When people talk about ASCII art, or an [ASCII table](http://www.asciitable.com/), they are referring to this (old) standard that was used to represent characters.

Most systems have been switched out of ASCII, because ASCII is suited exclusively to English. Unicode has created a successor, or rather, a set of successors: UTF-8, UTF-16 and UTF-32. UTF stands for Universal Text Format, and the number following represents the amount of bits that the encoding needs per character.
