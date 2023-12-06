# Contradictions Bible Quiz

An HTML quiz designed to highlight contradictions in the Bible. Give it to your Bible-loving friends and see how they perform!

* The quiz will show a number of Bible questions, in random order.
* The quiz is multi-choice, with each question having exactly two answers.
* No matter what option the user picks, they are told they are ❌**Wrong**.
* Scriptural citations are given to show the user why they are wrong, with links to chapter and verse.
  * This is the gimmick of the quiz. ***These citations are correct.*** The reason both answers can be wrong is because the Bible contains [contradictions](https://skepticsannotatedbible.com/first/contra2_list.html). In other words, for the questions in this quiz, there are at least two valid answers. We show the user scriptural refernces to the answer they did not pick.
    * A friendlier, kinder version of this quiz could let every answer be ✅Correct. But what's the fun in that?
* Browser [local storage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) is used to lock in previously-made answers, and keep the order of the questions static.  
  * This feature was implemented to make it harder for a user to discern the "always wrong" nature of the quiz. If they could refresh, they might quickly discover that both answers to a particular question are wrong. If they can't do this easily, they are more likely to continue engaging with the quiz.
  * There is a link secreted away at the bottom of the quiz to reset it. There are also other technical ways to circumvent it (e.g. Incognito mode). It's not meant to be uncrackable, simply "hard enough" to the average user.

# Inspiration

This project was inspired by:

1. [This video](https://www.youtube.com/watch?v=RB3g6mXLEKk) by [NonStampCollector](nonstampcollector.com).
1. The [Contradictions Page](https://skepticsannotatedbible.com/first/contra2_list.html) on [The Skeptic's Annotated Bible](https://skepticsannotatedbible.com/).

# FAQ

1. ***I want to add my own questions!***<br/>Go ahead! This is on GitHub. [Fork it!](https://heardlibrary.github.io/digital-scholarship/manage/control/github/fork/)
