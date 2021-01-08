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

Most of my recent years have been getting good at consuming things, and if there's one skill I can say I am the master of, is it of lisetning to podcasts at 2x speed, eating and learning, etc. and the life hacks I've applied are endless.

I have spent being as a consumer. In fact, I've grown by people telling me that the United States has the largest amount of consumerism of goods than anywhere else. Six years living here I didn't think I'd be as attached to certain things as I am or consume as many goods as I now do. Life before was more about working towards more audacious goals and less on the specific gadget I had to buy in order to have a better life, the newest piece of technology everybody else has and keep
upgrading, the iPhones, iWatches and iAnything else has become the reason why life isn't as great as it can be. My point here is that I realized that I became more of a consumer, and this in turn has been translating into things I actually didn't think they would. The ratio between reading, listening and watching something has significaly become far greater than the times I spend creating something.

TODO:
* How I got where I am today was through more action and less motion, there's a difference between the two (reference to Atomic Habits book/quotes)
* Writing is an opportunity to start creating, blogging is one way, Vitaly's speech was motivating
* Finding opportunities is not as hard as it may seem, we just need to switch the way we view the world by observing to engaging, interacting and participating.
* Writing can be for fun or professionally, they both work.
* RFC's is something I've been engaging more with at my company. Perhaps it may sound interesting to you.
* How do you gather and share feedback on ideas with people? where is the space for that?
 
### 2021-01-07 20:11 Stock Options at Private Companies

This is what I'd tell myself back in the day the first time I heard of Stock Options:

A Stock is way for people to own a slice of a company. For example, today you could buy a piece of the company Tesla and walk around the neighborhood telling your cat, mom and teacher that you are an owner of Tesla (although extremely small). That slice is formaly known as a Share, so you could have one or many Shares. Think of it as you are sharing the ownership of the company with many other people who are also holding their own Shares in their hands, known as Stockholders.

An Option is as the name alludes to, an optional thing, you have the right to have it or not, your choice. If we want to be slightly more specific, it’s the option you have to buy a Share, and the Option only becomes available at a certain time period.

Once you have been granted an Option, two basic events may happen:

1. Vesting
2. Exercising

Both Vesting and Exercising are highly bound to these periods:

1. Grant date
2. Vested date
3. Exercise date

So if we take our Tesla example from earlier, imagine Tesla is a private company and you just got a job offer to work there. Congrats! Right there and then on your first days they grant you one (1) option to own a slice of Tesla (i.e. a share) that has a value of one dollar ($1). The day this happened is known as the Grant Date. Even if you said "forget about stocks, I want money!", generally speaking, you wouldn't be able to make that exchange because given the nature of Stock Options, you will need to wait a certain period until it to become eligible or available (for lack of better word) to make money out of it.

But remember, all you have is the right to buy a Share, not the Share itself. So at this point you really own nothing. Tesla is not foolish and wouldn't hire you today, so you can get free shares and then go ahead and sell it the next day. You need to wait until the next date of an event that you can decide whether you're doing to buy it or not. This date when you can finally Exercise it is known as the "Vested Date", meaning the minimum number of days have been fullfilled. NOW, you actually
have the right to buy it, and by buying, what we're really talking about is the "Exercise Date".

So there you have it: You're granted an Option to own a Share of a company, where the only time you can really Exercise that Option is after it has been Vested at a given date.
 
### 2021-01-08 04:09 Kicking things off

Last year has been quite a year for pretty much all of us, and it's safe to say that people wanted 2020 to end as bad as they wanted their problems to go away. Although the reality is that the transition from 2020 to 2021 has no real impact on the events themselves and they will likely continue to exist despite of the flip of the calendar year: such as a virus, suffering and pain that were taken in place in 2020, the mental hope and relief of leaving things behind still exists and is worth celebrating at some level.

The mindset is certainly one of those things that is important to reset and reframe if necessary, while still relying on your values as a guiding principle. Values are what one lives for, what truly matters to them and what they use as guidance to conduct themselves while navigating in life. The mindset on the other hand is a way to approach more immediate events on a day to day basis, how are things being done now.

So perhaps this year one may want to approach their tasks with more boldness, resilliency, become a better team player and constantly take action on things.
 
