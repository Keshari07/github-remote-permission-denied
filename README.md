# github-remote-permission-denied

onfiguration can be achieved by using the git config command. Specifically, you need to provide your name and email address because Git embeds this information into each commit you do. You can add this information by typing:

    git config --global user.name "Your Name"
    git config --global user.email "youremail@domain.com"

You can display all the configuration items that have been set by typing:

    git config --list

Output
user.name=Your Name
user.email=youremail@domain.com
...

The information you enter is stored in your Git configuration file, which you can optionally edit by hand with a text editor of your choice. This example uses nano:

    nano ~/.gitconfig

~/.gitconfig contents

[user]
  name = Your Name
  email = youremail@domain.com

Press CTRL and X, then Y then ENTER to exit the nano text editor.

There are many other options that you can set, but these are the two essential ones needed. If you skip this step, you’ll likely see warnings when you commit to Git. This makes more work for you because you will then have to revise the commits you have done with the correct information.

github-remote-permission-denied
