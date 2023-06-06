
# Content Style Guide
- [Content Style Guide](#content-style-guide)
  - [Voice](#voice)
    - [Keep it simple.](#keep-it-simple)
    - [Use short sentences.](#use-short-sentences)
    - [Use short paragraphs.](#use-short-paragraphs)
    - [Write in Second Person](#write-in-second-person)
    - [Use Conversational, Business-Appropriate Language](#use-conversational-business-appropriate-language)
    - [Don’t Repeat Yourself](#dont-repeat-yourself)
    - [Stay on Topic](#stay-on-topic)
  - [Content](#content)
    - [Word count](#word-count)
    - [Topic research](#topic-research)
    - [The Outline](#the-outline)
    - [The Introduction](#the-introduction)
    - [Body](#body)
    - [Conclusion](#conclusion)
    - [Support Claims With Evidence](#support-claims-with-evidence)
    - [Content Exemplars](#content-exemplars)
  - [Conventions](#conventions)
    - [Deadline:](#deadline)
    - [Write in Markdown](#write-in-markdown)
    - [Upload Images to Imgur](#upload-images-to-imgur)
    - [Use Headers to Break Up Sections](#use-headers-to-break-up-sections)
    - [Denote Code with Backticks](#denote-code-with-backticks)
    - [Use Double Quotes for Quotations](#use-double-quotes-for-quotations)
    - [Use Emphasis Sparingly](#use-emphasis-sparingly)
  - [Communication](#communication)
    - [Communicate Delays and Roadblocks to Your Editor Proactively](#communicate-delays-and-roadblocks-to-your-editor-proactively)
    - [Check Your Email When You Have an Open Assignment](#check-your-email-when-you-have-an-open-assignment)


## Voice

### Keep it simple. 

Use simple, straightforward language whenever possible.

### Use short sentences. 
Break down longer sentences into shorter ones. This helps people read faster and understand better.

### Use short paragraphs. 

Break down longer paragraphs into one or two-sentence paragraphs. Walls of text will make your readers abandon your tutorial or switch to “skimming” mode.

### Write in Second Person

Speak to your readers directly using “you” and “your.” Avoid “we” and “our.”

Good:

*You can use a web browser (like Chrome, Safari, or Edge) to access websites on the internet*

Bad:

*We can use our web browsers (like Chrome, Safari, or Edge) to access websites on the internet.*

### Use Conversational, Business-Appropriate Language

Read your content out loud and ask yourself, “Would I talk like this at work?” Use your real-world experience, but avoid jargon when possible.

Good:

*Experts agree that the internet was not the product of any individual mind, but a series of advances in networking and computer science.*

Bad:

*Many scholars would agree that, had it not been for active networks, the simulation of Lamport clocks might never have occurred. The notion that end-users synchronize with the investigation of Markov models is rarely outdated. A theoretical grand challenge in theory is the important unification of virtual machines and real-time theory. To what extent can web browsers be constructed to achieve this purpose?*


### Don’t Repeat Yourself

Eliminate wordiness. You shouldn’t repeat yourself when programming, and you shouldn’t repeat yourself when writing.

Good:

*A lively debate rages among software developers. The contentious issue is: tabs or spaces?*

Bad:

*There is currently a lively, ongoing controversy among many computer scientists and other professionals in the field of software development: theories are being spun and arguments are being conducted among them about whether the use of tabs to designate indentation in a document is superior to the use of spaces for the same purpose.*

### Stay on Topic
Your readers’ time is finite. Help your readers get as much value from your content as possible before they have to move on with their lives.

## Content

### Word count
Each article should be at least 2000 words.

### Topic research

Searching for a topic on StackOverflow and Github is a smart way to conduct in-depth research. Find various related themes, issues, answers, and examples provided by other developers.
It will allow you to go into greater depth and provide good examples. 

As an example, consider the following topic: 'Python zip function'

The StackOverflow link below goes beyond the basic use of the Python zip function. 
It delves into numerous use cases involving various Python data types and provides concrete examples. 
If you look closely, you will discover that the StackOverflow page inspires the actual article and includes many of the same topics and examples. 

So, while StackOverflow, GitHub, and the official Python documentation can inspire, do not copy-paste code samples from these sites. 

Good: 

*Research reference:*
*https://stackoverflow.com/questions/13704860/zip-lists-in-python*

*Actual content:*
*https://realpython.com/python-zip-function/#looping-across-multiple-iterables*


Bad: 

*The following content lacks depth compared to the two resources mentioned above: 
https://www.programiz.com/python-programming/methods/built-in/zip*

### The Outline
- Title
- Introduction
  - Point 1
  - Point 2
- Body
  - Point 1
  - Point 2
  - Point 3
- Conclusion

### The Introduction

Every content should have a 1-3 paragraph introduction. This introduction should accomplish two things:
- Briefly tell readers what the content is about.
- Hook your readers. Give them a reason to continue reading.

Good: 

*Python’s zip() function creates an iterator that will aggregate elements from two or more iterables. You can use the resulting iterator to quickly and consistently solve common programming problems, like creating dictionaries. In this tutorial, you’ll discover the logic behind the Python zip() function and how you can use it to solve real-world problems.*

*By the end of this tutorial, you’ll learn:*

- *How zip() works in both Python 3 and Python 2*
- *How to use the Python zip() function for parallel iteration*
- *How to create dictionaries on the fly using zip()*

Bad (no “hook”):

*Postgres provides rich support for JSON fields, which can be very handy. Both JSON data types (json and jsonb) allow you to store entire objects or lists directly in your database. This means that you can store any number of user preferences in one column.
In this post, I’ll show you how to use Postgres’ JSON fields in a Django web application. You’ll learn about the differences between json and jsonb, how to query JSON data and some of the drawbacks of storing your data in JSON.*

### Body

There will be multiple headings and subheadings in the body of your content. It allows the reader to swiftly browse through your content and identify the information that is important to them.  

Add headers and subheadings to assist your readers in understanding the topic better:

1. See the official Python documentation if you require documented information about your topic or notion.
2. Use StackOverflow and GitHub to find several examples showcasing the usage of the topic.
3. Come up with your own examples that provide the opportunity to explain the topic further.

Example breakdown:

- ##### Understanding the Python zip() Function
- ##### Using zip() in Python
  - Passing n Arguments
  - Passing No Arguments
  - Passing One Argument
  - Passing Arguments of Unequal Length
- ##### Looping Over Multiple Iterables
  - Traversing Lists in Parallel
  - Traversing Dictionaries in Parallel
  - Unzipping a Sequence
  - Sorting in Parallel
  - Calculating in Pairs
  - Building 


The first header provides the zip function with additional context. At least 2 concrete examples should support each heading or subheading.

The second header divides the use of the zip function into subsections. At least 2 concrete examples should also support each heading or subheading.

On the other hand, the third heading provides subheadings that provide more practical applications of the zip function. At least 2 concrete examples should also support each subheading.

**Note: Include as many headings and subheadings as are required to provide clear and in-depth writing on the topic.**

### Conclusion
This section brings your writing to a close and summarizes what the reader has learned. Your content should include a 1-2 paragraph conclusion. It should restate the thesis of the content and remind your readers what they learned. 

Good:

*In this tutorial, you’ve learned how to use Python’s zip() function. zip() can receive multiple iterables as input. It returns an iterator that can generate tuples with paired elements from each argument. The resulting iterator can be quite useful when you need to process multiple iterables in a single loop and perform some actions on their items at the same time.*

*Now you can:*

- *Use the zip() function in both Python 3 and Python 2*
- *Loop over multiple iterables and perform different actions on their items in parallel*
- *Create and update dictionaries on the fly by zipping two input iterables together*
  
*You’ve also coded a few examples that you can use as a starting point for implementing your own solutions using Python’s zip() function. Feel free to modify these examples as you explore zip() in depth!*


### Support Claims With Evidence

Ask yourself for every claim you make, “How can I prove this?” You can do this by:
- Citing an academic study
- Linking to the official documentation

Good:

*While [Postgres can handle hundreds of columns](https://nerderati.com/2017/01/03/postgresql-tables-can-have-at-most-1600-columns/), it might not be a good idea to take advantage of this feature.*

Bad:

*While I’m guessing Postgres can handle a lot of columns, it might not be a good idea to use more than a hundred if you can help it.*


### Content Exemplars
- https://realpython.com/python-exceptions/
- https://realpython.com/python-use-global-variable-in-function/
- https://realpython.com/how-to-split-a-python-list-into-chunks/
- https://kinsta.com/blog/react-best-practices/
- https://www.freecodecamp.org/news/how-to-build-and-publish-python-packages-with-poetry/
- https://realpython.com/python-string-concatenation/



## Conventions 

### Deadline:
3 business days 

### Write in Markdown

All articles should be written in Markdown and submitted in the Google Doc sent to you when you accept the assignment.

Good:

*Markdown is a formatting language often *used by static site generators* and *blogs*. If you aren’t familiar with its syntax, you can [click here to learn more](https://guides.github.com/features/mastering-markdown/).*

### Upload Images to Imgur

If you have screenshots or diagrams in your content, upload them to Imgur’s free image hosting service and embed them using Markdown. Include descriptive text inside the brackets ([...]) so that screen readers can describe the image.

Good:

`![A diagram showing different computer hardware](https://i.imgur.com/hBE7ZF8.jpg)`

Bad:

`![](https://www.my-private-image-server.net/image-1.png)`

### Use Headers to Break Up Sections

Headers make your content more scannable. Use ##, ###, and #### header tags to denote different sections. Headings should be written in title case.
Good:

*## How to Use JSON Fields in Your Python Application*
*…*
*### The Two JSON Formats Supported by Postgres*
*…*

Bad (not title case):

*## How to use JSON fields in your Python application*
*### The two JSON formats supported by Postgres*
*…*

### Denote Code with Backticks

Use code blocks when the code is one or more lines long or deserves special emphasis.

Good:

```
function snafu() {
return null;
}
```
Bad:

`function snafu() {
return null;
}`
Use inline code when referring to a variable name or short command in context.

Good:

*Call the `snafu()` method to exit and return to your command line.*

Bad:

*Call the “snafu()” method to exit and return to your command line.*

### Use Double Quotes for Quotations

Use blockquotes when the quote is two or more lines long.

Good:

> *Some text leading up to the quote.*
>*“The field/element/path extraction operators return NULL, rather than failing, if the JSON input does not have the right structure to match the request; for example if no such key or array element exists.”*
>*Some text after the quote.*

Bad:

*Some text leading up to the quote. “The field/element/path extraction operators return NULL, rather than failing, if the JSON input does not have the right structure to match the request; for example if no such key or array element exists.” Some text after the quote.*

Use inline quotes when the quote is relatively short or when you’re referencing a single word or phrase.

Good:

*“There’s nothing to see here,” said Davies.*

Bad:

*“There’s nothing to see here.” - Davies*

### Use Emphasis Sparingly

Use italics to emphasize text or use bold to suggest strong emphasis.

Good:
*There is *nothing* as important as using **spaces** to indent your code.*

## Communication

### Communicate Delays and Roadblocks to Your Editor Proactively
You will not be penalized for late work if you’ve been in communication with us about the assignment. We can offer technical help and extensions, but you must ask two or more days before the due date.

Good:

*Hey James,
I know the Postgres content is due next week, but I’m running into trouble. Would you be willing to hop on a quick call and explain the JSON fields in Postgres? Or do you have any resources that might help me out?*

Bad:

*Hey James,
I know my Postgres content was due today, but I’m not able to figure out the JSON fields in Postgres. Could I have an extension until next week to struggle with it more?

Authors must communicate on time to meet deadlines to be eligible for future assignments.

### Check Your Email When You Have an Open Assignment
While you have an open assignment, you should respond to emails within 48 hours unless you’ve notified us of your unavailability. If the assignment is overdue, you should respond within 24 hours.

Good:

*Hey James,
Thanks for the update on this content. I’ll keep that in mind while I’m working on the piece this weekend.*

Bad:

*Hey James,
Sorry, but I didn’t see your email until today and I know the content is due now. I’ll try to incorporate your feedback before midnight if I can.*

Authors that fail to respond to emails about open assignments will not be eligible for future assignments.

