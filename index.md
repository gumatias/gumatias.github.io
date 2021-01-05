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

1. One of Python's package manager is called Poetry and `poetry install` is how you run it initially to install the project's dependencies.
 
