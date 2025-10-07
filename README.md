# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

A good technical explanation often uses a metaphor to help others understand a complex concept. Choose a metaphor to represent a Git commit. 

In a few brief paragraphs, use your chosen metaphor to explain:
* What a commit is
* How a commit is created (include the command-line syntax)
* Why commits are useful in version control.
* Why it is important to write descriptive clear messages in team settings.

### Response 1

A commit is a **set of instructions** that tells Git to **save changes** of a code to a repository. Imagine that you are playing in the violin section of an orchestra. Once you get your own violin sheet music, you realize that you need to add bowings, which are notes that remind you which direction your bow should move during different parts of the piece. In an orchestra, it’s standard practice for the entire section to use the same bowings so everyone moves together. 

After you write in your bowings, you need to communicate those changes to your section. A commit works in a similar way. The bowings you wrote changed how the music is read, just like editing a .js file makes changes to your code. Once those changes are made, you need to save and share them, the same way you would communicate your bowings to your section. Including a message in your commit is like explaining what bowings you changed, where you changed them, and why.


A commit is created with the following commands:

```js
git add [insert file name]
git commit -m "[message that explains changes to the code]"
```

Commits are useful because they keep track of **different versions of your code**. If you ever need to go back to a previous version, you can review your commit history. When bowings are decided in a violin section, there may be several possible versions but once one is chosen, it’s difficult to revert back later. Commits allow you to move freely between past versions of your code whenever needed.

Commit messages are also important because they provide **clear explanations** of what changed in each version. If you or your team ever need to return to a specific point in your project, descriptive messages make it easier for everyone to understand the history of the code.