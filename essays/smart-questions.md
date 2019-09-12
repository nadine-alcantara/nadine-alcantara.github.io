---
layout: essay
type: essay
title: Asking the Smart Questions
# All dates must be YYYY-MM-DD format!
date: 2019-09-11
draft: false
labels:
  - Learning
---

<!--[Smart way](https://stackoverflow.com/questions/52619841/how-can-i-clear-stdin-in-a-c-progam)-->
<!--[Not smart way](https://stackoverflow.com/questions/38767967/clear-input-buffer-after-fgets-in-c)-->

In Eric Raymond's "[How To Ask Questions The Smart Way](http://www.catb.org/esr/faqs/smart-questions.html)," he throws at us such great advice on how to maximize the effectiveness of our queries, but most of us have yet to catch it. Whenever trivial problems occur in code, one should always seek help from the internet to solve the issue. But surely, once we receive help from a passerby browsing the forums, we find ourselves lost with even more questions on why the answer works as it is. We never gain insight on techniques and strategies that would help with future challenges, and we are just presented with straightforward solutions that we should blindly trust, simply because a stranger posted it online. However, such naivety does not come from purely asking the questions, it's about _how_ the questions are formed.

On Stack Overflow, I have chosen two questions of the same problem that generate two seemingly different dynamics of responses: the ["smart way"](https://stackoverflow.com/questions/52619841/how-can-i-clear-stdin-in-a-c-progam) and the ["not smart" way](https://stackoverflow.com/questions/38767967/clear-input-buffer-after-fgets-in-c). The following question displays a good example of how one should phrase their questions on forums. 

<img class="ui large left floated image" src="../images/smart-question.png">

In this “smart” way, one of the first key aspects that satisfy a criterion on Raymond’s article is “describing the goal, not the step.” The question requests for a way to clear the stdin in the C language but leaves the title broad for readers to interpret for themselves and provide a unique method that would help reach the goal. Moreover, the original poster of this tread was precise and informative about the problem, as they described the symptoms in the code (i.e. fgets() reading unnecessary leftover string left on the stdin buff) and provided research on other methods such as using a while loop. Although it seems like they have laid out too much foundation for their question, the elaboration helps steer the readers towards accomplishing the task quicker by anticipating their questions.

<img class="ui large left floated image" src="../images/not-smart-question.png">

Now onto the “not smart” question. At first glance, this question violates many of the rules stated in Raymond’s article, starting with its title. As it is not even a question, I would like to add, this title is pre-supposing the use of a method that might not be appropriate for the task. It is using the template “How can I use X to do Y,” which constricts the viewers to only use this tool to accomplish the task, where other significant tactics might be more effective for the situation. This is not to blame for the poster’s naivety of using the method, but for their lack of understanding of how to approach their problem. Another blatant red flag is how they only demanded an answer to their specific problem. Certainly, one can ask on a forum to provide a diagnosis of any errors embedded in their code, but a smarter way to solve a challenge is by “[providing] a way to reproduce the problem in a controlled environment” as Raymond states. To provide a replicable test means it may act as a template to solve any similar issues one may come across on further projects. What would happen if this person encounters the same problem again on a different assignment? They should not their problem exact problem on Stack Overflow and pray that another kind bystander would fix it for them.

This experience allowed me to think deeper about what my goals are for asking my questions. Do I want a quick solution to my situation and go on my merry way, or do I want to have takeaways such that I gain a better understanding of how programming works? It should be the latter, obviously! Asking questions should not only benefit me by completing my homework assignments, asking questions should rather allow me to gain insight into solving further problems so that I would not need to ask any other questions. I believe this would elevate me from a passive learner to a successful student and maybe an even more successful software engineer.
