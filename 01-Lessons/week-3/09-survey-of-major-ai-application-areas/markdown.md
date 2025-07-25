# Survey Of Major AI Apllication Areas

AI today is being successfully applied to
image and video data, to language data,
to speech data, to many other areas. In this video, you see a survey of AI applied to these
different application areas. I hope that this may spark off some ideas of how
you might be able to use these techniques someday for your own projects as
well. Let's take a look. One of the major successes of deep learning has
been computer vision. Let's take a look
at some examples of computer vision applications. Image classification and
object recognition refer to taking as input a picture like that and telling us what
is in this picture. In this case, it'd be a cat. Rather than just
recognizing cats, I've seen AI algorithms able to recognize specific
types of flowers, AI able to recognize
specific types of food. The ability to take as
input a picture and classify it into what
type of object it is, is being used in all
sorts of applications. One specific type of image classification
that has had a lot of traction is face recognition. This is how face recognition
systems today work. A user might register one or more pictures of their face to show the
AI what they look like. Given a new image, the AI system can then say, is this the same person? Is this you? Or is this
a different person? So that it can decide if
it should unlock the door, or unlock the cell phone, or unlock the laptop, or something else based on
the identity of the person. Of course, I hope face
recognition will only be used in ways that respect
individual's privacy. We'll talk more about AI and
society next week as well. A different type of computer vision algorithm
is called object detection. Rather than just
trying to classify or recognize an object, you're trying to detect if
the object appears off. For example, in building
a self-driving car, we're seen how an AI
system can take as input a picture like this and not
just tell us yes or no, is there a car, yes or no, is there a pedestrian,
but actually, tell us the position
of the cars, as well as the positions of the pedestrians in this image. An object detection
algorithm can also take as input a picture
like that and just say, nope, I'm not finding any cars or any
pedestrians in that image. Rather than taking a picture and labeling the whole image, which is image
classification, instead, an object detection
algorithm will take as input an
image and tell us where in the picture different objects are as well as what are the types
of those objects. Image segmentation takes
us one step further. Given an image like this,
an image segmentation algorithm may help with that. Where it tells us not
just where the cars and pedestrians, but tells us, for every single pixel, is this pixel part of this car or is this pixel
part of the pedestrian. So it doesn't just
draw rectangles around the objects it detects, instead, it draws very precise boundaries around
the objects that it finds. In reading X-rays, for example, it would be an
image segmentation algorithm that could
look at an X-ray scan or some other image of
a human body and carefully segment out where is the liver or
where's the heart, or where is the
bone in this image. Computer vision can
also deal with video, and one application
of that is tracking. In this example, rather than just detecting the
runners in this video, it is also tracking, in the video, where the
runners are moving over time, so those little tails below
the red boxes show how the algorithm is tracking
different people running across several
seconds in the video. The ability to track people and maybe other moving objects
in the video helps the computer figure out
where things are going. If you're using a video
camera to track wildlife, for example, say
birds flying around, a tracking algorithm would
also be able to help track individual birds flying across the frames of your video. These are some of
the major areas of computer vision and
perhaps some of them will be useful
for your projects. AI and deep learning
specifically, is also making a lot of progress in natural
language processing. Natural language
processing, or NLP, refers to AI understanding
natural language, meaning the language
that you and I might use to communicate
with each other. One example is text
classification, where the job of the AI is
to input a piece of text, such as an email, and tell us what is the clause or what is the category
of this email. Such as is this spam
or non-spam email. There are also
websites that would input a product description. For example, you might write, I have a secondhand cell phone
for sale and automatically figure out what is
the product category in which to list this product, so that would go under cell
phones or electronics. Or if you write, I have
a new T-shirt to sell, then it would list it
automatically under clothing. One type of text
classification that has had a lot of attention is
sentiment recognition. For example, a sentiment recognition algorithm
can take as input a review like
this of a restaurant. The food was good, and
automatically try to tell us how many stars this
review might get. The food was good, it's
a pretty good review, maybe that's a four out
of five-star review. Whereas if someone writes
service was horrible, then the sentiment recognition average should be
able to tell us that this corresponds maybe
to a one-star review. A second type of NLP, or natural language processing,
is information retrieval. Web search is perhaps the best-known example of
information retrieval, where you type in a
text query and you want AI to help you find
relevant documents. Many corporations will also have internal information
retrieval systems where you might have
an interface to help you search just within your company's
center documents for something relevant to a
query that you might enter. Name entity recognition is another natural language
processing technology. Let's illustrate it
with an example. Say you have this
sentence and you want to find all the people's
names in this sentence. Queen Elizabeth,
second is a person. Sir Paul Mcconney is a
person in the sentence Queen Elizabeth the
Second night is Sir Paul Mcconney for a service of music
at the Buckm Palace. It would be a name entity
recognition system to confine all the people's
names in the sentence lights. If you want to find all
the location names, all the place names in
a sentence like that, a name entity recognition
system can also do so. Name entity recognition
systems can also automatically extract
names of companies, phone numbers,
names of countries. If you have a large document
collection and you want to find automatically
the company names, all the company names
that occur together, or all the people's names, then a name entity
recognition system would be the tool you
could use to do that. Another major AI application
area is machine translation. For example, if you
see this sentence in Japanese AI [FOREIGN], then hopefully a machine
translation system can input that and
output the translation. AI is in the electricity. The four items on this slide, text classification,
information retrieval, near mente recognition, and machine translation are four major categories of
useful NLP applications. Modern AI, specifically
deep learning, has also completely
transformed how software processes audio
data, such as speech. How is speech represented
in a computer. This is an audio
wave form of one of my friends saying the
phrase, machine learning. The x axis here is time. The vertical axis is what
a microphone is recording. What a microphone is recording
is little variation, very rapid variations
in air pressure which your ear and your brain
then interpret as sound. This plot shows as a function of time, the horizontal axis, how the air pressure
is changing very, very rapidly in response to someone saying the
word machine learning. The problem of
speech recognition, also known as speech-to-text, is the problem of taking
us input a plot like this and figuring out what were the words
that someone said. A lot of speech recognition's
recent progress has been due to deep learning. One particular type
of speech recognition is trigger word detection
or wakeword detection. You saw this in
the earlier video with having an AI system detect a trigger word wakeword such as Alexer or hey Google
or hey device. Speaker ID is a specialized
speech problem where the task is to listen to someone speak and figure out the
identity of the speaker. Just as face recognition helps verify your identity
by taking a picture, speaker ID can also help verify your identity by
listening to you speak. Finally, speech synthesis, also called
text-to-speech or TTS, is also getting a
lot of traction. Text-to-speech is a
problem of inputting a sentence written in text and turning that
into an audio file. Interestingly,
whereas texts speech is often abbreviated TTS. I don't often see
speech-to-text abbreviated STT. One quick example, Let's
take the sentence, the quick brown fox
jumps over the lazy dog. This is a fun sentence that
you often see NLP people use because this sentence contains every single letter from A to Z. That's ABC, all the
way up to X, Y, and Z. You can check all 26 letters
appear in this sentence. Some letters appear
more than once. If you pass this sentence
into a TTS system, then you might get an
audio put like this. The quick brown fox
jumps over the lazy dog. Modern TTS systems
are increasingly sounding more and more
natural and human-like. You've heard me
mention generative AI a few times so far
in this course. Generative I is a collection of AI systems that can produce
high-quality media, specifically text,
images, or audio. Let's take a look at
these applications of generative AI in more detail. Large language models are great
at text generation tasks, including writing
content from scratch, writing summaries,
copy editing, that is, editing text, improve
grammar clarity, and so on and chatting. For example, you can give one of these models an
instruction like suggests the funny creative names for a line of chocolate
ice cream and the model will generate some creative-sounding
names like Les. Note that this
input text here is known as a prompt and writing prompts to generate
the output you want is becoming a useful
skill for many jobs. I find that having a
large language model as a brainstorming partner
makes me more productive. If you're able to write
prompts effectively, perhaps you find it a
useful tool and work, or in your personal
life as well. In fact, I think
large language models are now at the point where almost all knowledge workers
can get at least a bit of a productivity boost
by learning and using them in their
day-to-day workflow. Generative AI can also create new images from scratch
software like Journey Ali, Adobe Firefly, and Stable Diffusion have
learned how to generate images from text descriptions by learning from millions of
images on the Internet. With one of these image
generation models, you can input an example prompt, like a purple-friendly
robot eating ice cream and the model will generate a high-quality image for you
that matches your prompt. What a Q robot.
Lastly, generative AI is also capable of
generating audio. Previously we saw how speech synthesis models can
convert text to speech. Audio software also exists like SyboI's Stable Audio
or Meta's Audicraft. They can generate music
and sound effects from a text prom so by writing
a prompt like drum solo, 140 BPM, or beats per minute. You can use a music
generation model to create an audio
track like this one. Generative AI is capable of creating several
types of content. This is affecting
many industry sectors and we'll learn more
about the impact of AI, including generative
AI on jobs next week. AI is also applied to
many applications in robotics and you've already seen one example in the
self-driving car. In robotics, the term
perception means figuring out what's in the
world around you based on the senses you have, be it cameras or radar or lied. Shown on the right is the
three-D laser scan or the light-up scan of a
cell-driving car as well as the vehicles that
this cell-driving car in the middle has detected in
the vicinity of your car. Motion planning refers to
finding a path for your robot to follow if your car
wants to make a left turn. The motion planner might
plan a path as well as a speed for the car to
make a left turn that way. Finally, control refers to sending commands to the motors, such as your steering
wheel motor, as well as your gas
pedal and brake motors, in order to make the car smoothly follow the
path that you want. On this line, focus on the software and the AI
aspects of robotics. Of course, there's also a
lot of important work being done to build hardware
for robotics as well. But a lot of the work of AI on perception,
motion planning, and control has focused
on the software rather than the
hardware of robotics. In addition to these
major application areas, machine learning is
also very broadly used. The examples you've seen in this video relate mainly
to unstructured data, such as images, audio, and text. Machine learning is
applied at least as much to structured data and that
means these tables of data, some of which you saw
in the earlier videos. But because unstructured
data such as images, is so easy for humans
to understand, there's something
very universal, very easy for any person to understand and
empathize with. When we talk about an AI
system that recognizes a cat, the popular press tends
to cover AI progress on unstructured data much more than it does AI on structured data. Structured data also tends to be more specific to
a single company, and so it's harder for people to write about or understand. But AI on structured data
or machine learning on structured data is creating tremendous economic value today, as well as AI on
unstructured data. I hope this survey of AI
application areas gives you a sense of the wide
range of data that AI is successfully applied to today and maybe this will even
inspire you to think of how some of these
application areas may be useful for
your own projects. Now, so far, the
one AI technique we've spend the
most time talking about is supervised learning. That means learning
input, output, or A, B mappings from labeled data, where you give the AI
system both A and B. But that's not the only
AI technique out there. In fact, the term supervised
learning almost invites the question of what is
unsupervised learning. Or you might also
have heard from media articles from the news about reinforcement learning. What are all these
other techniques? In the next video, the final optional
video for this week, we'll do a survey of AI techniques and I hope
that through that maybe you'll see if some of these
other AI techniques and supervised learning could be useful for your
projects as well. Let's go on to the final
optional video for the week.

---

###### last update: 25-7-2025