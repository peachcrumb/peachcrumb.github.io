---
layout: essay
type: essay
title: "The Elementary Teacher Lied to You"
# All dates must be YYYY-MM-DD format!
date: 2025-01-30
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<div class="text-center p-4"><img width="600px"" src="../img/pigeon.png"></div>  

## There are stupid questions

If you ever heard a teacher excitedly spouting about there being no stupid questions, either they had extremely little real-world experience (doubtful), or just said that to encourage class participation. Questions that can sometimes be considered 'stupid' are found throughout numerous areas in life. Let’s examine some specific examples and see how they can be improved or avoided.

## Reform your question and increase answerability

In life, when it comes to using the command-line to execute your statements or change the shell (something the [forums guide](http://www.catb.org/esr/faqs/smart-questions.html#idm568) specified not to ask!), StackExchange and likely one of its many sites in the family will have the answer for specific enough questions. The following question was found on the Apple Ask Different page since it was specifically regarding shells in Terminal. See how [this question](https://apple.stackexchange.com/questions/334542/zsh-vs-bash-shell-in-terminal) is missing pieces and clearly needs improvement:

```
Q: Zsh vs Bash shell in Terminal  

Are there any advantages to using zsh vs bash shell in Terminal app? Also, can you use zsh from the terminal? My understanding of zsh is skewed.
```

And if there isn’t time to check the link to the question itself, note that it was a duplicate or already existing question within the forum site (lending to its stupidity factor… may I say stfw). This question is bare-bones at best, given that it is missing:  
1) Evidence of attempting to answer their own questions
2) Specifications of what they need exactly
3) Background information on what they already know – in this case they only provide "My understanding of zsh is skewed"... Great! Give us nothing to work with, why don't you!?!

It also contains a yes/no type of question within the post, which can be considered unnecessary. Thankfully, a couple of people were gracious and answered the silly question with the following: 

```
Q: Are there any advantages to using zsh vs bash?
A: Both have their own unique set of features. It's upto you to choose a shell. Bash is the default login shell set for users in macOS whereas zsh is also available.

Q: can you use zsh from the terminal?
A: Yes. Simply type zsh in Terminal to start Zsh shell. You can also set zsh as your default shell by going to System Preferences app → Users & Groups right click on your account name and choose Advanced Options....

Choice of shell is a subjective matter. However, if you are a command line newbie, it's recommended to stick with Bash shell.
```
 
The answers were detailed and civil, and the one referenced above even included an image for reference. Next time, this poster should utilize Google first before creating a duplicate question, and figure out if they need to largely narrow what they are looking for before or as they draft their post.

## How to avoid asking a stupid question

[Here](https://apple.stackexchange.com/questions/388622/zsh-zprofile-zshrc-zlogin-what-goes-where) is another question on a similar topic within the same StackExchange site, but better formatted likely due to the author being more well-informed before posting:

```
Q: ZSH: .zprofile, .zshrc, .zlogin - What goes where?

Now that I've upgraded to Catalina and I am using the new ZSH shell, I've noticed that ~/.bash_profile has been replaced with ~/.zprofile and since installing iTerm2 shell integration, it added a ~/.zshrc file.

Looking at the ZSH documentation on Startup/Shutdown Files, there are a number of files (located in the home directory $HOME or ~/):

.zprofile (login shell)
.zshenv (environment variables)
.zshrc (interactive shell)
.zlogin (login shell)
.zlogout (when the shell exits)
What is also confusing is that ~/.zprofile and ~/.zlogin are both for login shells, so, things can get confusing as to what to put where.

What startup/shutdown files should be used when setting up the ZSH shell environment and how/what should they be configured?
```

Unlike the first example, this user explained what information was already known and things they tried before posting the question. They also precisely included what they needed help with, being "What startup/shutdown files should be used when setting up the ZSH shell environment and how/what should they be configured?". Since I found this question from my past Google searches because I was a beginner also confused by the differences between the different shells, I can understand why searching even with background knowledge may not immediately yield the most direct answer. Needless to say, they received one detailed and relative answer, which is as much as you can hope for when posting a 'smart' question to the internet.

## Final thoughts

From the examples above we see both the smart and not-so-bright ways to pose a question. We can conclude that including as much relevant information as possible and exhausting all other available resources before asking are the best strategies to get much closer to the answer one is looking for (rather than a vague or largely unhelpful one). In recent years and perhaps at times throughout the overall history of the internet, we've seen hyperspecific moments (like the commenters for both of these questions) where other users are generous and willing to respond regardless of the level of intelligence or thought input into the question. However, it cannot always be expected that people will be courteous online, and therefore we should do our best in serious forums to ask efficient questions so as not to waste our or everyone else's time and possibly avoid discomforting or hostile conversations.
