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

![](https://p-bofzyj.t3.n0.cdn.getcloudapp.com/items/wbu9JQql/6982aed9-c6a5-4324-be38-f5581f503f3f.jpeg?source=viewer&v=58418138a8be42b57e50535e70aee5a1)

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
 
### 2021-01-12 21:57 Quality Assurance

The more software I write the more biased I become and strive to be less ignorant of what I lack on paying more attention to. This is why I believe places that implement Quality Assurance processes are making better decisions for the organization and specially their customers.

QA for short, is the idea that software need to abide to abide to certain standards in order for it to satisfy and live up to the expectations of the users. Some may have the belief that automated tests is the ultimate goal to meeting that standard, but when it comes to testing software, the ways in which it can be tested is vast and hard to predict all possible paths without proper tooling. Engineers tend to code and test for the happy path and almost on a sort of ideological way
where no matter how much they try, there is likely to be gaps and uncovered branches or paths in the codebase.

This is when Quality Assurance professionals become a key component to the software development process and lifecycle.

I once heard that there are two parts to Quality Assurance, one is Quality Prevention and the other is Quality Control. Whereas the former is responsible for ensuring that defects are avoided as much as possible and the latter is managing the current state of the software. That frame of mind states that what most of what we see oragnizations doing with their manual QA Analysts, it's the Control/management portion of it and less if any of the defect prevention. However, it's fair to
say they both live under the Quality Assurance little pina colada umbrella.

QA analysts spend countless hours going over product specifications, trying to come up with the best test cases they possibly can so that they can go over that checklist when it's go time. This can be immediately after development in a staging environment or when it's relesed and deployed to production, or both. This lifecycle is what seems to be still up for debate on which way is better. Some swear by QA before software gets to our users' hand so that we can deliver the best
possible working piece of functionality to users, while others believe in failing fast and increasing cycle time (the time software takes from the initial coding phase to deployment). While both makes sense, there are cons and pros to both.

QA Analysts in addition to coming up with a exhaustive list of test cases in theri spreadcheets, checklist or whatever application they prefer to use, they also have the responsibility to be the voice of the customer during product conversations. This is so because QA are undoubtaly the internal contributor that has spent the most amount of time using the application as much if not more than the users themselves as an individual. They know the paths like the back of their
hands and feel the same level of pain as the users, and this is incredibly valuable during internal discussions.

People wearing such hat can and should create metrics for understanding the health of the software. Number of bugs is an important metric, but it's far from being the only one that people should be aware. The percentage of automated tests in the codebase, its coverage, ratio of tests that regressed and many others are things to also consider.

It's important to understand that although the standards, metrics and actual verification is done by those people, they are not one bit responsible for all the quality issues that can arise. QA Analysts have no control of the engineers their company hire or fire, the budget allocation to dedicate people to focus solely on quality, the amount of bugs that make into a team's backlog and so on... they do what they can with what they got, and blaming in an event that something goes off is not
the way to go here.

When it comes to testing itself, engineers tend to basically write two types of tests: unit tests and integration tests. Unit tests as the name suggests, is exercising the code paths at its most precise and compartmented level. Whereas integration tests is when you get all those individual bits, put them all together to interact with each other and check how they behave as a larger integrated system. There is a place for both to live, and QA loves both in addition to their manual testing
that they know can be automated only to a certain degree.

Exploratory Testing is the type of testing that unless someone comes up with some AI technology to do so, is what QA can also offer a great hand. Exploratory Testing is a unique type of verification because instead of the person going through a given checklist step by step, they actually use the software more naturally as a user would; without following any script and simply wondering around the application, going through the most unpredictable ways possible that no code as far as I'm aware
is capable of doing without instructions.

QA is important and the work they do is incredibly important to help increase the trust between ourselves and our customers.
 
### 2021-01-13 21:18 hi again, NPM

NPM stands for Node Package Manager and for developers is probably the most well known and used package manager to date. At its most basic level, NPM is the place where Javascript modules and dependencies can be found. If we dive a little deeper on what it actually is, it's more than "just" a database for Javascript and its meta-information (fun fact, I like how meta-"data" and meta-"information" are two different things, data is a value without context whereas information is a data
that has a meaning, so for example; "30" can be seen as a meta-data for a person, whereas "30 years" is information because it gave meaning to the numerical data.. I digress, back to NPM).

NPM is a few extra things:
1. CLI
2. Registry
3. Website
4. Organization

It's easy to see npm as just a Command Line Interface that download compressed projects from Github, but first of that is not entirely true, it's true that one facet of NPM is being this incredibly useful CLI as people know and use everyday. It has a main configuration file called "package.json" where the list of dependencies in other Javascript files is defined as well as meta-information about your project, and an also optional executable scripts that can be declared and ran from the
terminal. Just as any CLI, NPM has evolved from almost a decade and it has a collection of options and features to assist the underlying application in managing all of what its necessary for it to run.

The Registry part is the main aspect of it that made NPM stand out from its competitions, like Bower for example. To clarify, Registry is the database of modules and its meta-information lives and it's today extremely large and relied upon by probably 99% of the companies out there, definitely 100% of the Fortune 500 companies use it, so that's a great sign of success. The Registry has millions of Javascript packages for both NodeJS which was its main focus in the beginning to now frontend
Javascript modules later on as it's where the competition with other frontend package manager tools began.

It's fair to say today that NPM has "won" this Javascript package manager competition by miles since it dominated both ends of the stack, became the default choice for companies and has a bright future ahead given its large dataset and reliability.

NPM's Registry is widely known for being this public database, though since more recent dates it is also used as a private repository as well for organizations that need some confidentiality.

It's Website is the other piece of it that came earlier in the day and is useful until today as a way to scan through the Registry by using a web interface that surfaces all the millions of packages, its project information and a place where users can manage their packages.

Lastly and very importantly for NPMs survival, it's that it also became an organization. If my mind serves me correctly, NPM started circa 2012 and around 2015 (or perhaps less) it has gotten so popular that its creator Isaac Schlueter had to make a decision on where to take this project. It wasn't an easy decision to make as the growth of the project was exponential and the data clearly showed that its enormous success is undeniable. Isaac needed money to keep the Registry alive and
continue to maitain and evolve the software, he was able to survive by getting sponshorhip from the company he was working full-time at the time (yes, NPM was a side project) until it became unsustainable for them with all its costs. Isaac could've kept it as an Open Source Software while working for a big company like Google or Microsoft to have it under the company, Issact could've started a Foundation (which I'm personally unfamilar it at the moment), or better for him, started his
own business and taken funding from Venture Capitalists. And that is how NPM became now also NPM Inc., the company responsible for in addition to its open source package manage version, a Software As A Service companyt that provides values not only to the open source coomunity and companies who are OK with the public aspect of NPM, but private companies who prefer to keep their own version of the Registry in their own servers or request consulting services from the speciallists or so on..
Isaac is the Chief Product Officer and founter of NPM and has his fully remote team of about 60 people since the time of this writing.

A few interesting fact of the CLI itself though is that just like any package manager dependant on other packages for it to work, it uses some pretty neat tools such as an abbreviation mechanism so you don't need to type the whole command because it figures out for you what you meant.

There's an interesting aspect of NPM and it's architecture, it's built with the concept of SOA (Service Oriented Architecture) in mind (or microservices as people now like to call it and has a nice sounding touch to it). SOA is the idea that instead of having a single application or monolith, the application is built in multiple smaller chunks of independent applications that talk to each other. The benefits here are more than I can recall, but first, it goes witout saying that such
architecture is what NPM is about, it encourages applications to be modular and deployable in various servers, that's why it has so many individual packages, that's a good thing to keep them separate so that code reusability can take place. NPM also needs to be a very reliable application, since the web pretty much depends on it, so it uses CDN for speed and caching.

So, yes. NPM is all that and not just a command people type in the terminal.
 
### 2021-01-14 21:35 Holly Infinity

When dealing with numbers there are times when calculations produce unexpected results if people aren't as aware of the internals and how numbers work under the hood in computers and programming languages. I am (or think I was) one of those people and let's move away from that ignorance one word at a time, shall we?

Infinity is a Numerical value in languages like Ruby that means what it claims to be, something that doesn't have an end and goes on forever. What it initially appeared to be just a sign of a "bad" calculation when putting two incompatible numbers together, it turned out to be a more interesting dive than I ever imagined.

To explain why Infinity exists is important to understand that computers can only calculate so much and be as precise with describing numbers as it has bits for, and those bits have a limit. There was a time where computers were only able to process arithimetic with integers, well to a certain degree. Hardware was limited to integers, but the software could workaround it and workout the math to get decimals at that level, but it wasn't until computer hardware evolved enough that it
eventually began being able to support Float points and calculate that in the hardware, making things a lot faster to process. The idea here is that the closer to the hardware the faster calculations are, so today that problem is solved. The issue we have now is that the type of Float we're talking about is compressed to as far as there s enough bits, so as an example... one would think that 0.1 + 0.2 in Ruby IRB for example, would result in 0.3, right? but it turns out that it'll result in
0.30000000000000004, which with some level of ignorance, lack of curiosity and whatever-ness, looks good to me. What's happening here is that decimal numbers only go as far as it can go, but it stops at a certain point because it can go on forever.

The reality is that unless we're sending rockets to Mars or something of that magnitude, we can get away with the level of precision it provides out of the box from these languages. In the grand scheme of things, calculating the distance between earth and alpha centauri in milimeters won't make that big of a difference if the last decimal digits are an approximation number, or if one is creating a video game where the precision is at a level far closer than a pixel. In reality, we
wouldn't be able to tell the difference.

Floating-Point is a specification created by IEEE (guess: Electrical Engineering org) so that there can be certain guidelines and recommendations on how say, programming languages should deal with numbers in a way that's easier to communicate across all these different systems.

Ruby has Float::Infinity and -Float::Infinity, which both carry themselves telling everyone that can go far out up to the size of galaxies and beyind, to smaller than an atom size, it can just keep going.

A few more quicker things learned:
1. Floating points in binary are structure in three parts: sign + exponent + mantissa (this is basically the numbers that follow the decimal point)
2. Some programming languages simplify by supporting Float by default and "only", while others prefer to have two data types, one for Float and another for larger floating pints such as BigDecimal or Double.
3. When dividing a number with a 0.0 floating number, it results in Infitiy happens because 0.0 is not really 0.0, as we learned, it goes on and on with 0.000000..000000... until Infinity so we need to tell it when to stop or just say, "Yea, this goes forever, here's how we represent it as: Float::Infinity"
4. Earlier ruby versions made it easier to deal with Infinity in a more idiomatic way where instead of saying (0..Infinity), programmers can now leave the Infinity out and see that as a way to represent the same idea.

There's some math to be figured out here that I want to get to once I learn it, but today, this is the right place to start.
 
### 2021-01-15 21:19 Postgres Data Types

What happens when a Ruby data of value Infinity tries to be saved in a numerical database column? well it won't work. Those are times when the opportunity to brush up on some very basic PostgresSQL skills calls for attention.

Data Types in Postgres is a way to store a given data in a more meaninful and efficient way. There are about 20 data types in postgres from the most commonly used ones to the more recently created and even the ones the designers of the database will never know it existed because there's a way to leave the other data types up for the user to create is they choose to do so. For everything else, let me see what we can come up with:

1. boolean
2. bit
3. character varying; varchar
4. float
5. text
6. uuid: this universal unique identifier is so large that some say it'd be able to assign an id to every star in the universe. that's a lot of stars.
7. json: plain text json.
8. jsonb: some refer to json Better, but b stands for bynary. This means that the json instead of being stored as plain text like json would, it actualluy gets converter and stored as bytes and decompressed when reading the data.
9. integer
10. array: this is a new one I'm yet to learn more about. it's said to be helpful for more static data like tags (as in youtube video tags)
11. date: just the date, no timezone
12. datetime
13. timestampz: date and time without timezone
14. timestampz: date and time with timezone
15. time: time of the day without timezone

and a few others that still haven't solidified in my (or as) neurons yet. Each type has a strong reason to exist and some might still be around due to legacy reasons (like bit when it's recommended we use boolean for ths type of usage).

Since I'm running short on time and I'm literally falling asleep on my keyboard every few seconds, here's something more:

1. Postgres follow standards that other databases do (there's an RFC for it from IETF!)
2. tik tak tik tak
3. Postgres has some legacy data types that ti

zzzZZzzzZZZZZZzz
 
### 2021-01-18 20:14 BDD and Python's Behave Testing Framework

##### BDD

Behavior Driven Development is what BDD stands for and it was created circa 2003 (I think) by Dan North (might be mispronoucing his name, but all I write here is from memory, so let's be forgiving), an Australian working for Thoughtworks at the time, who got involved in the Agile community where he initially got inspired by Kent Beck's Test Driven Development.

Despite its name, Dan claims that BDD has nothing to do with testing and the reason he came up with it was mainly because he hoped to distinguish these two very related, although different ideas. Testing is when an individual or system verifies the results of the checks in place, and the Driven Development part of it is when tests are preceding the production code and dictating how it should be implemented. BDD on the other hand, in more or less Dan North's own words "To increase
the level of confidence in the stakeholders through evidence". The way he expands on this statement was pretty impressive and if only I can recall them.. there's a talk on Youtube called "BDD is not testing" (or something along those lines) that is worth watching, but as far as I can rembmer, there's everyone's current favorite worth "empathy" when it comes to writing a test that is not for yourself, but those who depend on the software to function as expected not because you said so,
but because there's evidence that we can show to our customers, product owners, fellow coworkers and even our future selves, and this really drove the point home. Writing a test thinking about others.

Now how much test should one write? There was a controversial post by Kent Beck on StackOverflow that asked "how deep are your tests?", where he mentioned that he "gets paid for code that works, not for tests" and that he "write as little as possible to reach a given level of confidence" acknowledging that levels of confidence vary per individual. I personally always struggled with this and this is certainly something I'm keeping in mind moving forward.

Back to BDD! It's all about increasing the level of confidence of the stakeholders through evidence (just making sure I still got this). This is what we're going to dive more deeply with a tool that I just got the pleasure to be introduced by an open source project I'm hoping to contribute; jrnl (the exact same one I'm using to write these posts).

##### Python's Behave

Behave is a BDD test framework written by yet another fellow Australian named Benno Rice (I'm getting good with names! who would've thought...). Benno's history with testing in Python wasn't a pleasant one, he looked into two other BDD-ish Python frameworks such as Lettuce and Freshened (I believe) and both had its own issues that didn't make him enjoy using it. That's when he along with a fellow programmer Richard Jones worked together on this cool framework that is today one of the
most widely used BDD testing frameworks in the Python ecosystem (pytest-bdd as another popular pick).

In one of his talks, Benno makes a compelling statement. Saying that the way we normally go about testing is we define our tests from the requirements, then define our application from the requirements. But what if instead we instead define our tests from the requirements and the application from the tests because the tests ARE the requirements.

This was so insightful that I need to attempt to break this down or express in a different way:

1) Requirements => Tests / Requirements => Application
2) Requirements => Tests / Tests => Application

#1 is what I personally do, but #2 which is what Benno Rice suggest, sounds much more appealing. When the tests themselves are the written requirements, then the fidelity is much higher because this can and perhaps should be the document that all stakeholders are looking at and communicating, it's shared and just by looking at that document writen in plain english, with a much more natural language and its easy to read Domain Specific Language, the level of confidence is much higher and
the evidence is right there becuse all those steps are translated into actual code.

This is what Benno Rice created along with Richard Jones, a Python BDD focused framework that's gotten the capability for DSLs to be written in its own file and an organized structure of files and folders where everything lives. Here's the organization from a user standpoint:

1) All Behave's related files live under a features/ directory
2) The tests cases themselves are listed under the same directory with a .feature file extension
3) The feature files have a DSL to assist with framing the requirements in a standard manner: Feature, Scenario, Given, When, Then, And. Which I plan to expand more on soon.
4) features/steps/ directory which is where the implementation for all the code that interacts with the software lives.

Let's take an example for cooking a Vietnamese soup in a Microwave application:

```
Feature: Heating food in the Microwave

Scenario: Heating a Vietnamese soup
  Given a vietnamese soup
  When I place the soup inside the Microwave
  And I set the timer for 2 minutes
  And I hit start
  Then the Microwave starts heating the food
  And after two minutes it stops
  And the food is warm
```

This was probably more complicated than necessary, but hopefully it was clear enough to capture the key idea here.

The next question was, but where is all the interaction with the application? Well, once the requirements are settled and clear (remember: QA, product owners and other stakeholders all agree and are looking at these same set of requirements), then it's time to go into the features/steps/ directory and create some Python code that links back to those requirements.

First I need to confess that I never writen a single piece of Python code so the syntax is a brutally incorrect guess, but i'll be something like:

```
@given("a vietnamese soup")
def step_given_soup
  # ...

@when("I place the soup inside the Microwave")
  # ...

@step("I set the timer for 2 minutes")
  # ...

@then("the Microwave starts heating the food")
  # ...
```

That's in the most basic way possible, the idea. Natural languange like requirements with the aid from Behave's DSL is defined in the feature file and each step (Given, When, Then and And) are implemented as steps.

Behave has a wide range of other features I didn't touch such as Fixtures and Hooks (which are in its essence, the same thing), support for arguments/variables so requirements can receive a variable set of value so we can reuse the same steps, contexts which is sort of like states that can be shared across steps and much more that makes testing with Behave quite a pleasure as far as I can tell.
 
### 2021-01-19 18:39 Numbers in Ruby

I recently dealt with numbers in Ruby and it was a delightful way to get more familiar with its API and how it works from a higher level.

Ruby treats all numbers as a Fixnum, and we can know that by grabbing the ancestors of any numerical value. e.g. `1.ancestors`, `1.1.ancestors` (pause to double check I actually got these right...).

ACTUALLY, Fixnum is a deprecated class and it seems to have been replace by Numeric. Doing `Numeric.class.ancestors` and `Integer.superclass` or `Float.class.ancestors` we will see that in its list of ancestors, `Numeric` is present. When it comes to numbers, it is the highest level number related class in Ruby. Above that it's the `Object`, which we know that as an object-oriented programming languange, everything in Ruby is an object.

Ruby also offers other ways to represent numbers that are more accurate and more suitable for other types of calculations. `BigDecimal`, `Complex` and `Rational` are some of those as far as I'm aware.

`BigDecimal` is a more accurate and exact version of `Float` which is referring to floating points that as we know is inexact given it's bit allocation for representing decimal numbers.

`Complex` is used for more scientific type of mathematical operations and `Rational` represent numbers in a way that I'll need to study more to not lie too much here.

An interesting that Ruby does automatically when calculating numbers is something called coersion. Given a set of numbers, Ruby will convert the numbers before applying the arithimetic. So for instance:

```
result = 1 + 2 #=> 3;
result.class #=> Integer

result = 1.0 + 2 #=> 3.0
result.class #=> Float

result = BigDecimal(1) + 2 #=> 3.0
result.class #=> BigDecimal
```

While the details are foreign to me today, Ruby makes sense of these number by coersing them to the largest Numeric type to avoid truncating the number and providing less exact results. This makes sense.

Ruby also has a `coerce` method that does it similarly:

```
1.coerce(2.0) #=> [2.0, 1.0]
```

Ruby also has a few other methods inherited from Numeric that are helpful:

```
-1.abs #=> 1 Returns the absolute number without a sign
1.to_f #=> 1.0 Coerces the number to Float
1.1.floor #=> 1 Rounds the number to its lowest integer representation
1.1.ceil #=> 2 Rounds the number to its highest integer representation
1.3.round #=> 1 Rounds the number to its closes integer representation
1.5.round #=> 2 Rounds the number to its closes integer representation
#### ... and many more
```

Ruby is a language writen in C, though I _think_ those classes are written in Ruby but core parts of it are delegated to its C version that performs the nitty gritty of the arithimetic operations that who knows one day I get to dive in.
 
### 2021-01-20 21:28 Rails' ActiveRecord STI and Polymorphic Associations

Rails comes with two promising feature in its ActiveRecord database framework; Single Table Inheritance (STI) and Polymorphic Associations.

STI in few and simple terms is a way to organize similar data in a single place. To be more specific, it means storing information that shares the same structure in a single database table, so that duplication can be avoided. Technically speaking, a STI table has essentially a `type` column where we can differenciate the various records that will be store. So an example that might work well depending on the requirements are in a farm application where we're storing the records of
animals, where we have Chicken and Cow both being an Animal. We could have a table `animals` where inserting records for either Chicken and Cow plus other shared attributes such as `name`, `weight`, etc. can also be stored. Let's give this a shot (again, all from memory):

```
class Animal < ActiveRecord::Base
  # ...
end

class Chicken < Animal
  # ...
end


class Cow < Animal
  # ...
end
```

This looks fine as long as the requirements of the application matches for all types of animals. There are situations where STI may seem like a good idea at first, but down the road it could turn into an unfortunate decision if things go a different direction than initially expected (to say the least).

As for Polymorphic Associations, it may seem similar since it also solves for avoiding duplicated table schemas and allowing similar types of data to live together in the same bucket, but just like STI, it's important to use it with care.


With Polymorphic Associations, we instead of having a `type` column that holds the distict values, it instead holds an `id` which is a foreign key to a table that is considered to be of that polymorphic table's type. I think that was confusing, so here's a clarification and example... Using the same farm idea as above, let's say we also want to store a picture of the animals. So an image can have the url for the file itself, and perhaps some metadata like size, name, etc. Our `images`
table would be referencing the animal's id in it so all animal's images can be stored in the same table. So unlike STI where it focuses on the type of each record, polymorphic associations focuses on a generic type of record that is applied or associated with the foreign table, and that is what gives it a type and meaning to it. Let me try again, STI focuses on a single place where many similar types are stored and Polymorphic Associations focuses on a single place where tables
with similar attributes can point to or live. huh.. good enough, at least I tried.

Pulling from the example above, we'd basically have an extra table and therefore model for the generic multi-purpose set of attributes:

```
class Image < ActiveRecord::Base
  belongs_to :imageable
end

class Chicken
  has_one image
end
```

(In very simple terms again, huge caveat in everything I write on this website)

There two data storage mechanisms are good tools to use when suitable, be careful (note to self).
 
### 2021-01-21 21:12 Application Performance

When it comes to a website's performance there are a various ways to think about it. We need to keep in mind the size of assets such as images, stylesheets and javascript that are being serve to clients and if the website has a server with database running, how long that slice of the web request takes to respond, it all counts.

Today there are online services available that does some of that benchmarking for us against different types of clients, devices, internet speeds and other important aspects that sometimes it's easy to forget, specially when living in a country where the internet speed and access is so abundant. We need to remember developing countries that are at the bottom of the technological advancement and are years behind the USA digital infrastructure. This matters specially when websites are
serving internationally. It's important to be inclusive even in that regard.

Lara Hogan, other than writing an incredible book about public speaking (Demistifying Public Speaking) that I was gifted, became a specialist in web performance and started consulting for companies and interviewing on podcasts to share her experiences. She says that performance is not a responbility of a single person of a certain role that is accountable for how the website performs, she says it's a responsbility all members have. Requests for website performance improvements or
issues may come from Customer Support, any engineer in a team and not just the tech lead, the product manager and so on. It's all in our hands to make sure we're delivering a delightful experience to customers.

But how fast is fast enough? Lara Hogan jokes that as long as we're faster than our competitors, than we should be good. Alghouth she shares that is often said that a 2 second load is what people believe is the limit that won't lose the attention of the user before they get frustrated and walk away thinking that things just doesn't work. Performance also matters depending on what the purpose of the page is, a search page may have a different set of expectations and relevancy to
users if strategic parts of the page is loaded before others, say the results come first while the javascript, images and style for the rest of the page loads later.

The closer we get to the metal the more complex things seems to get when we're taking a programming language execution time when running say, a loop, allocating objects into memory, performing expensive calculations or querying the database. Fortunately, Dave Beckperk (I am so sorry for mispronoucing it, I'll need to learn from memory) became specialized in Ruby performance, but also more generally application performance and a consultant with this very same focus. In one of his
talks during a RailsConf, Dave shared a fun fact about the Apollo lunar landing that had an error pop up five times just seconds away from the lunar lander touching down and was saved by a 26 year old programmer present in Mission Control who became aware of the issue and said it was OK to proceed instead of aborting the mission. Uncertain from my memory how related that was to performance, although the 1Mhz, 32kb of RAM (give or take) computer was clearly a feat to say the least.
 
### 2021-01-22 20:40 Performance Part 2

Nate Bercopek! I think my memory is getting better, that's the engineer who sort of got involved with Rails application performance by chance after sharing a post about Turbolinks on Twitter. He was surprised that people started reading and enjoyed his writing style so much that even DHH re-tweeted his post. That's when he realized there was a niche there worth diving into, and so he did.

In one of his interviews, Nate is asked about what is the top most important performance knowledge to keep in mind. He says something I have to agree given my current situation, which is the important of first and foremost understanding what the problem is without getting ahead of ourselves and jumping into the solution. Using measuring tools such as New Relic and Scout are great ways to dive into the actual numbers and measurements for what is happening in production. Performance seems
to be one of those things that we first need to see it happening in production before we have the evidence necessary to starting diagnosing and eventually solving it. Otherwise we're pulling things out of thin air and that is probably the most unproductive thing that can be done. There are situations where performance issues show up in development or a different environment other than production and even though it "feels" slow, it really is nothing but a shallow understanding of
the actual problem and no evidence of how it'll turn out to be like in production. So understanding it first, using metrics in production to then finally tackle the problem that has enough evidences in place that it can be used to benchmark against.

An interesting topic covered by Nate is the idea that Rails is slow. That is a blunk statement that first we need to clarify what slow means, because it can sound like an objective conclusion to some. Yes, Ruby has it's performance issues and slower than other languages, but not simply slow. That is what is to be argued, when benchmarking about faster tools such as NodeJS for example which could be 10x faster than Rails, then we have some more guidance here and can say with more
accuracy that yes, Rails is slower than NodeJS, but it is also faster than other languages, so it's subjective.

Active Record is also what tends to get a bad rep when talking about performance. That can be true, though it depends on how the tool is used. Active Record is not really a database and doesn't translate perfectly the same way the database does, so it is doing what it can, but at the end of the day the engineers are responsible about how its used. One can easily do `User.posts` with AR, and that is indeed a simple way to fetch information just like if one were calling just another method
on a given object, without realizing that behind the scenes there's database connections and queries being performed.

Rail's most predominant type of issue by far are N+1s, which are basically repeated SQL queries being executed in the database. This is exactly what Rails programmers fall into when dealing with Rails performance, the misuse or unawareness of certain APIs and a deeper understanding of how it all works. The trade-off is that you get a much more readable and easier to use database layer abstraction that is meant to facilitate programmers' lives, and indeed it does, though it comes with
a cost that at somepoint that pretty looking code might come back to bite us if we're not careful.

I'm hoping we can dive into the two application monitoring tools I mentioned earlier (New Relic and Scout) to see how they can help prevent major issues in production, so we'll leave that for next time.
 
### 2021-01-26 21:56 Microservices (again)

I have a strange feeling I've watched this movie before, or rather, written about it in some shape or form, though to a more superficial level perhaps. Well, today might be a replay or perhaps a better sequel of that movie. We'll need to wait to find out which one it'll be, until then, let's recap some basics of what we learned today.

**TL,DR;** Microservices is when applications are organized in a loosely coupled manner, where each individual and smaller application is decentralized and isolated from each other while still able to communicate through public interfaces.

Back in the day, perhaps decades ago when the world revolved around executables softwares that would be downloaded or even better, recorded into a CD-ROM, injected into a personal computer and then installed. During this period, where softwares would be fully deployed and executed in personal machines, there was a variety of issues that we programmers at the time had to deal with, the fact that software updates and fixes had to go through another process of reinstallation. This was
OK and quite honestly is still what we do with operating systems and Kernels, although today is more segmented and less likely to happen that way. Applications back then, no matter how modular and organized they were, it'll always be deployed as a single instalation executable. This was more dificult to scale because the software would be highly limited to the user's computer. Today, thanks to the internet that is no longer the case for the majority of the softwares out there, with
applications running online and in a separate computer or server, client computers are deferring the majority of the execution to another processing machine, this facilitated development and software updates since all software companies had to do was deploy to a single place. However, another type of issue arose, as a single computer was taking responsibility for all the load, it keeping up with the demand became an issue. We can only add so much memory and processing power to a single
computer before we hit a wall, in other words, vertically scalling computers had its limits.

If we think about a e-commerce application on the web during black friday, it's fair to imagine that its shopping card part of the application would be more heavily loaded than most of the rest of the website, say, the user profile service. This single running application is what we tend to call a Monolith. Mono stands for Single and Lith for Stone, originally in Greek. So basically the server is that single stone that everything runs together and goes to production as one. This ends up
introducing various risks to a company since if unrelated broken parts of the application can take down the entire company's website. This is one of the problems that a Microservice architecture solves for, if we continue with our e-commerce example, the shopping card could be a separate smaller application separate from everything else, this way it can scale up and down relative to the amount of demand at any given time. This helps save cost because instead of scaling an entire giant
monolith application because it's an all or nothing kind of deal, we're scaling a very specific service for a good reason.

Netflix has its most popular Microservice talk on Youtube by one of its early engineers who watched the company grow through most of its lifetime up until recently. Netflix also started as a monolith and learnings through similar experiences with the entire platform going down given that it was too centralized from the application to the database was some of the reasons Microservices came for the rescue.

Although Microservices has become the buzzword for web applications, it's good to remind ouselves that it is not the best or only solution, not is it better than Monolith applications, but instead a choice based on the company's needs.
 
### 2021-01-27 22:31 More microservicing

I know I told myself to avoid repeating the same topic in a row, otherwise I can get to an undesirable non-day-tight compartimented way to live, which I've been staying away from. Though I'm going to say perhaps 2 or at most 3 subsequent days of the same topic should be the limit. Now, onto the continuation of what actually matters most; Microservices.

A bit of history on how Microsercices came about, is that James (ahh blanking on the last name now, starts with "W") who used to work at a large consulting company famously known as Thoughtworks had started to witness a certain pattern on how the companies he was working for were solving their problems when attempting to vertically scale. James began putting the pieces of the puzzle together from what he known before such as Bounded Context, a few other Domain-Driven Design patterns and
more, that these very same companies began scaling through the creation of smaller self-contained, decentralized and loosely coupled applications. This allowed teams to instead of dealing as James call "a big ball of mud" that was rigid and resistance to change, have instead a organized and orchestrated set of smaller pieces taken apart from that same ball of mud monolith that in turn allowed teams to organize themselves more strategically around smaller chunks that had a single and well
defined responsibility that could leverage continuous integration more strategically running only highly related pieces of test suites, faster deploys and less downtime since each application although connected still independent enough that breaking one deploy won't take down the entire business application.

Dan North, the inventor of Behavior Driven Development also came up with a very similar pattern solving for the same set of problems that got another name, which is why James doesn't claim to be the inventor, but simply the contributor of a architectural solution that is standing on shoulders of giants.

---

Note to self: auditory learning is the worse way I can learn anything. The strategy that might work best is a multi-sensory learning experience where I can apply vision, tactory (right?! I mean, touching...), recall, self-assessment and a few other more effective ways that works best than auditory, rereading, highlithing, even mnemonics, imagery, summarizing and others I thought were actually beneficial but aren't. Anyways, this is not why I come here, but just wanted to add a separator between when I
wasn't learning as effective as I could've with when I learned the right way to learn.
 
### 2021-01-28 20:32 Anki, Quizlet and Brainscape

This is less of a technical writing and more of a review of tools that I'm planning to start using as a assistant for acquiring the knowledge I'm looking for to actually to the type of writing I'm dying for every single day :) so it's a meta writing in a sense.

Also, because I'm building a habit of consistent writing at this initial stage as the main part of this beginning of the process and then focus on quality afterwards. One thing at a time, otherwise I'll end up making a mistake analagous to as when I tried to run faster and longer than usual. Enough of rambling..

Learning through recall and self-assessment has been an attractive way for me to learn recently and as I attempted a few different ways to do so, one of which being writing this blog post amongst others more focused on visual and auditory aspects, I have to say that I'm still not getting a strong sense that I really master knowledges at the level I would like to. Which is why the interested on these two additional learning techniques. It still amazes me or perhaps I'm fortunate in a way,
that I haven't been exposed or at least even tried a lot of what is at lease known in the United States as the most common learning techniques, one of which is the usage of Flash Cards. Yes, I am not sure how I made my way through college exactly, to be honest, I cheated a lot and am not ashamed to assume, specially because I acklodge oen of the biggest mistakes one can do to their personal and professional development.

Either way, Flash Cards is here to stay (at least for me) and while one can simply ditch all the complexities and unnecessary tools available today through technology and stick with pen and paper, I found incredible value in the three ones that I spent some time researching today: Anki, Quizlet and Brainscape.

Anki is apparently the one that has existed the loggest (since around 2006) and has been widely used by medical students specially. This by itself is a great testament to its efficacy, since becoming a doctor is no joke and requires incredible dedication. Though let's not stop there, a deeper dive into the software and we can begin identifying some advantages and some downsides.

Anki's advantages are:
1. It's been battle tested by a wide community for the longest period
2. It's open source
3. It has Add-ons which dramatically enhances its capability to expand
4. It provides spaced repetition as its main methodology of learning
5. It's mostly free
6. It's gotten a very custimizable feature set

Anki's downsides are:
1. It's iOS app is the only thing that is paid ($25) while Android for instance, isn't (unsure why)
2. The user experience and interface is the simplest and most basic
3. Most content management features such as Add-ons are only available through its desktop version

As for Quizlet's advantages, they are:
1. It's user experience and interface is fresh looking and plesant to use
2. Provides all key functionalities that its competitors does (e.g. a sort of spaces repetition functionality, image upload)
3. It has a large collection of public content available for share
4. It also has mobile apps

Quizlet's downsides are:
1. It's paid with monthly subscription
2. It's a private company and I'm unaware of how long they've been on market for and whether they have a promising future or not. This is a personal downside based on my ignorance, nothing like a Google search wouldn't do it, but as I try really hard to write everything from memory, I'll leave this here.

How about Branscape? It's OK, great UI and UX, but given that my clock just ringed, I won't bother because I didn't find anything exceptionally different than the two tools above.

To wrap things up, I've opted to signed up for a 7-day trial with Quizlet as it seemed the most attractive to me today, so I'm hoping that I will actually start using it on a daily basis to enhance my learning and hopefully we'll get to write some ACTUAL software engineering nerdy stuff I really want to. Fingers crossed.
 
### 2021-01-29 20:00 A RFC is not a RFC

Yes, yet again we're chatting about RFCs. Spaced repetition anyone?

The IETF (Internet Engineering Task Force) has enabled for the development of more guidelines and specifications than I can imagine. From network protocols such as the TCP/IP, so SHH, audio and video streaming and beyond. What was once a smaller group meeting back in the 60's where less than 100 people would gather in Massachussets, it is now the open organization where internet related subjects are documented, discussed and analyzed. Where would we be without that group of people who
went through so many legislative, liability and political matters to be at the position we see them today.

One of IETF's main job is keep working groups and documentation in check. This is important because Working Groups as they call it, is the mechanism for developing specifications and guidelines, in which standards and recommendations are defined. This without a doubt comprises of people and technology to support this mission. The way those standards and recommendations are documented is through RFCs. In IETF's point of view, RFC is no longer a definition for Request for Comments, it
used to be that way, until they realized that once a RFC gets published, then it's already too late for revisions of the same document to happen. It'll then be another RFC. So to them, RFC is simply an RFC, period.

Let's imagine you have an idea that promises to revolutionize the internet, so you decide to contact one of IETF's working group and they'll tell you to:
1. Do some sanity checking. Share your idea to others, specially those who might have different opinions and listen to them. What might sound like a great idea to one person might not sound that great to another.
2. One you feel good about the theoretical part of it, then you can start Drafting your RFC document in good old plain text. No Microsoft Word or anything of that sort, IETF's like to keep it as simple and as text editor agnostic as possible. They've been supporting XML for multiple decades for instnace.
3. Now that you got your draft, it's time to begin sharing it, receiving feedback and going through multiple revisions as people help you hone your idea a bit more
4. Once you feel good about the current revision of the document, now you can have a meeting with the Working Group to discuss it further with interested volunteer members
5. If the plan continues to go well, you're then welcome to publish it for full visibility across the internet
6. That's about it!

Now let's drill down in a few specific concepts about the document itself. First is that there are multiple RFC Tracks in which a given document can/will go through:
1. Informational RFC track
2. Experimental RFC track
3. Standard RFC track
4. Historical RFC track

As we can see, the RFC can be just a FYI as covering the ground for documenting something that wasn't before, who knows. The other are things one is trying it out and using the experimental track to document, receive some feedback and leave it out there. Then we have the actual standard track that is widely known and used, and finally we have a track where we're looking back in time and writing it all down.

As we can see, the RFC at IETF is a very complex process to go through and requires good understanding of the entire process before attempting to write something RFC-worthy, which in itself is a very intriguing topic. But today we're stopping here :)
 
## February

### 2021-02-01 19:13 Continuous Delivery, Deployment and Integration

I know, I know... the title might seem like I'll cover a lot of ground, but although it's seen as three different subjects they all have a lot in common as we'll see. Today it was a great refresher, though I'd be lying if I say that I never really stopped to understand these concepts well enough. So let's quit the roundabout.

Continuous Delivery is a software delivery approach where merged code makes to production ideally on a daily basis. The key aspect of this approach is that although code is deployed quickly, it still has a need for a manual business intervention so it can get into the hands of the users. One of the main benefits of Continuous Delivery is the speed of which product owners learn from user feedback. This is due to the idea that by getting the software into users' hands as quickly as
possible, we will be comforming to the Agile methodology by iterating fast, learning and re-iterating to build and deliver better software next time around. It is more business and product oriented than the code itself although it is an umbrella in which Condinuous Deployment and Integration live.

Continuous Deployment on the other hand contrasts to Delivery where is automatically deployed into production as rapidly as possible without manual intervention, it is in production whether the user can see it or not, it's specifically code oriented regardless of whether it's ready to be seen and fully used by customers or not. As we can imagine, this brings a lot of benefits when code goes into a production environment very quickly; it is less susceptible to major outages, specially
those who are harder to debug. This is because smaller pieces of code is being deployed at a much faster rate, therefore the feedback loop is much shorter and the chances of one or many significant changes from breaking production is diminished. However, in the event that it does break something, the nature of continuous deployment will make it relativelty easier to identify problems due to less changes to go through.

Lastly, but not least and very importantly is Continuous Integration. This is the closest to the stack that we can get amongst these three and possibly the most important for the success of Continuous Deployment and Delivery. Continue Integration means code getting merged into the main trunk of development in a repository quickly, being built as soon as the merge happens and specially tested automatically to ensure that the code not only compiles but that everything is augorithmatically
correct when the software is run. A solid suite of automated testing is very important when it comes to CI, as it will help identifying bugs as quickly as possible on merges, so "merge hell" or "monster merge" can be avoided.

That's all I got for today :)
 
### 2021-02-02 20:51 Circuit Breaker Pattern

Thought I was stuck with RFC and Microservices for good, but I guess not! (sort of). There's always opportunity to learn something new and different. Lately I've been realizing how lucky ignorant people are (like myself), because if one starts knowing (or thinking you know) everything around themselves then life can seem boring. On the other hand, those who know very little are in for a big treat and I say for myself that there's no better place to be and discover all the things there
is to discover, learn, get curious about and teach! so let's get going and stop wasting time rambling as I like to do to procrastinate slightly...

Circuit Breaker is a software design pattern that aims to make software more resillient and fault tolerant. Resillient because it adapts to changes in a system very rapidly and dinamically. Fault tolerant by finding ways to continue providing good user experience and prevent the business from losing revenue by learning how to deal with application errors and timeouts.

This pattern is well known outside of the software industry and it's ubiquitous. In electrical engineering, that is how disasters in an eletrical system is prevented; if the electricity current that is flowing through one's house starts to fail, the best thing to do is cut the current flow so it doesn't run riot and affects everything else connected to that same curcuit, it breaks the circuit by opening it so that the flow stops running through. This is different than a fuse for
example, where it needs to be replaced in an event of a circuit failure, circuit breaks survives.

Back to software engineering, this design patter has been implemented by various people and companies, most notably Hyrics (or something like that) open sourced by Netflix, Resillient4J another by the Java community and Retry (I believe), as well as pages of NodeJS libraries available in the NPM registry.

This pattern is widely used and became very popular in Microservices because transfering data through networks is likely to have a variety of issues such as unexpected errors and timeouts.

Circuit Breakers have basically three states: Open, Closed and Half Open. Open is when the flow is disconnected and cautiously looking for an opportunity to retry and survey the situation, Closed is when everything is functioning as normal and it's business as usual, Half Open (disclaimer, unsure will check afterwards, read at your own risk) is when the Circuit Breaker is testing the waters and after it being fully open, is verifying the status of the service it once used to call and
analyzing how it's been going so it can make a decision by either staying open or getting back to closed.

Before we move on, it's important to quickly touch on the differences being a Resillient and a Fault Tolerant service. Resillient is the how much, whereas Fault Tolerant is the what, what types of failures can it tolerate and continue to move on? So the former can be capped, since being dynamically adaptable to change is based on much failures it can handle, at some point it might start tripping and can even collapsed. Which is why tolerating faults in an intelligent way by learning
about what types of failures it can toleate is beneficial, and how it will perform that.

The pattern has certain capabilities worth exploring that it can be own topic including; Timeouts, Errors, Fallbacks, Tripping and probably more.

That's it! super quick overview to start :)
 
### 2021-02-03 20:42 An idea

This is going to be probably one of the most random posts I've ever done, but I just cannot wait to write about it.

Singing or whispering in the shower has become a growing habit of mine since I started doing singing classes, which is gonna be a year now that I think about it! Still been able to manage doing it through video conferencing, which quite honestly is less fun than in person, but still entertaining enough that I keep doing it on a weekly basis and enjoy myself doing it. I know it may feel like I'm rambling, but I just have to. Plus, I still don't get write I write this stuff publicly.

One of the incredible things about music is just how easily they stick in my mind more than anything else I've ever wanted to memorize and internalize, which for someone who has been quite challenged by learning, being able to quickly recall concepts, ideas, solutions and so on.. as easily as I do with lyrics, would be quite life changing to me. I mean, if I could just quickly and consistently ace most exams, interviews and questions that I've been tested, then the sky would really be the limit, and yes, there's nothing new about what I'm sharing about this realization, though it's important to realize how just simply recalling things quickly at the right time can start to unlock as many doors as there are buildings. By the way, I gotta say that by no means I see myself as a good singer, though good enough that I can listen to myself as I sing and no longer cringe as much.

Leaving singing aside for a second, let's get to my second favorite hobbie of mine. Playing the Brazilian Tambourine, or mostly known in my hometown as Pandeiro. It's basically a lightweight minimal pocket drum that fits in a sackpack and depending on how skill one is with it, can produce incredible sounds. I happen to have found a great teacher that thought me pretty much everything I know about the Pandeiro, and his name is Tulio Araujo, he's got tons of content online of his music, which
gives people a solid idea of how capable this tiny pocked drum is. So this is the other thing I've been learning, so if we put together the singing and playing and instrument, then we got a one-dude band that can sing pretty much anything given it's abilities. I'm that dude, just like many out there who's doing things for fun on the side while trying to take on the rest of the world during the remaining hours of the day with family, friends, jobs and whatnot.

Let's now cover the third component of this idea; learning. Staying less ignorant has become one of my obsessions lately, just given how many years I lived based out of faith and belief without really taking evidence into consideration for most of the things I came upon. This is kind of sad, but as I might have mentioned in one of my previous post very briefly, a sort of blessing and luck to have spent so many years withot digging into stuff to a deeper lever, trying to understand them and internalize it so the knowledge can be taught and passed forward. So learning more frequently through reading, listening, watching, drawing, writing, speaking  and specially testing myself have been a combination of things I started doing to see how much of the content I can retain, and quite franquily, it's disappointing after spending so much time doing all those things and at the end of the day have a sense of not really knowing much or be able to graps the key concepts of an idea. This stuff is hard! What's my best way to learn? I'm still trying to figure that out...

Related to the above, but I think it's important to call out separately is how much in a healthy and admirable way, envy people who run Podcasts and Youtube Channels. I don't say that because of the fame and popularity, but just by the sheer fact that they're capable to express themselves at some level with the internet and grow from it, connect with people and from what I can tell, have fun and a more meaningful life.

After all that said, here finally comes the punchline. We got a few key compents worth highlighting here: singing, playing the Pandeiro, learning, writing, drawing, Podcast and Youtube.

The problem is that I only got enough time in the day to make the most out of everything I want to do, so why not do them all together? Why not combine music with learning and sharing publicly? I know this may not sound like a new idea. I actually been to a Meetup tech event in NYC where they played a video of a music video they created dancing and playing a cover of a popular song and singing a lyrics they came up with that instead of the original version, it was the idea they wanted to teach people. The concept sounded good, but to be frank I didn't think that was for me and I probably forgot what they were trying to teach as soon as I got home that same night. It's funny because now I think that might actually work, perhaps not for the listener, but I believe definitely for the one who's got the lyrics in their head easily memorized and is able to sing it out anytime just by listening to the first few seconds of the original song. I mean, has anyhone ever had that? The song in the "radio" (good old days) barely starts singing and you can immediately recall the lyrics that you had no awareness of before. Something triggered and that entire circuit came to life and became front and center in the brain and now all that's left to do is keep moving the lips word by word in a rythmic and pleasant way. That is exactly what I need, I just wish songs' lyrics were as educational to my desired subject of interest that I can 1) listen to the song and recall the actual idea I'd love to know by heard and 2) have it constantly playing in the background, when I'm showering, whispering, riding bike on the street, walkingm, etc, just because it's a fun and pleasant thing to do and doesn't feel like studying at all. I'm convinced life has magically brought me to this place where I have developed all the tools necessary for that to happen, and that being: Engineering Learning Through Music, Gustavo's say :)

I have a few things in mind to try it out, so I think it's also important to keep the momentum going, so I'll start carving out some time every day to focus on this project and see how much it helps or not, who knows.

I have so much more to write about it, but I just let my fingers continue typing non-stop and my mind to go all over the place as I'll be able to tell whenever I get to read everything I just wrote. Now let's get to work!
 
### 2021-02-04 19:03 Property-based testing

This type of testing is a style focused on properties rather than specific examples. Property-based testing runs through a randomly specified wider range of values in a given test. The way it compares to a example-based test is that, usually one would focus on a single scenario to be tested, normally a set of happy paths. The problem with that is it leaves out an large depth of untested scenarios that are susceptible (sorry, I just learn this new word and I gotta keep finding ways to
insert into my writing to get used to it) to bugs. When example-based testing asserts that 2 + 2 equals 4, Property-based testing tests that a + b = c. Meaning, it center it's efforts on the property itself rather than the value.

The benefits of this style of testing are:
1. Can find an unthinkable variety of bugs
2. It reduces lines of test code
3. It results in a more resillient and robust software

As most things in engineering, there are trade-offs. Adopting a Property-based testing style is no different:
1. Can fail at unexpected times depending on the range of variabe inputs
2. Can have a performant hit as more tests will be executed
3. People who have experience with it claimed it to be harder to implement and setup

This style of testing came to life from a Haskell testing library called QuickCheck. Its name came from the realization that although widely more robuts than example-based testing with specific scenarios, it still is humble enough to claim that it cannot check everything because it knows that software cannot really be 100% tested with all scenarios. It will simply do a quick check on what it can, though just enough to make programmers more comfortable with it.

After the immense success with QuickCheck, other languages started to adopt it and today Hypothesis from Python is another big hit, as well as a few other from different languages.

The creator of Hypothesis in one of his talks shares the idea that we can survive as a business without fully testing our code to a maximum. As long as we know the areas that it should be well exercised, then that'd be good enough for an application to be healthy.

A few of the great things about the libraries for property-based testing is that they are customizable enough that one can setup the range of data to test against, and what's allowed and disallowed.

Perhaps once I get my hands dirty with it on some language I can give some code samples a shot :)
 
### 2021-02-05 19:05 Test parallelization

Knapsack Pro is a Ruby gem that ensure tests are run in parallel, therefore speeding up the overall execution time of a given suite of tests in a Continuous Integration environment. The way it works is that it's API will contain a queue of file names where it will manage when and where to execute a set of files in the number of parallel nodes that a CI environment provides.

Knapsack Pro aims to more inteligently run tests by figuring out which node is the best candidate to run a set of test files. One way to think about it is that if we have two computer resources available and we tell both to run a set of tests, it's unlikely that they'll finish in the exact same time, one will probably be faster at some level. KnapSack Pro will become aware of that, and once that computer is done, it will ask the API for more tests to run, until it's all done. This approach
allows for a more meaningful parallelization, continiuously looking for the next available computer that can run more tests, so that in the end, they can finish faster. In a more practical example, this software was able to cut down on time from a 30min long running CI build to only 3 minutes.

This gem integrates with basically the most popular CI services out there and test runners such as Minitest, Rspec, Cucumber, Jest and probably more support is coming. It started as an open source project and now Arthur, it's creator, has turned it into a business that is helping a wide number of organizations run their tests faster and saving people's time.

Thank you Arthur.
 
### 2021-02-08 20:59 Rails performance knowledge dump of the day

When it comes to thinking about performance in web applications, more specifically in Rails. A few things that may pass through a Ruby on Rails' mind are:

1. Caching
2. Indexing
3. N+1 queries
4. Content Delivery Network

And probably a lot more, but for today's purpose. That's what we (re)learned :)

##### Caching
In general, caching is when a software saves data in a storage system so that it can be retrieved faster in future queries.

Rails goes a step beyond it's more vague definition by implementing through a mechanism that has been known as the russian doll caching system. This form of caching in Rails applications is when an inner fragment of data remains cached even if its top-most fragment is no longer cached. It allows for certain levels of the data set to remain in a warm state while the outer-most is cold and needs to be refreshed. This prompts the question, but what do we mean by warm or cold cache? In simple words, cold caches are caches that are empty and once it has had data stored in it, then it's said to be warm.

##### Indexing
Indexing is our next and widely used form of optimizing database queries. Indexing is when data is being stored in a sorted manner in a database so that it can be fetched faster than had the data been not previously indexed. An analogy I had the pleasure to have been humored today is that of a book, where say if your cat is sick and you have a book of medical remedies to give your cat, then a non-indexed way to go about looking for your cats illness is by starting on page one and going
page by page looking for the illness your cat has until you find the treatment. Now imagine in another scenario, where you open that book and right at the first page you see a catalog of all the pages marked by the first letter of the illness. This will allow you to just by looking at that catalog, know which page you should jump into more quickly without having to flip through page by page. This means that the pages have been indexed and it's what you get right in the first pages for
convenience.

One common rule of thumb for improving query performance is by indexing columns found in database queries. While this certainly helps, it's worth pointing out that the indexing process itself has a cost during inserts, updates and deletes.

##### N+1 queries

A common gotcha that people fall into when using Active Record is N+1 queries. This means that the first query is being executed repeated times for another record. It is usually recommended to use joins in queries by utilizing includes in Rails queries, though if using an approach such as russian doll caching, N+1 might actually be a feature (as per DHH's comment in a web conference). His argument is that russian doll caching works best with simple queries, and N+1 queries are normally
much simpler than a non-N+1 query that looks more compex and has joins in it.

##### Content Delivery Network

CDN is a way to deliver web content to users in a much faster way due to its location-based delivery strategy. This means that if a given website has CSS, Javascirpt and Images. Those will be cached in the closest computer network to the user so that the latency is decreased as much as possible. Conversely, people would rather not load those tyeps of assets from the furthest machine, so CDN offers a solution for that type of information going through the network.

When considering performance, databse, frontend assets, caching and much more are just a few of the things that need to be discussed if coming up with a more well understood problem and solution, this was just a tiny portion of them.
 
### 2021-02-09 19:26 Webpack

Webpack is a javascript module bundler. To put it simply. It takes numerous javascript libraries and modules, then put them all together in fewer, usually a single output file that is used as the entry point for a web application.

The problem it solves is one that is exposed without using it while attempting to create a web application that has dependncies in external libraries or even internal javascript files living in the same project. Pre-module bundlers such as Webpack, one would need to very deliberately declare the javascript html script tags in the html file as such:

```
<html>
  <head>
    </script src="file_a.js">
    </script src="file_b.js">
    </script src="file_c.js">
  </head>
  <body>
    <!-- ... -->
  </body>
</html>
```

While this approach has worked for years, it exposes inumerous complexities when managing those dependencies and dependencies of those dependencies and so on all the way deep into that tree. Webpack takes care of that dependency tree for us during its build process.

Webpack became a powerful tool for not only creating a built bundled javascript file, but also for things such as:
1. Also bundling CSS
2. Executing transformers for executing things like Babel that serves as a way to translate or in other words polyfill latest-released EcmaScript versions into what current browsers can understand
3. Lazy loading dependencies only when modules are required and used (there's a specific technical name for that which I'm blanking out)
4. Transform SASS and LESS stylesheet files into regular CSS, as well as JXS (React) into plain old Javascript

These are just a few examples of how capable it can be as it gets used in projects.
 
