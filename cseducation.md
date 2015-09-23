working title: Should we <offer, require> <CS, programming> classes?

Advocates of computer science education have been pushing for improvements to pre-university computer science education, often bemoaning its underrepresentation and lack of recognition in our high schools. They're not without cause: as recently as 2013, only 9 U.S. states recognized Computer Science as a math or science class, and 90% of high schools had no offerings in the field. Countless big names have gotten behind efforts to improve this, and made big statements of encouragement:

"There just aren't enough people who are trained and have these skills today" - Mark Zuckerberg, Facebook

"It's important moving forward in the future, which is now, that everybody learn it" - Chris Bosh, Miami Heat

"Give it a shot, and don't let anyone tell you you can't" - President Obama

With so many such public advocates coming forward in recent months, especially surrounding Code.org's "Hour of Code" campaign last December, there's been plenty of buzz about computer science education. Visitors to Code.org are asked if they agree with the notion that "Every student in every school should have the opportunity to learn computer science," and to sign their name to show support. Nearly 2 million people have done so, myself included.

But there's a subtlety at play when you try to get more specific and ask someone exactly /what/ they support; there are plenty of different questions posed, and it's difficult to have a conversation about the future of computer science education without mixing them up:
"Should every school offer CS classes?"
"Should every school offer programming classes?"
"Should every school require CS classes?"
"Should every school require programming classes?"

The most idealist advocates suggest the answer to all of them is "Yes, absolutely, everywhere", but most have less absolute and more varying answers. Each one is more difficult than the last to answer with certainty, and one must give careful consideration to these very different questions.

Some measures are easy to support unconditionally: Yes, a good computer science class should count as more than an elective. Yes, more schools should offer computer science classes. Yes, we want more people to learn computer science. But beyond these, there exist many different schools of thought, and nobody seems to be sure what to do.

Perhaps the most influential figures in the development of modern computing, Steve Jobs gave us a suggestion when he said:

"Everybody in this country should learn how to program a computer."

The Code.org petition seems like a nice start toward this vision, but a discerning eye will note the difference between "learn computer science" and "learn to program a computer." First we have to wonder, what even is the difference between programming and CS? The two are not one and the same, but many people either don't know the distinction or don't consider it important. For the sake of precise terminology, let's clear that up.

The existing AP Computer Science A curriculum is almost entirely a programming course. It teaches object-oriented programming with Java, and its exam consists entirely of questions like "Here's a piece of code, what does it do?" and "Here's a problem, write a program to solve it."

The recently introduced AP Computer Science Principles, on the other hand, focuses on higher-level computational thinking, with programming being only one of seven "big ideas" covered by the curriculum. It discusses topics from audio and video to how the internet works, how we keep things secure, and the impacts computer systems can and do have on the world. It's so unmarried to programming that it doesn't even require teachers to use a specific programming language.

Of course, part of the confusion comes from history: AP Computer Science A (and formerly AP CS AB) was largely the only show in town for decades, and it was a programming course being called Computer Science. The AP CS Principles curriculum is the kind of broad foundation course suited for the more general "Computer Science" name.

This new AP CS Principles curriculum was introduced in late 2014 for launch during the 2016-17 school year, and 60 million students participated in "Hour of Code" in 2014, compared to just 20 million in 2013. We now have 27 states recognizing computer science courses as more than just an elective. Even over just the last two years, we've seen great improvements, but where we are now isn't enough for the long term. The internet isn't going anywhere, and neither are personal computing devices, with over one billion smartphones sold in 2014. What do we have to do to keep up?

"Make everyone learn to code!" - Maybe not that much.

"Give everyone the opportunity to learn computer science!" - Yes, at least this much!

Now that I've stuck my flag in the ground and established the beginnings of a position, let me begin to develop it by presenting some more context and background before I launch into discussion of a series of arguments both for and against that position. First, who am I, what is my interest in this topic, and what perspective do I have?

I taught myself to program in middle school, then lamented the limited computer science offerings in my high school\*\*\*. In college, I taught computer science to many of my peers as an undergraduate TA for seven semesters. I also organized and ran four instances of a high-school-level programming contest\*\*\* totaling over 1000 participants, so I've spent significant time interacting with CS students and instructors at both the secondary and post-secondary level.

I've explicitly discussed CS education with numerous high school teachers, hearing stories of their struggles, successes, and varying perspectives. Much of what I've heard has lined up with a 2013 survey by the Computer Science Teachers Association, which found that:

> 40 percent of teachers said the greatest challenge in teaching computer science is a lack of support or interest from school staff. Another 35 percent said a lack of student interest or enrollment was the greatest challenge. Rapidly changing technology and a lack of curriculum resources were cited as the greatest challenge by 30.5 percent and 23.5 percent of teachers, respectively.

All of these were reflected in stories teachers have told me about how they grade their programming assignments. They would typically receive submissions from their students by email, and then run and evaluate them manually on their own computer. This is archaic compared to the online submission systems and autograders used in universities, but teachers seem complacent. They explain that without the enrollment numbers, staffing, or financial backing of a university CS department, they don't have the resources to develop or invest in something more sophisticated. Even if they did, schools typically only have one computer science teacher who would stand to benefit. Nonetheless, these teachers would always have inspiring stories of the students they've taught, the curiosity they've helped spark, and the exciting things their students have gone on to do.

Asking those students what got them into computer science and how they decided to stick with it proved insightful. Answers and stories would vary widely, but a common thread came out: it took little time and exposure for them to realize they liked computer science. I've never heard anyone say that it took a long time for them to develop an interest in the subject; they just needed an introduction, and curiosity took care of the rest.

This brings me to a study done some years ago that suggested an incredible related result. The original paper is [here](http://www.eis.mdx.ac.uk/research/PhDArea/saeed/SD_PPIG_2009.pdf), and Jeff Atwood provides a great summary [here](http://blog.codinghorror.com/separating-programming-sheep-from-non-programming-goats/). From the paper's abstract:

> An experiment found two distinct populations of students: one could build and consistently apply a mental model of program execution; the other appeared either unable to build a model or to apply one consistently. The first group performed very much better in their end-of-course examination than the second in terms of success or failure ... We show that consistency does have a strong effect on success in early learning to program but background programming experience, on the other hand, has little or no effect."

To quote Jeff Atwood's take, this means that "the act of programming seems literally unteachable to a sizable subset of incoming computer science students." This is not just numbers telling a story; every computer science educator I've asked has had some similar hunch that things just haven't quite clicked for some sizable portion of their class. 

I've seen it first hand over and over in my time as a teaching assistant for various intro-sequence programming-heavy CS courses. Every semester there would be a number of students who, not for lack of trying, simply could not make it through the course. It was prototypical: they would invest 20 or 30 hours per week, triple that of the average student, trying to get through each assignment, often spending 10 or sometimes even 20 hours in office hours seeking guidance, confirming understanding, and asking questions. As TAs we would do everything we could, but it was always painful seeing these students put forth so much effort while so many others breeze by in comparison, spending 5 or 10 hours per assignment and rarely needing help. It happened every semester, in every intro CS course, to a not-insignificant portion of the class. These are some of the brightest students in the world at the University of Pennsylvania, and once they find that CS isn't a good fit for them, they go on to be researchers, bankers, doctors, and lawyers. If these otherwise perfectly intelligent and hardworking students are finding that it's not for them, how can we possibly expect every high school student to learn any serious amount of programming?

Even if we dismiss the notion that many people just don't grasp programming as well as others, Dan Bricklin, a decorated technologist best known for inventing the electronic spreadsheet, offers another take:

> Programming is a very error-prone business, especially with "typed-statement" systems. Most of them are very intolerant of errors (even simple typos). You must really have a good conceptual model of how each individual statement (and its sub-components) effects the result in conjunction with each other statement. You have to know how to check for proper operation (testing) and how to find out what to fix if it isn't (debugging). Unless you are totally immersed in that particular programming system (understanding the varieties and subtleties of its statements and functions) it is very hard for most people to do this. Most people will not get immersed in such systems that way.
> ...this is not to say that many people can't get immersed in systems that require such understanding. They do in many parts of their lives. For example, lawyers and tax accountants routinely work with such complexity in their contracts and planning. Doctors work with an untold number of variables. Someone planning a big party has to work out the food, matching paper goods, favors, invitation list, entertainment, etc. Yet, all of these people rarely program computers in addition. It's just that people who aren't professional or hobbyist programmers usually don't want to get so immersed in something that is infrequently done and not part of the rest of their lives. The question really isn't "Why Johnny can't program" but rather "Why Johnny won't or doesn't choose to program".

Instead of splitting people into performance-based buckets, he considers motivations and complexity and suggests that maybe there's some self-selection going on. Maybe some people just don't want to invest heavily in something for which they see correspondingly little use. Maybe some people like some flavors of complexity but not others.

Sam Altman, President of Y Combinator (the famous seed fund which helped Dropbox, Airbnb, and countless other technology companies get off the ground), recently tweeted a concise summary of this notion:

> Everyone should have the opportunity to learn to code. But it's not the answer to everything. Not everyone will like it or be good at it. I will never like or be good at football. A world where CS is the only option would be a sad one indeed.

So what does all this mean? Programming isn't for everyone. Not everyone will like or be good at it, just like not everyone will like or be good at many other things. Plenty of people have little desire to learn accounting or law, and plenty of people have little desire to learn to program.

All we need to do is knock on that potential desire's door and see if anyone answers. All we need to do is give students the opportunity to learn some computer science, including but not limited to an introduction to programming (think AP CS Principles), and they'll see for themselves if they want to learn more.

The students who find that they don't will still get something useful; they'll leave with a basic understanding of how computers are programmed and a variety of new understandings of how the technological world works. Perhaps more importantly, by taking an overview class instead of an all-programming class, they'll manage to avoid the negative experience of trying to immerse themselves in the increasing complexities of programming for several months /after/ they've already figured out that they either don't have a knack for it or just don't particularly like it.

The education system will thus make more efficient use of its finite resources by allowing students to give computer science a try and then self-select, and we'll end up with fewer unfortunate students trudging through all-programming classes in which they have neither interest nor inclination.

I very strongly believe that every student should have this opportunity to learn some computer science, at least enough for them to decide if they like it. Why, then, have I not said that we should put every student through such a class?

Arguments against blanket programming/cs req, to present/support:

- Many bright students at top universities find that it's just not for them, so why should we force it to be for everyone?
- What would it replace? What is it more important than? Are there better things to fix first in the general high school curriculum?
- Let kids do it if they want, but why /require/?
- Most states dont even have CS curricula/certifications, much less a good way to measure the effectiveness of CS curricula/teachers
- Goat sheep argument: some kids will simply fail, we don't need to make them miserable
- Scarcity of good CS teachers: we just don't have enough, and forcing everyone to take an intro class isn't the best use of the ones we have. needs time until we'll have the resources to make it part of standard curriculum.
- Most highschoolers are still learning how to teach themselves new things, we can't escape the need for teachers
- Existing effective online learning efforts are still very hands-on with remote teachers
- True need is to teach students to think; CS is neither necessary nor the one true way to do that
- Students that are sufficiently motivated/interested will find this material on their own, or at least explore it further on their own after being introduced
- CS majors make lots of money, so "there's not enough incentive for truly qualified programmers/engineers to pursue teaching their subject in the public school system."
- No evidence that starting programming early is necessary or even beneficial: lots of people learn to code in college, and prior experience is not a predictive factor
- We don't want students who would otherwise be interested to be turned away from the field prematurely by a poorly implemented or undersupported graduation requirement

Arguments for, to discuss/refute:
- Mandatory CS courses will happen eventually, so they might as well happen now.
- Learning to code is easier today than ever before.
- There is almost no reason not to teach students how to program.
- "you dont have to be a genius to code" - "don't have to be a genius to do math"
- Just because it's intimidating or challenging doesn't mean people shouldn't try.
- Students don't even know what computer science is since schools don't teach it.
- Programming teaches you to actually think.
- Online resources like Codecademy and Code.org make a teacher with programming experience unnecessary.
- Having a programming background is important for running a business or organization.

So, with various points considered, what exactly should we do?

1. Make CS more than an elective. A series of missing incentives has been stunting the growth of computer science education. When a class doesn't count for anything, there's:
  - no incentive for students to take it, and thus
  - no incentive for schools to offer it, and thus
  - no incentive for teachers to train to teach it

2. Make a broad introductory CS course accessible to every student. We only need to offer enough for students to try it out and see if they like it. If they do, and they want to learn more, the course served its purpose, and hopefully more in-depth offerings are also available. If they don't, the course should have still taught some useful understandings, not just a bunch of programming specifics that the uninterested student is likely to never use again.

3. Establish clear certification pathways and curricula for computer science teachers. Few states have done this, but it helps make teaching computer science more accessible to interested teachers. That leads to more computer science teachers, which enables more schools to offer computer science classes. It also helps us know when we have enough CS teachers to consider bigger future initiatives, which will require more resources than are currently available.

Returning to our original four questions:

"Should all schools offer CS classes?" - Absolutely, as much as possible.

"Should all schools offer programming classes?" - Yes, if we have enough good teachers to teach them, but there's no sense in doing it poorly or without sufficient resources.

"Should all schools require CS classes?" - Eventually, yes, but definitely not yet.

"Should all schools require programming classes?" - Absolutely not.

To whomever may be reading this, I'm quite interested to hear what you think.

*** Fortunately my high school did offer one CS class, and my computer science teacher was great. But there was only one of him, and he taught lots of other classes, and not many people took his CS class, so there wasn't much hope for anything further.

*** PClassic.org

todo: discuss survey, opinions esp. of principals from http://qz.com/502478/americans-agree-computer-science-is-important-but-only-one-quarter-of-us-schools-teach-it/