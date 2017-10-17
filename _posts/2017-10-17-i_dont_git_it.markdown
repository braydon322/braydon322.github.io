---
layout: post
title:      "I don't GIT it."
date:       2017-10-17 23:18:34 +0000
permalink:  i_dont_git_it
---


Beginning this school I had literally zero understanding of what Git or Github was. 

I knew github as some sort of hangout for geeks, but had no clue in terms of why people liked to hang out on such a confusing platform. I decided early on that I was going to approach my learning very fast paced, but if necessary that I would go back and review the information I did not understand.

Being almost 400 lessons through the program (about half way) I realized that my knowledge of Git and Github really hadn't increased all that much. Yes, I now understood what the Language and Platform did, and yes I now understood why so many people hung out on such a platform... but I did not know the ins and outs. Everytime I would fork and clone a repository I would have to go and look up a tutorial here or there just to get me through the few simple steps of connecting my IDE to Github.

I recently just completed my Sinatra Final Project which consisted of a CRUD program(Create. Read. Update. Delete) written in ruby and the Sinatra interface. Having done such, I can honestly say I now have a much better understanding of that beast Git. I decided writing a blog post on it would solidify my understanding even more.

# 1. Starting your project.

There are two options when it comes to starting a project. 

You can create a brand new repository, and start from scratch... or you can fork and clone someone elses already created repo. 

I prefer the first because it gives you a perfectly clean slate in which you can begin programming. However, I would suggest that if you have a hard time with setting up the correct layout and structure of programs and applications in ruby, that you look through the already created gems certain users have put together to help people like you. These gems can provide quick one word commands that will help you set up the tree layout for your application. 

# 2. Connecting to your IDE.
Personally, I love atom. I love the flexibility and ease of use of the program and for me it is my go to. 

There are many others out there that could be a great fit for you. Sublime is another great option. However if you're looking for flexibility and a nice designed feel, I suggest checking out atom.

Once you have your IDE figured out you want to go ahead and Clone the Repo you've just forked, or create.

# 3. Cloning
This can be done quite simply following a few quick steps.

Go to the newly cloned or created repo and search for the green button that says 'Clone or Download'.

Click that button, and you should be presented with something along the lines of this:

      git@github.com:your-username/your-repo-name.git

You'll want to go ahead and copy that, then open up your editor.

Type in the following command followed by the SSH Key you just copied.

      git clone ' YOUR SSH KEY '
			
This will now connect your editor to that online repo.

# 4. Adding in changed files.
Very simply, if you're wanting to upload all the changes you've made you're going to want to type in the following:

      git add -A
			
This will add all the updated files into your repo.

# 5. Adding 'Commits' to your repo to track changes.

This one is very important, however it is quite difficult to get in the hang of doing.

Type the following code - after you have already run the 'git add -A' command.

      git commit -m "Your Commit Message Goes Here"
			
This will now publish each individual message as you begin to make changes to your program. I would suggest committing every 5-7 lines of code, however there really is no limit on how little or significant the changes made are.

# 6. Pushing to the server.
This is probably the most important of all the commands you have just run, because without this small line of code, no commits, files, or information will ever be pushed to the server.... leaving you potentially empty handed when it comes to a published application.

Add, Commit, Push. It's very simple.

Here is the command:

      git push
			




# Now go and check!
If your code is not publishing to the server, make sure you are following my instructions step by step. It really is quite simple, however it does take some time learning and remembering the commands..

Here they are one more time.


			git add -A
			git commit "Whatever changes you have made to your files"
			git push
			
			
			
After learning these easy commands, I'll never lose my code again. Nothing is worse than a crashing application and you realizing that nothing was saved.

Commit and Push often and you'll be good.


