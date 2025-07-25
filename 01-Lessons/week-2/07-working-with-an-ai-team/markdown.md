# Working With An AI Team

Say you found an exciting project that you want to
try to execute on, how do you work with an
AI team on this project? In this video, you learn how AI teams think about
data and therefore how you can interact
with AI teams to help them succeed on a project. Now, there is
one caveat which is, whether you have a cool idea but you don't have access
to an AI team, you don't have any access
to any AI engineers. Fortunately in today's world, if either yourself
or you can encourage some of your engineering friends to take an online course or two on machine learning or
deep learning that often will give them enough knowledge to get going and make a start
of an attempt, make a reasonable attempt
on these types of projects. So, let's talk about how you
can work with an AI team. First, it really helps
your AI team if you can specify an acceptance criterion
for the project. I've done a lot of work in
automated vision inspection. So, I'm going to use that as a running example in
these few slides. Let's say your goal is
to detect defects in coffee mugs with
at least 95% accuracy. So, that can be your acceptance criteria
for this project. But 95% accuracy, how do
you measure accuracy? One of the things that an
AI team would need is a dataset on which to
measure the accuracy. So, a dataset is just a set of pictures like these
together with the labels, with the design output B that the first two coffee
mugs are okay and the third one is defective. So, as part of
your specification for the acceptance criteria
you should make sure that the AI team has a dataset
on which to measure the performance so
that they can know if they've achieved 95% accuracy. The formal term for this dataset
is called a test set. The test set may not
need to be too big, maybe a 1,000 pictures will be just fine
for this example. But, if you consult with an AI expert they can give
you a better sense of how big the test set needs to be
for them to be able to evaluate whether or not they're
getting to 95% accuracy. One novel part of
AI systems is that their performance is usually specified in a statistical way. So, rather than asking for an AI system that just does
something perfectly you see very often that we
want an AI system that performs at a certain
percentage accuracy like this example here. So, when specifying
your acceptance criteria think of whether
your acceptance criteria needs to be specified in a statistical way
where you specify on average hour does or what percent of time it has
to get the right answer. Let's dive more deeply into
the concept of a test set. This is how AI teams
think about data. AI teams group data
into two main datasets. The first called
the training set and the second called the test set which we've already
talked a bit about. The training set is just a set of pictures together
with labels showing whether each of
these pictures is of a coffee mug that is
okay or defective. So, the training
set gives examples of both the input
A the pictures of the coffee mugs as
well as the desired output B whether it's
okay or defective. So, given this training set what a machine-learning algorithm will do is learn in other words computes or figure out some mapping from A to B so
that you now have a piece of software that can take
as input the input A and try to figure out what
is the appropriate output B. So, the training set is the
input to the machine learning software that lets it figure out what is this A to B mapping. The second dataset that an AI team will use
is the test set. As you've seen this is just
another set of images that's different from the training sets also with the labels provided. The way an AI team will evaluate their learning algorithms
performance is to give the images into the test set to the AI software and see what
the AI software outputs. For example, if on
this three test set images the AI software
outputs okay for this, okay for this, and
also okay for this, then we will say
that they got two out of three examples right and so that's a 66.7% accuracy. In this figure
the training set and test set above have
only three pictures, in practice both of these datasets would be
much bigger of course. You find that for
most problems the training set is much bigger than the test set. But you can talk to
AI engineers to find out how much data they need
for a given problem. Finally, for technical reasons some AI teams will need not just one but
two different test sets. If you hear AI teams talk about development or dev
or validation tests that's the second test
set that they're using. The reasons why they
need two test set is quite technical and beyond
the scope of this course, but if an AI team asks you for two different test
sets it's quite reasonable to try to
provide that to them. Before wrapping up
this video one pitfall I want to urge you to avoid is expecting a 100% accuracy
from your AI software. Here's what I mean,
let's say this is your test set which you've already seen on the last slide. But, let me add a few more
examples to this test set. Here are some of the reasons
it may not be possible for a piece of AI software
to be a 100% accurate. First, machine
learning technology today despite being very powerful still has limitations and they just can't
do everything. So, you may be working on
a problem that it's just very difficult even for today's
machine learning technology. Second, insufficient data. If you don't have enough data specifically, if you don't
have enough training data for the AI software to learn
from it may be very difficult to get
a very high level of accuracy. Third, data is messy and sometimes data can be mislabeled. For example, this
green coffee mug here looks perfectly okay to me, so, the label of it being
a defect looks like an incorrect label and that would hurt the performance
of your AI software. Data can also be ambiguous. For example, it looks
like this coffee mug has a small scratch over there and it's
a pretty small scratch, so, maybe we will think
of this though okay. But maybe this should actually have been a defect or maybe even different experts
won't agree if this particular coffee mug is okay and should pass
the inspection step. Some of these problems
can be ameliorated. For example, if you don't
have enough data, maybe you can try to collect more data, and more data will often help. Or you can also try to clean
up mislabeled data or try to get your factories
experts to come to better agreement about
these ambiguous labels. So, there are ways to try to make these things better, but, a lot of AI systems
are incredibly valuable even without
achieving a 100% accuracy. So, I will urge you to discuss
with your AI engineers what is a reasonable level of accuracy to try to accomplish? Then try to find
something that passes both technical diligence as well as business diligence without necessarily needing
a 100% accuracy. Congratulations on finishing
all the videos for this week. You now know what it
feels like and what it takes to build an AI project. I hope you start brainstorming and exploring some ideas. There is one more optional video
describing some of the technical tools that AI teams use that you can
watch if you wish. But either way, I look forward
to seeing you next week, where you'll learn
how AI projects fit in the context
of a bigger company. Look forward to
seeing you next week.

---

###### last update: 25-7-2025