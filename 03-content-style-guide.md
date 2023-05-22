
- [Voice](#voice)
      - [Keep it simple.](#keep-it-simple)
      - [Use short sentences.](#use-short-sentences)
      - [Use short paragraphs.](#use-short-paragraphs)
      - [Write in Second Person](#write-in-second-person)
      - [Use Conversational, Business-Appropriate Language](#use-conversational-business-appropriate-language)
      - [Don’t Repeat Yourself](#dont-repeat-yourself)
      - [Stay on Topic](#stay-on-topic)
- [Content](#content)
      - [The Introduction](#the-introduction)
      - [Use Sub-headings to Structure Your Main Concepts](#use-sub-headings-to-structure-your-main-concepts)
      - [Support Claims With Evidence](#support-claims-with-evidence)
      - [The Conclusion](#the-conclusion)
      - [Sample Contents](#sample-contents)
- [Conventions](#conventions)
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

##### Keep it simple. 

Use simple, straightforward language whenever possible.

##### Use short sentences. 
Break down longer sentences into shorter ones. This helps people read faster and understand better.

##### Use short paragraphs. 

Break down longer paragraphs into one or two sentence paragraphs. Walls of text will make your readers abandon your tutorial or switch to “skimming” mode.

##### Write in Second Person

Speak to your readers directly using “you” and “your.” Avoid “we” and “our.”

Good:

*You can use a web browser (like Chrome, Safari, or Edge) to access web sites on the internet*

Bad:

*We can use our web browsers (like Chrome, Safari, or Edge) to access web sites on the internet.*

##### Use Conversational, Business-Appropriate Language

Read your content out loud and ask yourself, “Would I talk like this at work?” Use your real-world experience, but avoid jargon when possible.

Good:

*Experts agree that the internet was not the product of any individual mind, but a series of advances in networking and computer science.*

Bad:

*Many scholars would agree that, had it not been for active networks, the simulation of Lamport clocks might never have occurred. The notion that end-users synchronize with the investigation of Markov models is rarely outdated. A theoretical grand challenge in theory is the important unification of virtual machines and real-time theory. To what extent can web browsers be constructed to achieve this purpose?*


##### Don’t Repeat Yourself

Eliminate wordiness. You shouldn’t repeat yourself when programming, and you shouldn’t repeat yourself when writing.

Good:

*A lively debate rages among software developers. The contentious issue is: tabs or spaces?*

Bad:

*There is currently a lively, ongoing controversy among many computer scientists and other professionals in the field of software development: theories are being spun and arguments are being conducted among them about whether the use of tabs to designate indentation in a document is superior to the use of spaces for the same purpose.*

##### Stay on Topic
Your readers’ time is finite. Help your readers to get as much value out of your content as possible before they have to move on with their lives.

## Content

##### The Introduction

Every content should have a 1-3 paragraph introduction. This introduction should accomplish two things:
- Briefly tell readers what the content is about.
- Hook your readers. Give them a reason to continue reading.

Good: 

*I remember the first time I built user preferences into an app. At first, users just needed to be able to opt in or out of our weekly emails. “No big deal,” I thought, “I’ll just add a new field on the Users table.” For a while, that was fine. A few weeks later, my boss asked me if we could let users opt into push notifications. Fine, that’s just one more column on the database. Can’t hurt, right?
You probably see where this is going.
Within months, my user table had 40 columns, and while Postgres can handle it, it gets pretty tricky for new devs to keep up with all of them.
Fortunately, Postgres provides rich support for JSON fields, which can be very handy in situations like mine. Both JSON data types (json and jsonb) allow you to store entire objects or lists directly in your database. This means that you can store any number of user preferences in one column.
In this post, I’ll show you how to use Postgres’ JSON fields in a Django web application. You’ll learn about the differences between json and jsonb, how to query JSON data and some of the drawbacks of storing your data in JSON.*

Bad (no “hook”):

*Postgres provides rich support for JSON fields, which can be very handy. Both JSON data types (json and jsonb) allow you to store entire objects or lists directly in your database. This means that you can store any number of user preferences in one column.
In this post, I’ll show you how to use Postgres’ JSON fields in a Django web application. You’ll learn about the differences between json and jsonb, how to query JSON data and some of the drawbacks of storing your data in JSON.*

##### Use Sub-headings to Structure Your Main Concepts
Structure your text with sub-headings. For every main concept related to your original topic, add sub-headings to introduce the concepts.

Good:

- *Exceptions versus Syntax Errors*
- *Raising an Exception*
- *The AssertionError Exception*
- *The try and except Block: Handling Exceptions*

Bad:

*Writing about several different topics without any structure.*


##### Support Claims With Evidence

For every claim you make, ask yourself, “How can I prove this?” You can do this by:
- Including a link to a reputable content
- Including a quote from another source
- Citing an academic study
- Linking to the official documentation
- Interviewing knowledgeable professionals

Good:

*While [Postgres can handle hundreds of columns](https://nerderati.com/2017/01/03/postgresql-tables-can-have-at-most-1600-columns/), it might not be a good idea to take advantage of this feature.*

Bad:

*While I’m guessing Postgres can handle a lot of columns, it might not be a good idea to use more than a hundred if you can help it.*

##### The Conclusion

Every content should include a 1-2 paragraph conclusion. This should restate the thesis of the content and remind readers what they learned. It may also include other resources readers can reference to learn more.

Good:

*While JSON data types come with some drawbacks, they are useful when you need more flexibility in your data structure. Thanks to Django’s native support for `jsonb`, you can get started using JSON data in your web applications without [learning all the native Postgres query operators](https://www.postgresql.org/docs/current/functions-json.html).
Next time you need more flexibility in your data model and want to benefit from the strengths of Postgres give `jsonb` fields a try.*

##### Sample Contents
- https://realpython.com/python-exceptions/
- https://realpython.com/python-use-global-variable-in-function/
- https://realpython.com/how-to-split-a-python-list-into-chunks/
- https://kinsta.com/blog/react-best-practices/
- https://www.freecodecamp.org/news/how-to-build-and-publish-python-packages-with-poetry/
- https://realpython.com/python-string-concatenation/

## Conventions 

##### Write in Markdown

All articles should be written in Markdown and submitted in the Google Doc sent to you when you accept the assignment.

Good:

*Markdown is a formatting language often *used by static site generators* and *blogs*. If you aren’t familiar with its syntax, you can [click here to learn more](https://guides.github.com/features/mastering-markdown/).*

##### Upload Images to Imgur

If you have screenshots or diagrams in your content, upload them to Imgur’s free image hosting service and embed them using Markdown. Include descriptive text inside the brackets ([...]) so that screen readers can describe the image.

Good:

*![A diagram showing different computer hardware](https://i.imgur.com/hBE7ZF8.jpg)*

Bad:

*![](https://www.my-private-image-server.net/image-1.png)*

##### Use Headers to Break Up Sections

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

##### Denote Code with Backticks

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

##### Use Double Quotes for Quotations

Use blockquotes when the quote is two or more lines long.

Good:

*Some text leading up to the quote.
> “The field/element/path extraction operators return NULL, rather than failing, if the JSON input does not have the right structure to match the request; for example if no such key or array element exists.”
Some text after the quote.*

Bad:

*Some text leading up to the quote. “The field/element/path extraction operators return NULL, rather than failing, if the JSON input does not have the right structure to match the request; for example if no such key or array element exists.” Some text after the quote.
Use inline quotes when the quote is relatively short or when you’re referencing a single word or phrase.*

Good:

*“There’s nothing to see here,” said Davies.*

Bad:

*> “There’s nothing to see here.” - Davies*

##### Use Emphasis Sparingly

Use italics to emphasize text or use bold to suggest strong emphasis.

Good:
*There is *nothing* as important as using **spaces** to indent your code.*

## Communication

##### Communicate Delays and Roadblocks to Your Editor Proactively
You will not be penalized for late work if you’ve been in communication with us about the assignment. We can offer technical help and extensions, but you must ask two or more days before the due date.

Good:

*Hey James,
I know the Postgres content is due next week, but I’m running into trouble. Would you be willing to hop on a quick call and explain the JSON fields in Postgres? Or do you have any resources that might help me out?*

Bad:

*Hey James,
I know my Postgres content was due today, but I’m not able to figure out the JSON fields in Postgres. Could I have an extension until next week to struggle with it more?
Authors that miss deadlines without communicating will not be eligible for future assignments.
Check Your Email When You Have an Open Assignment
While you have an open assignment, you should respond to emails within 48 hours unless you’ve notified us of your unavailability. If the assignment is overdue, you should respond within 24 hours.*

Good:

*Hey James,
Thanks for the update on this content. I’ll keep that in mind while I’m working on the piece this weekend.*

Bad:

*Hey James,
Sorry, but I didn’t see your email until today and I know the content is due now. I’ll try to incorporate your feedback before midnight if I can.*

Authors that fail to respond to emails about open assignments will not be eligible for future assignments.


*This content brief template is provided free of charge from Draft.dev. It may be used and distributed freely with attribution by linking to the source at Draft.dev/#playbook.*

##### Check Your Email When You Have an Open Assignment
While you have an open assignment, you should respond to emails within 48 hours unless you’ve notified us of your unavailability. If the assignment is overdue, you should respond within 24 hours.

Good:

*Hey James,
Thanks for the update on this content. I’ll keep that in mind while I’m working on the piece this weekend.*

Bad:

*Hey James,
Sorry, but I didn’t see your email until today and I know the content is due now. I’ll try to incorporate your feedback before midnight if I can.*

Authors that fail to respond to emails about open assignments will not be eligible for future assignments.

This guide has been produced with the help of style guides provided by freecodecamp.com, Draft.dev and others.
