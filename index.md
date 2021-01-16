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
 
