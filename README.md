We all have cases where we __want to learn something outside the school context__. Maybe you need to pick up some skills for your job or hobby. Maybe you read something surprising in the newspaper and want to know the details. Maybe you're just starting out in research and wondering how you're going to make sense of all those papers.

Unfortunately, today's educational system up through college micromanages the learning process, 
thereby doing little to prepare you for independent study. How do you go about learning something on your own?

The Ph.D. is perhaps the only part of the educational system where you're expected to manage your own education -- to learn more about some topic than anyone around you, including your advisor. I've just recently finished a Ph.D. (in machine learning), so I've just had to grapple with these issues myself. While the Ph.D. is good practice with self-directed learning, people rarely seem to write up explicitly what they've learned. This roadmap is a collection of various pieces of advice based on my experiences. 

Here are a few things this roadmap does not cover:

* __Humanities, social sciences, and foreign languages.__ While there's value to being cultured and well-read, I don't have any particular advice in this area. 
Most of what I say is oriented towards STEM subjects, and maybe some related areas such as cognitive science. If your
goal is to be generally well-read, you might want to
check out  [How to Read a Book](http://www.amazon.com/gp/product/0671212095/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0671212095&linkCode=as2&tag=metacademy-20&linkId=ZAYT6JFYGCXXYCPZ).
* __Unschooling.__ Managing your own education in its entirety is a tall order, but [some](http://www.amazon.com/gp/product/0465025994/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0465025994&linkCode=as2&tag=metacademy-20&linkId=2W2STH6SNZMLSHDP) [people](http://www.amazon.com/gp/product/0962959170/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0962959170&linkCode=as2&tag=metacademy-20&linkId=HIM3YXYTORAWOZ2S) manage to do it. 
I admire the initiative they have taken, and hope that Metacademy can contribute to making it possible. But I went through 
a traditional education, so I have no advice to offer here either. This roadmap is oriented towards people who have something specific 
they want to learn.
* __Test prep.__ If you need to take the MCATs next week, there are lots of other resources out there. I'm assuming here that you have a real desire to learn something -- either for its own sake, or because you need it for some other end.

In short, this roadmap is really about __how to learn specific technical topics that you're interested in__. I'll highlight various strategies I've used, as well as resources that I've found useful.

Let me insert the major caveat that there __aren't any recipes__ for learning on your own. Different people have different learning styles, and what worked for me might not work for you. Ultimately, you will need to __experiment to figure out how you learn__.


# Types of resources

You have various options for where to learn from:

* Most obviously, __textbooks__. It's pretty important to find a good one. A good strategy is to check course web pages at top universities and see what's assigned/recommended. [MIT OpenCourseware](http://ocw.mit.edu/index.htm) has an especially comprehensive collection of course reading lists. For AI-related subjects, MIRI has compiled a pretty good [list](http://intelligence.org/courses/).
* __Massive open online courses (MOOCs).__ Despite the hype about MOOCs disrupting traditional education, I see them as more like textbooks in the format of lecture videos. The reason they make a big difference for self-directed learning is that, unlike most textbooks, they are delivered free of charge, which makes it easy for you to mix-and-match: a few videos from this course, a few videos from that one. (This is actually pretty amazing when you think about it: according to [this report](http://cbcse.org/wordpress/wp-content/uploads/2014/05/MOOCs_Expectations_and_Reality.pdf), it costs between $30K and $300K to produce a typical MOOC, yet universities are giving them away for free. Enjoy it while it lasts!)
* __Course notes.__ There are lecture notes posted online for a lot of courses, especially on [MIT OpenCourseware](http://ocw.mit.edu/index.htm). The upside is that notes are often more concise than textbooks. On the downside, they are typically less polished, especially if (as in the majority of cases) they are transcribed by students as a homework assignment.
* __Research papers.__ For more advanced topics, there might not be a textbook or a MOOC that covers them adequately, and you'll need to turn to the academic literature. (Some fields, such as physics and computer science, are pretty good about making research publications openly available. For most others, if you don't have access to a university library, you're hosed.) 
    * Unless you're actually doing research in a particular field, you probably _won't_ want to read the most __bleeding edge papers__. The topics are naturally the least well understood, and most papers are not optimized for readability.
    * One strategy is to look for __highly cited papers__. While citation counts are deeply flawed in a lot of ways, they provide a rough measure of impact, and highly cited papers are, on average, considerably more readable than a random paper. 
    * In some fields, there are journals that publish __review papers__, e.g. [Trends in Cognitive Sciences](http://www.cell.com/trends/cognitive-sciences/home), or [Foundations and Trends in Machine Learning](http://www.nowpublishers.com/journals/MAL/latest). These are sort of intermediate between textbooks and research papers, and are a good way to get up to speed on important results of the past decade or so which haven't yet found their way into textbooks.
    * If you are not at a university, and find that a given paper is locked behind a (absurdly expensive) paywall, try __searching for the title and authors__ on [Google Scholar](http://scholar.google.com/). Often, even when a paper is closed access, the authors are still allowed to post it (or at least a preprint) openly on their web pages.
    * [Here](http://blizzard.cs.uwaterloo.ca/keshav/home/Papers/data/07/paper-reading.pdf) is some good advice on reading research papers.

A good general piece of advice is to __consult multiple resources.__ Different textbooks or courses will explain something from a different perspective, and often when reading one you get an "aha!" moment for something which didn't make sense in the other. Unfortunately, this option might not be practical unless you have access to a university library.


# Motivation

Learning things can take energy and willpower. There's been a lot of talk about how students [fail to finish the MOOCs they signed up for](http://www.nytimes.com/2014/06/18/business/economy/udacity-att-nanodegree-offers-an-entry-level-approach-to-college.html). If you want to learn something, how do you keep yourself motivated?

Maybe we should first ask, why is it so hard to keep motivated?  Part of the answer is that technical subjects are inherently challenging. (And pretty different from anything in the [ancestral environment](http://en.wikipedia.org/wiki/Evolutionary_psychology).) But, if most of your learning of technical subjects happened in school, the way it is structured likely presented its own __obstacles to motivation__:

* Students set aside a decade or two of their lives to learn (or at least pretend to learn) things long before they have any idea why they'd need to know them.
* Students have little or no control over their course of studies, since the educational system processes far too many students to be able to personalize the curriculum.
* Even at the college level, course bulletins provide almost no guidance about what a class covers or why it's useful (lest too many trees be killed).
* The choice of topics favors things which can be easily tested, such as rote manipulations.
* Since the whole class must progress through the curriculum at the same rate, it's impossible to go back to repair gaps in students' knowledge. This means the only workable strategy is to rehearse each topic endlessly before moving on to the next one.

Ultimately, school is the result of a series of compromises which allow an adequate amount of learning without overburdening society's resources. Unfortunately, these compromises mean there's often __little intrinsic motivation__ to learn the material, hence the need for external motivators like mandatory homeworks and exams. If you keep the structure of school but remove the external motivator -- as is the case for MOOCs, where your grade basically doesn't matter -- it can certainly be hard to stay motivated. Consider that the total amount of time you spend on a semester college course would be somewhere between 50 and 200 hours. It's hard to put that amount of time into any activity in the absence of a strong motivator.

But notice that all the items in the above list are __responses to various constraints which don't apply when you are teaching yoruself__. You don't have to go through the topics linearly, you can go back to repair gaps in your knowledge, and you have plenty of time to learn things you're interested in.  If you're working linearly through a convex optimization textbook because someone told you "you should learn convex optimization if you want to do machine learning," think about whether you're copying the structure of school too closely.

The main way to stay motivated is to __learn topics you're interested in learning__. Maybe someone told you about a crazy result like [Godel's Incompleteness Theorem](godels_incompleteness_theorems), and you're convinced there's got to be a catch. Or maybe you need to learn something to solve a problem for your job or hobby. Then you're intrinsically motivated. On the other hand, if you simply "think you should" learn something, that's not much of a motivator.

Of course, the thing you want to learn might have prerequisites. In that case, a reasonable strategy is to __eat dessert first__. Suppose you open up a logic textbook to the section on Godel's Incompleteness Theorem. You'll probably get the gist of some of the ideas, but a lot of other things won't make sense. How the heck can you encode a proof as a number?  How can a statement about natural numbers be "true in some models and not others?"  Your confusion about these things will serve as a motivator when you go back to learn the topics earlier in the book.

Needing intrinsic motivation applies even to boring things like pencil-and-paper manipulations. You might encounter a situation where you had a hard time solving a problem since you weren't comfortable with a basic trick like integration by parts. Then you have a reason to go back and practice it. 

None of this will make it easy to learn things on your own. It'll still require some energy and discipline. The difference is that the __rewards come as you're learning__, rather than at some indefinite point in the future. As you clear up your previous sources of confusion or finally master those skills that had been frustrating you before, you'll get that nice "Aha!" feeling. 


# Metacognition

Learning without a teacher presents many challenges, but in my experience the biggest is that __you don't get any feedback__. (That is, unless you're using a service with interactive exercises, such as [Khan Academy](https://www.khanacademy.org/).)  Without feedback, you need to monitor your own understanding to decide if you're done or which gaps still need to be filled. The ability to introspect on and manage your own thought processes is known as [metacognition](http://en.wikipedia.org/wiki/Metacognition). 

When you read a textbook or listen to a lecture, it's easy to trick yourself into thinking you understand it. You can't directly observe your state of understanding. You need to find ways to __test your understanding__, for instance:

* try to write out the definitions, theorems, proofs, etc. from memory
* do some exercises
* try to explain the ideas in your own words

You might or might not have official answers you can check against, but at least you'll get a sense of the subjective difficulty you have doing these things. It also has the benefit of giving you a concrete feeling of accomplishment when you succeed.

You might have had the experience while reading that your mind wandered and you completely missed everything in the last few paragraphs. It's hard to notice your lack of attention. One trick I've found to make it more obvious is __parallel reading__: read two different (possibly unrelated) things in parallel. Read a few paragraphs of one, then a few paragraphs of the other, and so on. Each time you switch, try to recall what the previous stretch of text was about. Switching forces it out of your working memory (the kind that stores words and images for short times). Therefore, you find out whether the material actually made it into your long-term memory. 

Ironically, the challenges of self-directed learning also make metacognition easier in some ways. Good lecturers often try to structure the material so that each point seems to follow naturally from the previous one. This can make the ideas appear obvious -- but maybe you won't find them so obvious later on, when you have to reconstruct them yourself. Textbooks usually don't have this problem to the same degree.

Similarly, good teachers endeavor to make the notation as clean and consistent as possible. This makes it easier to remember formulas and push symbols around during the course. But if you use the notation as a crutch, you might stumble once you have to apply the ideas in a different context. If you're studying on your own using multiple resources, the clashes of notation might be confusing. But I often find that __confusion about notation reflects an underlying confusion about ideas__, and that having to confront multiple notations ultimately helps my understanding.

The Center for Applied Rationality (CFAR) put together a nice [rationality checklist](http://rationality.org/checklist/). Despite the name, it's really more of a metacognition checklist, and a lot of the points are relevant to learning on your own.


# Learning math

Mathematical topics can be tricky to learn because of the high level of abstraction required. 

A lot of math textbooks are terse and give little by way of examples or motivation. You are expected to fill in the gaps yourself. When you learn a new definition, __come up with several examples__ -- both typical examples and edge cases. Then, when you find a theorem stated in the abstract, try plugging in those examples to see if it makes more sense. For a statement about polynomials, what does it imply for linear functions?  Quadratics?  If a theorem makes a set of assumptions, try coming up with examples where each of the assumptions is violated and the conclusion of the theorem is false. 

Another important strategy is to __try to prove the theorems yourself__. There are a lot of reasons for this:

* you can test your understanding of the concepts previously covered
* you get practice problem solving
* it forces you to develop your own mental representations of the concepts
* once you read the proof, you can spot the key insight more easily
* if you succeed using a different method from the book, you learn how yours is related to it
* you will have a better intuitive understanding of why the theorem is true, and therefore be more likely to remember it

If you get stuck and aren't making progress, __try coming back to it the next day__ -- often it magically seems easier then. One theory is that in the interim, your brain is doing subconsious processing known as [incubation](http://en.wikipedia.org/wiki/Incubation_(psychology)). Or maybe you're just better rested.

In addition to learning mathematical concepts, you also want to develop __[mathematical maturity](http://en.wikipedia.org/wiki/Mathematical_maturity)__ -- a general level of comfort with mathematical notation, proof techniques, formulating conjectures, and so on. While this is mostly something that comes with time, there are also some resources which talk about these skills directly:

* Polya's books [How to Solve it](http://www.amazon.com/gp/product/069111966X/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=069111966X&linkCode=as2&tag=metacademy-20&linkId=ZCN4RYLYPVGE2PDQ) and [Mathematics and Plausible Reasoning](http://www.amazon.com/gp/product/0691025096/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0691025096&linkCode=as2&tag=metacademy-20&linkId=DFBLLQE5GTMAEGJF)
* [How to Prove It](http://www.amazon.com/gp/product/0521675995/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0521675995&linkCode=as2&tag=metacademy-20&linkId=N6WU6UYJUOF6RW7C)
* The following are about specific topics, but they try to suggest how one might discover the conclusions (instead of presenting them as a done deal, as do most textbooks):
    * [Surreal Numbers](http://www.amazon.com/gp/product/0201038129/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0201038129&linkCode=as2&tag=metacademy-20&linkId=HIZP7A5C5NOG6SVA)
    * [Concrete Mathematics](http://amzn.to/1jrRRBa)

Some other useful links:

* Nate Soares has an interesting [blog post](http://lesswrong.com/lw/j10/on_learning_difficult_things/) on his experiences reading a lot of math books in a short time period.
* The [Moore Method](http://en.wikipedia.org/wiki/Moore_method) is a method of teaching math based on the idea that you learn the most by working through the proofs yourself.


# Memory

If you're trying to learn math, programming, or anything closely related, try not to do much rote memorization. You get familiar with the concepts by using them.

Interestingly, a lot of pure math courses in college expect the students to be able to reproduce any proof from the course during a time pressured exam. What gives?  Isn't memorization supposed to be a bad way to learn?  Actually, this method makes a lot of sense: since it's pretty much impossible to literally memorize every proof, you basically have to memorize the one or two key steps, and be comfortable enough with the routine manipulations that you can fill in the rest of the details. Fields medalist Tim Gowers has a nice [blog post](http://gowers.wordpress.com/2014/02/03/how-to-work-out-proofs-in-analysis-i/) about this.

So in mathematics, __memorization and looking for patterns go hand in hand__. Interestingly, [there's some evidence](http://arxiv.org/abs/1307.0254) that in the early days of science, mnemonics were seen not just as a memory tool, but as a way to discover new regularities in nature.

In other areas like biology, you probably would need to do a fair amount of memorization. Here are some good books which talk about __mnemonics and other memory tricks__:

* [Use your Perfect Memory](http://amzn.to/1sUwJ78)
* [Moonwalking with Einstein](http://www.amazon.com/gp/product/0143120530/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0143120530&linkCode=as2&tag=metacademy-20&linkId=XIPT7HVA66IY45PH) (supposed to be good, but I haven't read it)
* [Embracing the Wide Sky](http://amzn.to/1sUx1eb)

One potentially very useful tool for memorization is __spaced repetition__. The idea is, you enter flash cards into a software package, and it determines when to present you with each one. Cards are scheduled according to a formula whereby each time you get a card right, its time interval is raised by some factor, whereas if you get it wrong, the interval is reset to one day. Piotr Wozniak, a pioneer of spaced repetition, has a big [collection of resources](http://www.supermemo.com/), and [here](http://www.gwern.net/Spaced%20repetition) is a fairly thorough literature review. Software packages include [SuperMemo](http://www.supermemo.com/), [Anki](http://ankisrs.net/), and [Mnemosyne](http://mnemosyne-proj.org/). 

Personally, I've found that spaced repetition seems to work well for remembering simple things, such as definitions and statements of theorems, over a long period of time. It is no silver bullet, though, and no substitute for understanding. A major downside is that it takes a fair amount of time to make the cards. Another problem is that you can wind up relying on irrelevant cues, such as the wording of the card. Reviewing the cards also takes some time, but not as much as you'd think (as long as you keep the cards simple). [Gwern](http://www.gwern.net/Spaced%20repetition) has a simple rule of thumb, derived as a consequence of the scheduling formula: don't use spaced repetition for a fact which is worth less than five minutes, or which you need in less than five days.


# Miscellaneous

Other links:

* [The Art of Learning](http://amzn.to/1yhX1mC) is the memoirs of polymath [Josh Waitzkin](http://en.wikipedia.org/wiki/Josh_Waitzkin), with advice on how to learn skills. 
* [Deliberate practice](http://en.wikipedia.org/wiki/Deliberate_practice#Deliberate_practice) refers to a set of techniques for structuring practice time in a way that focuses on component skills and results in immediate feedback (see Ericsson et al., "The role of deliberate practice in the acquisition of expert performance").
* Terry Sejnowski and Barbara Oakley are (as of this writing) about to teach a Coursera course on [learning how to learn](https://www.coursera.org/course/learning), with an accompanying [book](http://amzn.to/1n2LjKm). I haven't looked at this, but Professor Sejnowski is a leading figure in neuroscience, so this could turn out to be quite good.



