[TOC]

# Crowdsourcing Campaign

# 1 The Intersection Between Mathematics, Programming, and Hardware

<!--
The goal of this email is to source interesting problems somewhere in **"The Intersection,"** defined as
-->

In this email, we're looking at

$$
\text{Programming} \cap (\text{Mathematics} \cup \text{Hardware} \cup \text{Video Games})
$$

but primarily

$$
\text{Programming} \cap \text{Mathematics}
$$

since this is the most accessible to us at this stage in the process.

# 2 The Mathematical Fields of Programming

<!--
I found a couple of online discussions with programmers giving advice to math PhDs who are looking to break into the profession from academia.

Unfortunately, the signal-to-noise ratio is quite low with these threads: programmers typically show lots of disdain for academics (and, in particular, for pure mathematics); however,

The following sub-fields were offered up as historical examples of what lies between math and programming.
-->

Here's a list of a bunch of mathematical programming subfields that came up in a crowdsourcing campaign. Note: where a subfield came up more than once, I show the tally.

1. AI x 4
2. Machine Learning x 4
3. Computer Vision
4. 3D Graphics x 4 ("needs physics")

 > "For what it's worth, nearly all of the mathematics you will use in practice for graphics, is fairly basic stuff from the point of view of a mathematician. Sure, you've got vector spaces, dynamical systems, linear algebra, simple AI ... but all at an undergraduate level. Especially for games"
5. Game programming x 2
6. Physics Engines
7. Data Mining x 2
8. Network Design & MPI (i.e., "high-performance computing").
9. Robitics (i.e., "Control Theory").
10. Operations Research (i.e., "industry/military/govt").
11. Modeling (i.e., "dynamical systems").
12. Code Complexity ("You need to know Calculus, Summations for figuring out complexity of code that you write.")
13. Quantitative Analysis (i.e., "finance and others").
14. Fluids and Geophyics (i.e., "oil & natural gas").
15. Pharmaceutical R&D
16. Computer Aided Design (2D/3D editors for medical applications, video game modeling etc.)
17. Search Engines ("uses Vector Calculus for Searching Data"
18. Sentiment Analysis (uses "Matrix Factorization")
19. Probabilistic Information Retrieval/Search
20. Predictive Analysis (uses "Naive Bayes Theorem")
21. Natural Language Processing (uses "Entropy")
22. Latent Semantic Index / Principle Component Analysis used by Search Engines (uses "matrix algebra")
23. Facial Recognition ("quite a bit of linear algebra")
24. Networks ("topology").
25. Crypography/Encryption (however: "needs too much experience").
26. Relational Database Theory x 2 (uses "relational calculus")
27. Digital Signal Processing x 2 (i.e., "medical/industrial imaging")

## 2.1 The FancyHands List

I also asked [FancyHands](https://www.youtube.com/watch?v=F_LGYIQUQwQ) to aggregate a list of fields at the intersection of mathematics, hardware, and programming. I attached the result to this email. Personally, the list looks like a bunch of extremely narrow applications for entrenched industries (particular industries of the huge, highly bureaucratic variety); however, let me know if anything on it strikes you as interesting.

file:///home/george/Downloads/Math-Programming-SoftwareResearch.pdf

# 3 Results from the "Math ∩ Programming" Blog

I found a blog online which is explicitly about the intersection of mathematics and programming; however, the content seems more math focused than programming focused; in addition, the posts are extremely cherry picked and probably misleading (the author mostly cares about what is "beautiful" to write about, not what is practical to implement). In fact, you can see the author's disdain for applied fields in the following quote:

> "I'm a graduate student in mathematics, and did my undergraduate in computer science. I keep a blog called Math ∩ Programming in which I explore applications of mathematics to programming (and vice versa), and **I have to admit I find most of the less-mathematical aspects of computer science rather dry and uninspired** (basically, my opposition to all of the ridiculous hacks that go into systems programming in my experience in industry).
>
> On the other hand, on my blog I look at problems like facial recognition (quite a bit of linear algebra), encryption methods, Turing machines and cellular automata, models for predicting serial killer activity, search engines, and a bunch of other mathematical concepts. The best part is that I get to implement the ideas, and any of my own!"

Still, the blog is extremely well-written and is useful in giving a quick feel for how certain programming applications *can* draw heavily from math. Here are my favorite examples (obviously, don't read any of this stuff in detail; just skim some of the links to get a feel for what pure math + programming can look like):

1. [Google's PageRank Algorithm](jeremykun.com/2011/06/18/googles-pagerank-a-first-attempt/). Outline's Google's PageRank algorithm using graph theory + linear algebra.

2. [The Čech Complex and the Vietoris-Rips Complex](jeremykun.com/2015/08/06/cech-vietoris-rips-complex/). Uses algebraic topology to analyze the "shape" of data (simple Python implementation).

3. [Miller-Rabin Primality Test](jeremykun.com/2013/06/16/miller-rabin-primality-test/). An algorithm (in Python) to determine if a number is prime (up to a small error rate). Useful in cryptography, where everything is encoded in huge prime numbers.

4. [Dynamic Time Warping for Sequence Comparison](jeremykun.com/2012/07/25/dynamic-time-warping/). Uses real analysis + Python to compare sequences of numbers for "similarity".

5. [Metrics on Words](jeremykun.com/2011/12/19/metrics-on-words/). The mathematics of spellchecking and typing prediction (uses real analysis + topology before implementing something in Python).

6. [Binary Search Algorithm](jeremykun.com/2011/06/14/well-orderings-and-search/). Analyzes the binary search algorithm using the mathematics "well-ordered" sets.

# 4 The Frequency of Mathematical Terms on GitHub and Stackoverflow

I compiled a list of mathematical terms and then, afterwards, had a FancyHands bitch populate it with their respective frequences on GitHub (API repository) and StackOverflow.

To me, **this is the most accurate, factual representation of what sorts of mathematics programmers *are actually using*** (as opposed to what they *think* and *say* they are using, or (even worse) what kinds of math they *used* to be using but are no longer using).

The results are presented roughly in top-to-bottom GitHub order:

| Search Term                      |# of GitHub Repositories |# of StackOverflow Questions|
|---------------------------|------------|---------------|
| "Algorithm"               |     59,894 | 55,280        |
| "AI"                      |     32,266 | 12,755        |
| "Artificial Intelligence" |      2,533 | 1,062         |
| "Machine Learning"        |     16,754 | 8,091         |
| "Matrix"                  |      9,603 | 150,883       |
| "Matrices"                |      1,417 | 24,388        |
| "Statistics"              |      9,179 | 46,015        |
| "Statistical"             |      4,615 | 11,711        |
| "Proof"                   |      7,813 | 31,581        |
| "Physics"                 |      6,634 | 15,752        |
| "Data Mining"             |      3,569 | 3,161         |
| "Bayes"                   |      3,616 | 3,014         |
| "Mathematics"             |      3,505 | 27,786        |
| "Algebra"                 |      2,928 | 9,987         |
| "Bayesian "               |      2,311 | 2,412         |
| "Linear Algebra"          |      1,134 | 2,918         |
| "ODE"                     |      1,667 | 3,919         |
| "Topology"                |       1,141 | 4,614        |
| "Topological"             |        282 | 1,422         |
| "Probability"             |      1,683 | 21,954        |
| "Probalistically"         |          0 | 9             |
| "Entropy"                 |        971 | 3,932         |
| "PDE"                     |        683 | 1,767         |
| "Signal Processing"       |        896 | 18,023        |
| "Dynamical Systems"       |        734 | 18,537        |
| "Theorem"                 |        564 | 4,690         |
| "Fuzzy Logic"             |        306 | 665           |
| "Real Analysis"           |        312 | 3,098         |
| "Discrete Math"           |        186 | 448           |
| "Discrete Mathematics"    |        110 | 459           |
| "Model Theory"            |        121 | 2,735         |
| "Complex Analysis"        |        142 | 2,018         |
| "Quantitative Analysis"   |        107 | 102           |
| "Abstract Algebra"        |         89 | 307           |
| "Group Theory"            |         77 | 1,135         |
| "Control Theory"          |         64 | 2,361         |
| "Harmonic Analysis"       |         30 | 89            |
| "Modal Logic"             |         27 | 1,053         |
| "Measure Theory"          |         26 | 560           |
| "Vector Calculus"         |         14 | 151           |


## 4.1 We need to know Algorithms, Linear Algebra, and Statistics.

From the list above, here are, what seems to me, the top 3 most important mathematical subjects to understand to get to the bleeding edge of mathematical programming:

1. Algorithms (& Data Structures) // Computer Science
2. Linear Algebra
3. Statistics / Probability Theory

Moreover, this conclusion is also more or less corroborated by this [Quora thread](http://www.quora.com/Which-computer-courses-other-than-programming-are-important-for-a-job-seeking-computer-science-graduate).

To be perfectly honest, I feel a ridiculously strong urge to drop everything and read textbooks on Probability Theory, Statistics, and Algorithms. Yet I also feel a strong urge to not dick around on anything that isn't 100% essential to the Unicorn. We'll talk about this later on the phone. To give you an idea about (1), however, I attached to this email the best textbook currently available on Algorithms and Data Structures. While this book is long, it actually covers most of the statistics, probability theory, and linear algebra needed for practical applications in computer science. I estimate it would take me ~4 weeks to get through this text in full. While doing so would be extremely expensive, I can't imagine getting to the leading edge of this field without doing so.

# 5 Programming from a Former Academic's Perspective

Now for some soft stuff: in [this article](https://www.chrisstucchio.com/blog/2012/leaving_academia.html) a former professor discusses what it's like to move from a technical academic subject to professional programming. I outline the important parts below (from the perspective of the author).

## 5.1 How to Leverage Mathematical Skills in Programming

In particular, he discusses how to leverage one's mathematical skills in the field:

> **It's important to learn about algorithms.** One of the classic books is Introduction to Algorithms (it's the one on my desk right now), but there are many more. Also, algorithm questions come up often on job interviews.

and

> **The most accessible job to a typical physicist cum programmer goes by the job title Data Scientist.** It's also one of the more high paying jobs in technology. Probably the best way to describe the job is **"be the programmer who understands regression and confidence intervals".**

> Nowadays, businesses generate a lot of data. A single user browsing a website can generate 20-30 data points in a few minutes - click data, scroll data, pause data (the user paused to look at something), etc. The job of the data scientist is to look for patterns in this data and come up with useful ways of explaining it to technical and non-technical people. For example, at Styloot, I analyzed data to determine which properties of a dress are considered important by women (and used this to build a search engine for clothing).

> **To do this job you need to be a good programmer. You also need some basic statistics and machine learning skills.** The classic introduction to machine learning is Pattern Recognition and Machine Learning, by Bishop. A basic intro to statistics is Data Analysis: A Bayesian Tutorial by Sivia and Skilling, a more advanced intro is Bayesian Data Analysis by Gelman. Of course, whatever you used in grad school is probably also sufficient.

In a nutshell: he adivses to learn Algorithms and Statistics (see below for more of a discussion on this). As an aside, he also recommends that we learn Python and C++. We'll cross that bridge when we get it, however.

## 5.2 There are Small Tech Companies that Hire Mathematicians

He discusses "small" but mathy tech companies that sell things to larger institutions:

> There are also a variety of small tech companies selling specific scientific products to larger institutions. These will often be things like face recognition, LIDAR systems, sensor networks, statistical software, telecom or environmental modelling. The culture at these places varies widely - some behave like Valley startups, others act like government contractors.

I don't think this applies to us (we don't intend to be "small"), but I included it nevertheless.

## 5.3 Your Clients Don't Give a F*ck about your Math Skills

Here is a great blurb from the article where he reminds the reader that, in business, nobody gives a f*ck about how smart you are. They just want value. It's important to *always* remember this, especially when we consider studying something that suits our interests.

> ##### What it's actually like
>
> Once you actually get a job, things are a bit different. **In academia, half the goal is to show how smart you are.** The end goal is to have a grand unified theory of whatever, which is simple, elegant and beautiful. The problems you solve should be as general as possible. Code is written to get a single graph, attach it to the paper, and submit. The end product is publications and grants.
>
> **In the outside world, the goal is to give customers something in return for money.** This won't necessarily be a testament to your genius - **the customers don't care if you use cheap tricks to avoid solving the fundamental problem. You can build Strong AI or just run a call center in India - your customers don't care about those details, they just care about you solving their problems. Cheap hacks are just as good as grand theorems.**
>
> Much like in academia, some of the work you do will be the fun work you signed up for, and some of it will be boring grunt work. As a postdoc, I found teaching and writing papers to be boring. As a startup CTO, I find writing web scrapers and building crud apps to be similarly boring. You can't avoid this, all you can do is change the form it takes.
>
> One of the biggest differences between academia and industry is the ranking system. Academia is a tournament - either you make it to the top or you are nobody. Once you prove the full theorem, there is little interest in special cases. **In industry there is plenty of room for B-players and there is lots of interest in yet another CRUD app or a new application of linear regression.**

# 6 Searching GitHub for (Mathematical) "Toys" (a brief experiment).

Per Paul Graham, I ran an experiment last night **where I searched GitHub for interesting "mathematical" programming APIs to play with.** Literally the only criterion I used was "does this fascinate me?" (all in all, took about 5 minutes).

The result: I found the following project + API for "statistical relational learning," which combines elements of **formal logic** and **probability theory** for a **machine learning** application. I don't have anything else to say about it except that stuff like this is definitely up my alley (or nearly up my alley with a bit more training). It would come completely natural to me, and is something that I would love to do (and would be very good at doing), if only I was convinced a 10x product could shoot out the other side of the rainbow. Anyway, to get a feel for what I'm talking about (i.e., what's out there on GitHub), briefly scan the following links:

1. [The Article of the Author Explaining the Project.](http://phdp.github.io/posts/2015-07-13-srl-code.html)
2. [The GitHub Repository with his API.](https://github.com/PhDP/Sphinx-AI)

# 7 Conclusion
## 7.1 Ultimately, Programming > Mathematics

Overall, there doesn't seem to be a **huge** intersection between mathematics and programming (at least, this is the sentiment I picked up from online discussions). At the end of the day, programming is still programming (and not math). Moreover, far more important to good programming than mathematical ability is **the ability to ship programming product.** That's not to say diving into the intersection of math and programming wouldn't give us an advantage (it would); it's just we have to remember that we are ultimately still in the world of programming where what ultimately matters is shipping 10x.

<!--
Of course, the flip side is that academics find that "industry is smug, deceptive, fad-driven, [and] cares nothing for fundamental problem-solving until you pay them for it, and (of course) near-fatally infected with live-to-work-ism and the Californian Ideology" ([source](https://news.ycombinator.com/item?id=3804039)).
-->

## 7.2 Programmers vs. Mathematicians: They All Suck

As alluded to above, there is quite a bit of animosity between these communities: on the one hand, the programmers bitch that the mathematicians are lazy and don't get anything done (which is true), while the mathematicians have a total disdain for programming work as boring, repetitive, and beneath them (which is also true).

Personally, I'm a fan of hating them both: instead of siding with one camp, we can be in the top 0.0001% of their intersection (and really, we can be the best mathematicians in the room, the best programmers in the room, and the best businessmen in the room). I.E. Be like Elon, nigga:

> "He is by far the single smartest person that I have ever worked with ...  period.  I can't estimate his IQ but he is very very intelligent.  And not the typical egg head kind of smart.  He has a real applied mind.  He literally sucks the knowledge and experience out of people that he is around.  He borrowed all of my college texts on rocket propulsion when we first started working together in 2001.  We also hired as many of my colleagues in the rocket and spacecraft business that were willing to consult with him.  It was like a gigantic spaceapalooza.  At that point we were not  talking about building a rocket ourselves, only launching a privately  funded mission to Mars.  I found out later that he was talking to a  bunch of other people about rocket designs and collaborating on some spreadsheet level systems designs for launchers.  Once our dealings with the Russians fell apart, he decided to build his own rocket and this was the genesis of SpaceX."

<!--
![Be Elon Musk](images.thecarconnection.com/lrg/revenge-of-the-electric-car-premiere_100347936_l.jpg)
-->

<!--
Still, there is an intersection, so that's what I'll be discussing below; however, keep in mind this intersection can be divided into two categories: (i) backward focused and (ii) future focused.

The backward focused intersection are areas where programming has traditionally been intersected with mathematics, while the future focused intersection are areas where programming is currently being intersected with mathematics.

Since we're in the business of startups, we're more than likely only going to be interested in the future-focused areas.
-->

## 7.3 Action Plan

1. Discuss over the phone which of these subfields interests us the most.
2. From (1), pick a hard problem.
3. From (1)-(2), crowdsource the leading APIs to play with (+pick a set of books to read?).
4. Implement a "toy" solution using (2)-(3) as necessary.
