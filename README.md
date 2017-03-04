# Tutorial

This is my tutorial repository.

I will add a github desktop tip.

When I first used github desktop for Mac, everything went well. But for some reasons I did not know, I got a **Git Error** message.

> Git Error  
> git config --global user.email "you@example.com"  
> git config --global username  

I opened a terminal and typed the command above, but I got another message which told me to install **XCode** and **command line tools**. Oh NO!

Then I googled this Error message. Below is the solvation.

1. goes to user's home directory `~`
* open the `.gitconfig` file with your favorite editor. (*use `shift+cmd+.` to view hidding files*)
* in the **[user]** block, add two lines as
    * `name = ***` your github username, which usually exists.
    * `email = ***` your email address, which missing cause the error.
* save and close the `.gitconfig` file and run the github desktop again.