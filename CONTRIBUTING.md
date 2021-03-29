# Contributing
Thank you for reading this. It's really important that this guide is kept accurate and up to date, especially when Minecraft and plugins change frequently and require updates.

### Submitting changes
To submit a change to this guide, you can do so via [Pull Requests (PRs)](http://help.github.com/pull-requests/).
Please send a [PR here](https://github.com/osdiscord/minecraft/pull/new/master), accurately explaining the changes you made with a clear list. Follow our writing conventions below to ensure that your PR is merged efficiently.

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:
```
$ git commit -m "A brief summary of the commit
> 
> A paragraph describing what changed and its impact."
```

### How to add pages
To add a new page to the guide, create a ``file-name.md`` file inside a folder of your choice. 

## Guidelines
Because we want to keep everything as consistent and clean as possible, here are some guidelines we strongly recommend you try to follow when making a contribution.

### Spelling, grammar, and wording
Improper grammar, strange wording, and incorrect spelling are all things that may lead to confusion when a user reads a guide page. It's important to attempt to keep the content clear and consistent. Re-read what you've written and place yourself in the shoes of someone else for a moment to see if you can fully understand everything without any confusion.

Don't worry if you aren't super confident with your grammar/spelling/wording skills; all pull requests get thoroughly reviewed, and comments are left in areas that need to be fixed or could be done better/differently.

### "You"/"your" instead of "we"/"our"
When explaining parts of a guide, it's recommended to use "you" instead of "we" in most situations. For example:

```diff
- To check our balance, we can run ``/bal``.
+ To check your balance, you can run ``/bal``.

- To send a message, we can do ``/msg``.
+ To send a message, you can do ``/msg``.

- Our command should look like this: ...
+ Your command should look like this: ...
```

### "We" instead of "I"
When referring to yourself, use "we" (as in "the writers of this guide") instead of "I". For example:

```diff
- If you don't already have some knowledge of Towny, I would highly recommend reading this guide.
+ If you don't already have some knowledge of Towny, we would highly recommend reading this guide.
# Valid alternative:
+ If you don't already have some knowledge of Towny, it's highly recommended that you read this guide.

- In this section, I'll be covering how to do that really cool thing everyone's asking about.
+ In this section, we'll be covering how to do that really cool thing everyone's asking about.
```

### Inclusive language
Try to avoid gendered and otherwise non-inclusive language. Examples are:

 - Whitelist -> Allowlist
 - Blacklist -> Denylist
 - Master/Slave -> Leader/follower, primary/replica, primary/secondary, primary/standby
 - Gendered pronouns (e.g. he/him/his) -> They, them, their
 - Gendered terms (e.g. guys) -> Folks, people
 - Sanity check -> Quick check, confidence check, coherence check
 - Dummy value -> Placeholder, sample value
 
## General styling

### Images and links
If you want to include an image in a page, the image you add should be saved to the repo itself instead of using external services. If you want to link to other sections of the guide, be sure to use relative paths instead of full URLs to the live site. For example:

```diff
- Here's what the final result would look like:
-
- ![Final result](https://i.imgur.com/28xPGgM.png)
-
- If you want to read more about this, you can check out the page on [that other cool stuff](https://github.com/osdiscord/minecraft/README.md).

+ Here's what the final result would look like:
+
+ ![Final result](~@/images/28xPGgM.png)
+
+ If you want to read more about this, you can check out the page on [that other cool stuff](/README.md).
```

### Commands and other code snippets
To make the guide easier to read and navigate for users, commands and other code snippets you use should be in code blocks. There are a few types of codeblock:

\`\`Short text codeblock\`\` -> ``Short text codeblock``

\`\`\`
Long text codeblock
that works on multiple lines
\`\`\`
->
```
Long text codeblock
that works on multiple lines
```

## Other Markdown features
Of course, there are Markdown features that aren't covered in this contribution guide. If you want to find more examples of how to style your text, go to [this helpful guide by GitHub.](https://guides.github.com/features/mastering-markdown/)

Happy contributing!
