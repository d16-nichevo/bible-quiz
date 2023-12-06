# Contradictions Bible Quiz

An HTML quiz designed to highlight contradictions in the Bible. Give it to your Bible-loving friends and see how they perform!

The quiz can be accessed by clicking here:

* https://d16-nichevo.github.io/bible-quiz/

About the quiz:

* The quiz will show a number of Bible questions, in random order.
* The quiz is multi-choice, with each question having exactly two answers.
* No matter what option the user picks, they are told they are ❌**Wrong**.
* Scriptural citations are given to show the user why they are wrong, with links to chapter and verse.
  * This is the gimmick of the quiz. ***These citations are correct.*** The reason both answers can be wrong is because the Bible contains [contradictions](https://skepticsannotatedbible.com/first/contra2_list.html). In other words, for the questions in this quiz, there are at least two valid answers. We show the user scriptural refernces to the answer they ***did not*** pick. A friendlier, kinder version of this quiz could let every answer be ✅**Correct**. But what's the fun in that?

# Inspiration

This project was inspired by:

1. [This video](https://www.youtube.com/watch?v=RB3g6mXLEKk) by [NonStampCollector](nonstampcollector.com).
1. The [Contradictions Page](https://skepticsannotatedbible.com/first/contra2_list.html) on [The Skeptic's Annotated Bible](https://skepticsannotatedbible.com/).

# FAQ

1. ***What's the point of this quiz?***
   * It's designed to be given to people who believe the Bible to be without error. The hope is that the "hands-on" nature of this quiz commuicates this idea in a way that simple debate might not be able to. It ***might*** just sink in a little better than standard rhetoric. Basically: it's meant to be a tool in the online atheist's arsenal.
1. ***But none of these are actual contradictions, if you understand the Bible fully.***
   * Is that true for *all* of them? Oh. No problems -- I guess I was mistaken then! 😅
1. ***Why did you put these contradictions in the quiz, and not other ones?***
   * I wanted to choose contradictions that seemed particular indefensible. In other words, I was avoiding "weak" contradictions. Obviously this is fairly subjective.
1. ***Why are the questions randomly ordered?***
   * Because I wasn't really sure how to order them in a curated sense. By order in the Bible? By theme? By difficulty? I wasn't sure, and being lazy, thought that randomness could save me here.
1. ***Why do my answers get "locked in"?***
   * This feature (using [local storage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)) was implemented to make it harder for a user to discern the "you're always wrong" nature of the quiz. If a user could refresh, they might quickly discover that both answers to a particular question are wrong. If they can't do this easily, they are more likely to continue engaging with the quiz.
   * There is a link secreted away at the bottom of the quiz to reset it. There are also other technical ways to circumvent it (e.g. Incognito mode). It's not meant to be uncrackable, simply "hard enough" to the average user.
1. ***Why is the source code minified?***
   * This is just another step to prevent curious semi-technical users from discerning the nature of the quiz too easily. It's not a perfect measure by any means.
   * A non-minified version exists in the repository. You should work with that, not the "live" page in the `docs` directory.
   * The "live" page in the `docs` directory gets automatically updated on commit.
1. ***I want to add my own questions!***
   * Go ahead! This is why I put this on GitHub. [Fork it!](https://heardlibrary.github.io/digital-scholarship/manage/control/github/fork/) I've added comments so the HTML code should be easy enough to figure out, even if you're not super-technical.
   * Be sure not to try edit the minified file (see above).
1. ***How do I contact the author?***
   * My contact information can be found [here](https://deck16.net/contact).
