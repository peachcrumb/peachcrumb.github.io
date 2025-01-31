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

<img width="600px" class="rounded float-start pe-4" src="../img/pigeon.png">  

## There are stupid questions

If you ever heard a teacher excitedly spouting about there being no stupid questions, either they had extremely little real-world experience (doubtful), or just said that to encourage class participation. Questions that can sometimes be considered "stupid" are found throughout numerous areas in life. Let’s examine some specific examples and see how they can be improved or avoided.

## Reform your question and increase answerability

In life, when it comes to using the command-line to execute your statements or change the shell (something the [forums guide](http://www.catb.org/esr/faqs/smart-questions.html#idm568) specified not to ask!), StackExchange and likely one of its many sites in the family will have the answer for specific enough questions. The following question was found on the Apple Ask Different page since it was specifically regarding shells in Terminal. See how [this question](https://apple.stackexchange.com/questions/334542/zsh-vs-bash-shell-in-terminal) is missing pieces and clearly needs improvement:

```
Q: Zsh vs Bash shell in Terminal  

Are there any advantages to using zsh vs bash shell in Terminal app? Also, can you use zsh from the terminal? My understanding of zsh is skewed.
```

And if there isn’t time to check the link to the question itself, note that it was a duplicate or already existing question within the forum site (lending to its stupidity factor… may I say stfw).

```
A: datetime and the datetime.timedelta classes are your friend.

1. find today
2. use that to find the first day of this month.
3. use timedelta to backup a single day, to the last day of the previous month.
4. print the YYYYMM string you're looking for.

Like this:

 >>> import datetime
 >>> today = datetime.date.today()
 >>> first = datetime.date(day=1, month=today.month, year=today.year)
 >>> lastMonth = first - datetime.timedelta(days=1)
 >>> print lastMonth.strftime("%Y%m")
 201202
 >>>

```
 
The asker received six possible answers, and he or she was successful in inciting discussion from multiple users. The answers themselves were clear and were devoid of the rumored sarcasm and hostility of “hackers.” Since I myself have referenced this page and found it useful, I can confidently say that it is a good question.

## How to avoid asking a stupid question

While there are decent questions that benefit everyone, there are those one can ask to create an entirely different effect. In the following example, a user asks how he would, in short, create a desktop application with Facebook.

```
Q: Facebook Desktop Notifier

I am a beginner programmer that have never used anything other than what's included in a language.

I am trying to create a desktop application that notifies me anytime I get an update onfacebook. 
How should go about doing this? Thanks in advance.

edit Sorry I was not clear. Is there any way to make a DESKTOP application with facebook?
```

A simple “yes” would have answered the question, but we know that’s not the sort of answer he or she is looking for. Fortunately, someone kindly responded with a link to Facebook’s developer website. The asker should have done more research on his or her potential project. Then further down the road, he or she could have asked more specific and detailed questions that wouldn’t require a thousand-paged response for a sufficient answer.

## Conclusion

When we rely on others’ generosity and expertise to provide answers to our questions, it should hold that the question we ask should be one that leads to efficient and effective help that not only benefits us, but also the people we ask and others who might ask the same question in the future. Thus, if you have a question… make it a smart one! Asking questions may not always get you the best answer, but asking them in a way that will make others want to answer them will increase the success of finding a good solution and make it a positive experience on all sides.
