# Understanding data

"There are 3 kinds of lies: lies, damned lies, and statistics."
*Mark Twain, 1906*

My sister manages a group of data scientists for a living, despite not being a data scientist herself. She tells me, however, over a few glasses of wine and half-eaten pizza that even though she's doesn't atcually work with the data directly, she often finds herself in the firing line of why statistical models doesn't always do what the company wants them to do. 

She says to me: "It's like, you know, if you *really* wanted to you can prove that 2 + 2 = 5. If you wanted to!"

And while I appreciate the fevour (and the frustation that comes with dealing a plethora of different models and different outcomes), I had to point out that her analogy was not quite accurate. Instead, this was my response. 

Imagine data as an ocean and your data-scientists as fishermen (yes, for those who realise where this is going, the analogy is going to get very on the nose, very fast). On their first day of fishing, they only catch tuna. 

Fisherman 1 declares: "Since we caught only tuna today, only tuna must live in the ocean (and nothing else)."

Fisherman 2 declares: "Since we caught only tuna today, mostly tuna live in the ocean."

Fisherman 3 declares: "Since we caught only tuna today, this area of the ocean must only have tuna in it."

Fisherman 4 declares: "Unless we catch only tuna for the next 30 days, I refuse to believe only tuna lives in the ocean."

Fisherman 5 declares: "Unless we fish only tuna in every possible location across the whole ocean, I refuse to believe only tuna lives in the ocean."

Fisherman 6 finishes by saying:

"Well, I bet if we had longer fishing lines we'd also be able to catch sword-fish."

The fisherman go out for another 9 days and still catch only tuna. On the 10th day, they catch a couple of sword-fish. Fisherman 1 and 2 become disgruntled, so fisherman 2 says:

"I don't think I'm wrong, I'm just saying that today they wind and currents were the strongest they've been since we started fishing. Who's to say the current and wind didn't blow the sword-fish into this area of the ocean?"

And so the fisherman start arguing and placing bets again and again and again. 

And this, in a nut-shell, is what makes Mark Twain's words still ring true to this day. 

# How to use this git repository

**Pre-requisites**

The only pre-requiste is basic knowledge of jupyter/notebook environments. The code is written in python, but the notebookes will talk you through in detail what each chuk of the code does so no previous knowledge of python should be required. 

(One day, I may also extend this repository to also include version of these notebooks in R).

**Introduction**

This git repository is a library of knowledge on basic statistics I've acquired throughout my studies and teaching experience. However, it came about because I had many, many years of experience navigating convoluted forum answers, lengthy you tube videos, and patches of different coding languages. I've found many amazing resources in my time, but one thing I've found useful (but rare) are quick and readible ways that show me (a) the statistical model I need to use, (b) how it's implemented, (c) code that allows me to implement it and (d) how the results can be interpreted. 

Therefore, this repo is divided in to sub-sections on the basis of how models compare data (for example, "pairwise tests" will talk you through tests that compare groups of data versus "relational/predictive tests" will talk you through tests that look for trends in data). See further below for a more detailed explanation of the sub-sections.

Then in each of the folders you will find a read me file that introduces the tests. For each of the models/statistical tests in the folder, there will be a jupyter notebook that presents some fake data and shows you: 

1) how to check your data meets the criteria for applying that specific test
2) how to implement that specific test
3) how to interpret the results of that test
4) how to graph/represent the data to better understand the results of the test

**Discipline neutral**

Because I have habit of bouncing through disciplines (and I'm no mathematician) I spend a lot of time digesting different terminologies and applications of models to churn them into something applicable to my work. Therefore, none of the tests in this repo are presented to be used for a specific discpline (hence the fake research scenarios and data). Most tests will come from the field of psychology/neuroscience as that is mainly my background. However (see first point of this paragraph), if I come across something new from a further field (for example, I'm currently entrenched in applying mantel (field: ecology) and cointegration (field: econometrics) tests to my data) I will dump it into this repo. 

**Disclaimer!**

I am NOT a statastician or mathematician. But I love statistics and I love maths and, mostly, I love finding new and interesting ways to intepret my data in a way that pushes whatever work I'm doing forwars. In academic research, I often find that different disciplines are siloed away from each-other and while we may all be working on similair data, this siloing can sometimes push researchers into using statistical models out of a sense of familiarity because they are what they been taught from their field (+) (++). 

Also, there are always new methods and new models being developed by reseachers every day. Why not use them? I believe thet really understanding your data, how it can be interpreted through standard tests and, overall, just sitting in the trenches of what it means to be a 'data scientist' is just, simply put, an amazing use of one's time.

(+) during my PhD I discovered a group of researchers at McGill had figured out how to applying Shannon's entropy to questionnaire data asking multilingual people to rate how frequently they use of their languages. In sum, because Shannon's entropy measures how unpredictable an environment is, they could use entropy to assess how likely or unlikely participants were to speak in 1 or more languages (i.e., a participant who only used on language was 100% predictable as you know 100% of the time what language they were using). When I figured out this was super relevant to what I was doing, well after that, I was hooked on applying different models to unexpected data. 

If you're interested in more about this, you can read their paper here: Gullifer, J. W., & Titone, D. (2020). Characterizing the social diversity of bilingualism using language entropy. Bilingualism: Language and cognition, 23(2), 283-294.

(++) for example, despite taking a course in Advanced Quantiative Methods during my Masters (UCL/Birkbeck) we never really covered bayesian models! But we did cover ANCOVAs and mediation/moderation analysis and whilst I deal with the word 'bayesian' on daily basis, I've still yet to use an ANCOVA once. This is not to say that ANCOVAs are useless - simply to hone in on how one stats course at one university can miss something that seems so obvious to another course at another university.
