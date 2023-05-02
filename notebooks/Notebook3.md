# Design notebook entry

## Last week's critique

The critique I recieved last week was good for finalizing some of the specifics of my DSL's syntax, which should make it a lot more usable. More importantly, I got a few key good pieces of advice for tools to use for the final output to pdf- by writing to an "intermediate language", then putting that through a tool to convert it to the final PDF, things can be done easier.

## Description

This week, I ended up doing a lot more work on the syntax and parsing parts of the DSL. It's not complete yet, but after looking for parsing tools in Java, I eventually settled on a strategy that would take a little longer, but would also give me a lot more control of designing error handling (something I was still unable to adequately figure out in scala's JavaTokenParsers).

## Questions

**What is the most pressing issue for your project? What design decision do
you need to make, what implementation issue are you trying to solve, or how
are you evaluating your design and implementation?**

The most pressing issue for my project is still working on finding strategies for the final "output to PDF" part of the project. If I do decide to write everything in an intermediate language, that will take a while to plan out; if I find a really good library, it'll take some time to learn, so I'll need to come to a final decision on that in the very short term.

**What questions do you have for your critique partners? How can they best help
you?**

I don't really have any questions for my critique partners, orther than if the work I've done for my DSL makes sense so far, and if there's any more input on working with pdfs.

**How much time did you spend on the project this week? If you're working in a
team, how did you share the work?**

I spent... maybe five or six hours? A lot of it was fruitless research into potentially useful libraries, though, so I still need to do a lot more.

**Compared to what you wrote in your contract about what you want to get out of this
project, how did this week go?**

I'm still somewhat behind of where I intended to be. While I still have some work to do on parsing, that's alright becuase it'll make error checking easier. I also have a lot of work to do on creating the final output pdf, though, which isn't great.
