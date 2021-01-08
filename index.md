# 2021

## January

### 2021-01-03 11:38 First post

Testing the body
 
### 2021-01-03 11:41 Testing new entry

 
### 2021-01-03 12:01 Another new entry

 
### 2021-01-03 12:20 How I created this blog

I spent the weekend overwhelmed with the amount of blogging options out there, and it wasn't the first time. I've attempted blogging before, and failed to my discontent... Was it lack of willpower, determination, focus or a goal oriented mindset? Maybe. One thing I know for sure is that the idea of blogging to me, has that senseof something well fleshed out, official and good looking for others to read.

Although I like that as an outcome and even aspiration, I would dread it sometimes because the standards I'd set to myself would be greater than I probably should.

I'm now approaching it with a journaling mentality. Where any time of the day, I can jot down my notes, thoughts and ideas without much pressure on how it should look or anything of that sort.

To start, I'm sharing the script I wrote that created this blog more or less automatically, it's a script called [one-step-to-journal](https://gist.github.com/gumatias/209da343a168c34320e1bb59d3508c60).
 
### 2021-01-03 22:16 First Time Open Sourcing in Python

I'm realizing today that one of the most purposeful and productive way to work, learn and grow is by tackling the problem that is right in front of me. For instance, I'm very hooked on this journaling idea and have been messing with Github Pages and jrnl over the past few days, and now I'm finding myself in need of a feature that jrnl [currently does not support](https://github.com/jrnl-org/jrnl/issues/821).

The problem seems simple, but the scope seems large: I'm unfamiliar with the internals of the tool, the programming language its been developed in and it's something I could easily ignore.

I decided not to, and instead, take this need as an opportunity to learn and tangentially contribute in a good way to a community I initially had no intentions to help. I started [very very small though](https://github.com/jrnl-org/jrnl/pull/1148), but I believe it's a solid first step.

We'll see where this goes.
 
### 2021-01-04 15:13 Today I Learned

1. Docker is an open source application that with containers and images it can run applications in isolation in a virtual environment. This makes the running apps secure and reliable. An image is file that contains the configuration of an application that can be used to run, when running, it is used as a template to run as a container. It's important to note that images are immutable and read-only, therefore, wanting to update an application configuration, dependency, version and
so on.. can only be done form a container which itself can become an image where future containers can be created from. Dockerfile is where that image configuration exists. An image can exist without a container, though a container cannot exist without an image since it strictly needs it so it can create itself and come to life an a virtual running self-contained environment.

![](https://p-bofzyj.t3.n0.cdn.getcloudapp.com/items/04uN8m4X/1462556c-9d39-483c-b6fd-db5659fc5ce9.jpeg?source=viewer&v=8cfbd5e64e9fc26bbe8c1dfc742589f8)

2. One of Python's package manager is called Poetry and `poetry install` is how you run it initially to install the project's dependencies.
 
### 2021-01-05 14:03 Request For Comments (RFCs)

One of the initiatives I've been focusing on is how to enable people and consequently teams to collect feedback on their ideas while leveraging the experience and expertise of their colleagues. One of the best ways I found it to work is through a process called RFCs.

One simple and common way to think about it is where you have a document that you're receiving feedback on from people. Currently two types of these documents have been seen: Proposals and Tech Specs.

1. Proposals: Is a general and more abstract idea that captures the core of what the author is proposing given an identified and clarified problem.
2. Tech Specs: It's an extended and more technical Proposal that goes into the nitty gritty of the proposed approach.

To use an analogy (because why not), if we were the people who created and advocated for seat belts, one would use Proposals to explain why seat belts are important and what the general idea is for solving the safety problem, whereas Tech Specs would contain more of the How to create, install and roll it out on cars, along with other relevant details. Hope you got the idea.

There are cons and pros to encouraging people to go through this type of process, which I plan to expand more in another opportunity.
 
### 2021-01-06 09:03 Writing can be fun

Most of my recent years have been getting good at consuming things, and if there's a handful of skills I can say I am the master of, is of going out for a jog while listening to podcasts at 2x speed, watching Youtube videos as I attempt to avoid mindlessly chugging down food into my throat and reading online content as I do my most private business (if you know what I mean). The life hacks I've been applying to maximize my learning are endless...

While this is all fine and good, it's an ilusion. The idea that we're actually learning anything at its best is almost inexistent. Just think about all the good books and lectures you've read or watched so far, how many can you actually give say a twenty minute presentation on?

The author of "Mind for numbers" Barbara Oakley found herself having a similar struggle. For someone who used to hate anything math and science to becoming a Ph.D. and engineering professor and involved in researches related to learning how to learn, she is yet another great example that our brain is indeed adaptable, mutable and can grow.

Barbara shares an interesting concept about how the learning process goes in the brain. It's the pinball game metaphor. It boils down to two different modes of thinking; focused and difused. In that game, imagine when you pull the ball shooter springs and releases, it lauches and starts hitting on all those rubber pins back and forth on a certain pattern. This is the focused mode in activation, your brain has that knowledge and knows how to connect the dots and quickly help you
retrieve the concept one is thinking about.

Now, the other version of that game is when the rubber pins are further apart than the first game your brain just played. You spring shoot the ball and as soon as that little ball reaches the "main field" it starts unpredictably hitting other pins. That's the defuse mode, it's more exploratory and in the process of solidifying and finding certain patterns that give it enough time and reinforcement, it will transform into the more focused version if given enough work.

![](Image example here)

Let's think about brushing our teeth. Whatever primary hand you use, when you grab the tooth brush the mindless automation gets triggered and there we go holding the tooth brush, pressing for paste and brushing it around your moth the same way you've been doing for your whole life. Your mom, dad or caregiver got to teach you one day and you kept at it until you no longer have to think about it. Now try to do it with your left hand... I tried and it actually works, in fact that
became my default brush teething predominant hand.

---

I have spent being as a consumer. In fact, I've grown by people telling me that the United States has the largest amount of consumerism of goods than anywhere else. Six years living here I didn't think I'd be as attached to certain things as I am or consume as many goods as I now do. Life before was more about working towards more audacious goals and less on the specific gadget I had to buy in order to have a better life, the newest piece of technology everybody else has and keep
upgrading, the iPhones, iWatches and iAnything else has become the reason why life isn't as great as it can be. My point here is that I realized that I became more of a consumer, and this in turn has been translating into things I actually didn't think they would. The ratio between reading, listening and watching something has significaly become far greater than the times I spend creating something.

TODO:
* How I got where I am today was through more action and less motion, there's a difference between the two (reference to Atomic Habits book/quotes)
* Writing is an opportunity to start creating, blogging is one way, Vitaly's speech was motivating
* Finding opportunities is not as hard as it may seem, we just need to switch the way we view the world by observing to engaging, interacting and participating.
* Writing can be for fun or professionally, they both work.
* RFC's is something I've been engaging more with at my company. Perhaps it may sound interesting to you.
* How do you gather and share feedback on ideas with people? where is the space for that?
 
