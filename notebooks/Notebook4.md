# Design notebook entry

## Last week's critique

The feedback I recieved last week was really useful for deciding on an intermediate language between my DSL and the final output PDF. By using MusixTex as an intermediate language, I can avoid a lot of the difficulties of operating with PDFs as a file format. The critique also gave me a lot of insights into the potential benefits of my current parsing strategy, so rather than spending any additional time on looking for parsers, I decided to continue with my current strategies. 

## Description

My first immediate goal this week was to decide on a method to output the results as a PDF. I settled on using MusixTex for this purpose. I then worked a lot more on my text parser, and then put a lot of work into outputting the results to a .tex (MusixTex) file. I made a very simple method of processing tokens into notes in order to be able to connect the program all the way through for extremely simple cases (a series of quarter notes). 

## Questions

**What is the most pressing issue for your project? What design decision do
you need to make, what implementation issue are you trying to solve, or how
are you evaluating your design and implementation?**

The biggest issue is taking my current "works for the simplest case" strategy and expanding it to meet all the cases I laid out in my example file. This will require a lot more work on my MusixTexWriter to cover more cases, and a lot more work on processing notes. I have more work in the TextParser, so that's less concerning.

From there, there are two big things to work on that would significantly improve my project. First, adding a lot of error handling will make the last stretch of development easier as I expand to more use cases, and will make it friendlier to use. Secondly, adding code to convert the intermediate .tex file to a pdf, then to delete the .pdf file, would make my resulting output much cleaner.

**What questions do you have for your critique partners? How can they best help
you?**

With the time to work on the project rapidly coming to a close, I could probably use some advice in what areas of my project syntax to prioritize. What oarts of the syntax I initially defined are most useful for making the language capable and effective, and which are less critical?

**How much time did you spend on the project this week? If you're working in a
team, how did you share the work?**

5-6 hours, maybe?

**Compared to what you wrote in your contract about what you want to get out of this
project, how did this week go?**

I ultimately ended up pursuing a different strategy from what I laid out in the contract- while in the contract I wanted to build a complex system from the ground up, I instead focused more on getting a small test case to work, then expanding that case.
