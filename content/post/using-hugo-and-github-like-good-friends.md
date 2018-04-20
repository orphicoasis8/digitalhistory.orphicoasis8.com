---
title: "Using Hugo and Github Like Good Friends"
date: 2017-01-01T19:56:54-06:00
draft: false
---

# Using Hugo with Github

Hugo is the program that compiles your web content (aka posts) into a website.

Hugo is completely separate from Github. Not related in any way.

All Hugo does is help you make a pretty website.

So, we can go to our terminal and enter the site directory by issuing the command

```sh
cd ~/Documents/digitalhistory.orphicoasis8.com
```

Now we can use any text editor or VS code to edit our posts

The posts are in the `content/post` folder

You can open them or create new ones with a `.md` file extension at the end.

I suggest using the hugo command since we’re here

From the terminal

```sh
hugo new post/my-new-post.md
```

Now that we have a new post to work with, we make our changes, save it and get ready to rebuild the website.

From the terminal

```
hugo
```

That’s it, the site is rebuilt and ready to be committed and pushed to Github.

---

Now in the Github GUI we need to commit our changes.

1. Enter a meaningful commit message like, "Just made the best post in the world!"

1. Then hit `Commit to Master`

1. Now push it up to the repository on Github by pressing the "Push Origin" button

Done.


