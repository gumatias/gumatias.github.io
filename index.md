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
 
### 2021-01-08 20:18 Who's looking after the internet since day one?

It's uncertain where my mind have been wondering over years since I got a chance to be part of the technology industry, but one thing is for sure: there are people looking after the internet in a way that people might not be as aware of.

Those people can be found as voluntary members of the Internet Engineering Task Force (IETF), which is an open organization that founded around the time the core infrastructure of the internet was being discussed and created. Not only that, but they've primarely helped create standards for the things we rely on every day and still going to help shape the internet's future. From the Internet Protocol, which is the way we can connect with each other, to the audio and video protocols we
use and get to enjoy every single day.

The IETF is an open organization, meaning they have open:

1. Participation
2. Processes
3. Standards

Their process to discuss anything internet related are open to the public, meaning anyone interested is free to participate. The standards they create are also open, therefore it's not a requirement for anyone to follow. In fact not all standards they create are followed by other organizations, but a great significant portion of them are.

The IETF is creates their standars through a documentation and feedback process called RFC. RFC stands for Request For Comments, and is basically a way that authors of developing standards can share their proposals and receive feedback from those interested on the topic. As an open organization, the very first RFC document; RFC 1 up until the ones being created today are going through this very same process and are all available to all of us. If you ever wondered who are behind the scenes attempting to develop, scale, maintain, influence and help shape the future of the internet, then we just found those people.

The RFC process is something as I might have spoken before, am highly focused on these days. Knowing that this very same process has been battled tested for decades since the beginning of the internet is what makes me confident that it's not a fad and that actually works at some level.
 
### 2021-01-09 20:23 A few similarities and differences between Ruby and Python

Rambling, unnecessary thoughts and introductions aside, let me get straight into some of the things I can think during this Pomodoro...

1. Both are dynamic programming languages
2. Everything to them is an object
3. Foundational data structures like Arrays, Hash Tables and classes exists in both
4. The Zen of Python states that there's only one obvious way to solve every problem and strongly encourages namespacing all things, whereas Ruby although possible, doesn't officially make such statements and encourages more "freedom" if you will
5. Python's identation is part of its syntax, whereas Ruby doesn't care and treat it as just white spaces
6. Python claims to perform slightly better than Ruby (as far as I learned, not looking for evidences today)
7. Syntax for classes, method, hash, array and variables declaration and calls look very similar
8. Python is more widely used by scholars and researchers
9. Python doesn't provide all the extra redundant helper methods Ruby does for more easily using data structures

Some of these points are more vague than others, so I hope to expand more on each if/when I get more familiarity.
 
### 2021-01-10 04:47 Forcing my way through simplicity

Years ago I couldn't imagine I would be able to work from such a simple and minimal setup: A tablet. In fact, I've always strived to keep my desktop and desk as clear and clutter free as possible. I'm a firm believer on what I learned my partner and Jiro (possibly one of the most admired Suhi chefs of all time) to live by; a neat and clear workspace allows for more productive, joyful and creative work.

It's been indeed pleasant to get to my little office and see such a simple area to get started with the day, it excites and motives me. For my own records, here's how it looks:

![](https://p-bofzyj.t3.n0.cdn.getcloudapp.com/items/llunbdlE/b013ae61-6673-4f8e-910f-135d565b72ba.jpeg?source=viewer&v=5fad2378d53942ebaaa3e79c82d48457)

It truly has all I need
It's gotten a frame with my company values that I strive to live by each day when interacting with my coworkers and challenging daily tasks, a tabled (more on that below), airpods and a water bottle.

To be frank, other than my iPad, that's pretty much how my desk has looked like since I started working from home (actually even my office desk would have just a water bottle).

I' going to focus on the iPad today because it truly has been a feat (to say the least) to find ways to be productive and get proper engineering work done with it. First let me share my motivations for doing so:

1. It's super portable: I've been strategically taking meetings outdoors at a beatufiul park closeby in San Diego and I detested the weight and size of the Macbook (although being the smallest version money could buy).
2. It reminds and helps me to create the habit of drawing (I love thinking visually and have fun doing so whenever I get to draw to express my ideas, but was doing less than I wanted)
3. It helps me to learn about networking, brush up on my Unix command line skills
4. It improves my focus; I'm not a multitasker and stay away from that idea, I like to focus on as less things as possible and doing it as well as I can. The iPad can't handle too much when it comes to that given the screen size and technical resources.
5. It reminds me that great job can be done with very little as long as the individual doing the job is creative and focused enough. It still amazes me whenever I stop to think that we sent people to the moon in the 60's! I mean, people got to do what they got to do with the technology that was available to them at the time, and building rockets is no small feat. I enjoy challenging my creativity and dealing with setbacks while doing certain tasks.

There are probably more reasons as to why, but those are basically the main ones that I can think of. Now, I'm a software engineer and there are certain tools that an iPad just don't have installed by default and I need to get most of my job done. So I went hunting, and to my surprise, the technology is catching up surprisingly well. I'm able to have such simple and enjoyable work days thanks to:

1. Mosh/SSH: How I connect to my server computer that actually does all the heavy lifting
2. Termius: Terminal app that I connect to the remote server for development
3. VIM: Text editor I swear by
4. Tmux: Terminal multiplexer (as in a movie theather with multiple separate screens) to manage the session and keep it alive even if I lose connectivity with the host computer
5. Inspect: Frontend development-focused browser with core capabilities to inspect HTML elements, watch the Network, console outputs and more.

It's only been less than a month that I put my Macbook in the shelf to serve as a host and solely using my iPad as the only place I can get do my work. Below is a pic of my poor Macbook hidden away from me so I can create the habit of using the iPad for all my tasks.

![](https://p-bofzyj.t3.n0.cdn.getcloudapp.com/items/2Nu0e7ZR/59cae467-d0b0-48ea-99fd-073c2d8b4429.jpeg?source=viewer&v=27868d866fc5ff4430ffa79578a4f973)

Let's see how far this can go before I start experiencing limitations and make it unbearable, but so far I'm happy and pleased with it.
 
### 2021-01-10 20:44 SSH Shallow Dive

Today I had the pleasure to learn in more depth about a vastly used protocol and software called SSH. I'm going to go over some of the things that I think are important and fun to know.

SSH stands for Secure Shell and was born and created by Tatu Ylonen in Finland as a need to communicate more securily through the network in his university. Tatu faced issues with people sniffing on the communications to get passwords as remote communications were at the time wereTelnet, Rlogin, Rsh and similar others.

Telnet served its purpose well and allowed users to login on remote machines, execute commands, run programs, copy files and such. However, the local networks started to become insecure since long was the time that only system administrators working in the universities' local network had access to. Thanks to the internet and LANs (Local Area Networks) connectivity to WANs (Wide Area Networks) the internet was born and everything then became part of this wider ecosystem of machines.

Telnet made it easy to see what was being sent over the wire. SSH came to solve this problem by providing a way for communication to happen more securely in an insecure network environment that the internet is. This is what Tuto build for us back in 1995 at his university to solve his particular password sniffing problem and now it became the secure protocol over 2 millions of users are relying on to talk to computers everywhere across the internet.

Today SSH has helped support the invention of many important communication protocols such as SFTP (Secure File Transfer Protocol) and SCP (Secure Copy), which are used for transfering files to remote machines.

The reason SSH is so secure is because it uses a key pair mechanism to authenticate users. What this means is that there are two keys that are used for the connection to be succesfuly authenticate, by using a private and public key.

The best way to explain how this works is by sharing one of the most popular analogies. Let's say you're friends with your neighbor and the only way to communicate with them is by sending a letter. One way to send them the letter is by simply putting it in their mailbox. This creates a problem though; anyone can go ahead and read the letter since it's unprotected. This is how Telnet works.

Now imagine that instead, you go for a more secure approach.. You tell your neighbor you want to send a letter to them, they then send you a briefcase that you can put the letter in, you put your letter in it and lock using the key only you have access to, you then send it to them and they put another lock on it that they can open and they send it back to you, you then open your lock leaving only theirs and send it back, they receive it and are then able to open the last lock on the briefcase. This is basically what SSH does and its a technique called asymmetric cryptography.

When Tatu Ylonen created this software he had no idea it would take off as fantastically as it did. Companies started contacting him for support and contracting, other universities were interested in using it and its usage continue to grow from there. Today SSH comes preinstalled in all Unix-based systems such as MacOS, Linux and even Windows 10 onwards. About 6 months later, Tatu then decided to create his own consulting company called SSH Communications Security and make it a
proprietary software. This created an opportunity for those wanting a free version of the software, and since the earlier versions of SSH were freeware and open source, people forked it and created OSSH which then was also forked to create what is today known as OpenSSH that is what believe to be in fact most widely used since it's open source and free.

Thanks to Tatu and his incentive to solve a personal problem and the ones he worked with directly, he forever changed the way computer communcate.
 
### 2021-01-11 04:08 The opportunity of intermittent test failures

Having our softwares be tested automatically without the need of human manual verification is incredibly powerful and productive. This means we can go do something else as long as the tests in place have good coverage.

The problem comes when those tests begin failing for strange reasons on strage times. This is usually referred to as intermitent failing or "flaky" tests. I've used this term more than I'm willing to admit, but it's a true pain for engineering and more common than I thought it was the first time I encountered it.

There are various ways a test can begin failing:

1. Performance
2. User Interface interactions
3. Race conditions
4. Infrastructure
5. Timebomb
6. Random generated data

If I were to quickly explain each in a few sentence, it would be:

Performance: This is when the application logic has taken longer to fetch its data given the computer resource allocated to run the tests, therefore when a test run at a certain speed and expect the data to be there within a given time period, but the data has not yet finished loading, the test ends up failing.

User Interface interactions: This is by far the one I face the most often. This is when interacting with a webpage doesn't reliabily resulting in the web component to behave as expected. Some common examples are when hovering on a the interface and expecting something else to show up so you can interact with it, say you hover or a menu bar and expect to click on a button within that bar but the button hasn't showed itself yet. Another example is a button that is visible and barely made it
into the screen to be interacted with, and although it passes in a development machine it ends up failing depending on how the page was loaded, perhaps the button is no longer visible to be clicked because is now off screen or another component is on top of it and it's no longer visible and ready to interact with.

Race conditions: This is sort of a combination of both performance and UI. Imagine the web page under test loads a list of items and that list is still being fetched from the serve while the browser is already attempting to interact with the list row.

Infrastructure: Sometimes tests can fail randomly because of bugs with the programming language itself or tools being used to run the application such as a search mechanism.

Timebomb: These are amongst the ones that are quicker to spot, but still no fun. Timebombs are the types of failures that only happen at a given date and time. For example, imagine a test has expects the age of a person to be 30, but as the new year rolls around, the test that had it hardcoded the age to be 30 is no longer true because time moved on and that person is now 31.

Random generated data: This is in the same easier to spot category, because it's when data to automatically generate test data, say a user first name has an expecation on a particular name that happened to be selected most frequently, but then by pure unluck, the random generator engine has provided a different name now. This also happens with IDs where we expect records to be created in a certain order and assigned a unique identifier a certain way so that we can verify its ID on the UI,
but then the test realizes that ID is no longer assigned to the expected record.

BONUS: Another type of category of reaons why tests can fail intermitently are sorting issues. This happens when the test expects the results to come in a certain order, say a list with items, but that list has been provided sorted in a different way. This happens when sorting is not enforced and simply given the database the opportunity to sort at its own taste.

There we have it, some of the most common types of flaky specs I encountered over the years. Hope I get to dive deeper into explaining each at some point in the future. Thanks!
 
### 2021-01-11 20:33 Jest-ing

Today I got a chance to explore some more of the Javascript testing universe, and since Jest has been the chosen testing framework of choice, I was happy to spend some hours of the day learning about it. So let's do this recall thingy shall we.

Jest is yet another Javascript testing framework that was built by Facebook developers and later on open source to the React community and nowadays has gotten quite popular and it is as far as I can tell the most widely used in the React ecosystem, but also getting popularity in other Javascript frameworks such as VueJS and Angular.

Jest's primary goals are to make testing easier and faster for developers, while still providing the most important tools in a single library. In addition to running Javascript tests, it also offers assertion APIs, mocking capabilities, code coverage reporting and an entirely new way to facilitate assertions called Snapshots.

While running tests, it can also listen to filesystem changes in the codebase in a smart way using another tool that Facebook engineers have also created called Watchmen. This "watch" mechanism that is also available in Jest was created during a Hackathon project and has some cool functionalities as programmers instead of asking the computer to run the tests on every change, can instead make their changes in the files and expect Watchmen to notice changes across the codebase and
automatically run those tests for them.

The assertion part of Jest is pretty straightforward and is meant to replace ChaiJS, another assertion framework, though with the benefit that is also part of the package that people get with Jest.

Snapshots is another cool functionality that record expectation objects for assertions while still ensuring the saved snapshots are updated and compared against the current execution result. I think I just confused myself so let's articulate an example: It's like take a photo of the Statue of Liberty last year, then going back again a year later with a better camera to take a new photo and replacing it with the old one. If that was still confusing, we can think of a situation where a
button was in the page the first time the test ran, and Jest took a snapshot of that state of the HTML, then later on changing the color of that button. Jest will compare the previously saved snapshot and take another snapshot at today's execution and compare them. In this example, the button changed so the test would fail for a good reason. This way Jest let us aware that something has changed from its previous state and it's up to the programmer to check the failure and say "Ops, that
wasn's intended" or "Looks good, these changes are expected. Let's refresh the snapshot so it keeps the most recent version of it". This is helpful because then programmers can go straight changing the implementation code without doing it TDD style, since Jest will take care of applying the change in the test assertion.

Jest also attempts to provide a better and faster experience than Mocha, another widely used test framework. Though React's popularity definitely help Jest to be nowadays more downloaded in projects (last time peole checked it had about 4 million downloads per day as per NPM repository).

Jest interacts really well with react-testing-framework as well as other react testing libraries that are used. Although I'm unable to recall, it apparently had an unsuccessful initial release that seems to have fell flat because of some issues including performance, but its later and more recent versions are fast and better.

That's all for today. Baby stepping the heck out of it.
 
