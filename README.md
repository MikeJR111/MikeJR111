# Culture Amp Technical Interview Exercise

In this exercise, we look forward to working with you and learning about how you approach hands-on technical work.

We’re sharing this exercise in advance so you can familiarise yourself with it as much (or as little) as you need. Don’t do any work ahead of time - there’ll be enough time in the interview for us to work through everything together.

## What we’ll be building

You will be provided with sample data in two formats, Markdown and JSON, and should be prepared to:

1. Design and implement a table schema (SQL) or data structure (Python) that supports the analysis

2. Query or process the data and present results for:

    a. Participation: Calculate the number and percentage of submitted responses for the survey

    b. Average results: Calculate the average result for each survey question

Any response with a submission time is considered to have participated in the survey. Results from non-submitted surveys should not be considered in the analysis.

*Depending on how we spend our time, we may not have time to implement these requirements in full, and that's okay. At a minimum, we want we get a feel for how the solution would grow to add the remaining capabilities.*

### Survey data

| Employee ID | Submission time | I like the kind of work I do. | In general, I have the resources I need to be effective. | We are working at the right pace to meet our goals. | I feel empowered to get the work done for which I am responsible. | I am appropriately involved in decisions that affect my work. |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|2014-07-28T20:35:41+00:00|5|5|5|4|4|
|2|2014-07-29T07:05:41+00:00|4|5|5|3|3|
|3|2014-07-29T17:35:41+00:00|5|5|5|5|4|
|4|||||||
|5|2014-07-30T04:05:41+00:00|4|5|5|4|4|
|6|2014-07-31T11:35:41+00:00|5|5|5|2|3|

Each row in the above table represents a response to the survey.

The headers in the table are:

- Employee ID
- Submission time *(if there is no timestamp, you can assume this person did not submit a survey)*
- A column for the answer to each of the 5 survey questions. The headers contain the question text.

The answers to questions are always an integer between (and including) 1 and 5. Blank values represent not answered questions.

## Getting started

Do not write any code before the interview. Instead, here's what we'd like you to do:

- Decide whether to solve the exercise using SQL or Python. Pick the language that you’re more familiar with and that will show you at your best. We want you to focus on demonstrating the fundamentals of your chosen language rather than relying on frameworks or libraries.
- Set up your development environment in a way that you are comfortable with. If you rely on a code formatter to keep your code tidy, feel free to set this up.

## How we’ll spend our time together

This part of your interview will consist of the following:

**1. Requirements discussion (~10 minutes)**

We’ll start by confirming your understanding of the requirements, and then you’ll model a possible solution at a high level. We’ll discuss this with you as you go.

What may be useful here is to draw a diagram representing the various steps of your solution.

**2. Coding (~35 minutes)**

We’ll ask you to take the lead to start implementing the project requirements, treating us as your collaborators. **It is very unlikely we will have time to finish.**

Please don't rush to cover all the requirements within the interview time. You'd likely have to cut corners, you normally wouldn't, to do this. We want to see a true reflection of how you normally work, not a race to the finish line. We encourage you to spend this time working on the most *interesting* parts of the solution.

As in any collaborative coding situation, please talk us through your thought process as you work. If you'd normally ask a collaborator an opinion, or if they remember how to do something, ask us! If you'd normally look things up online, use the same resources you normally would.

**3. Wrap up (~5 minutes)**

We'll be tempted to use every remaining minute of the interview to write code, but we'll make a point to stop before the end to take stock:

- Did you solve the problem we set out to solve? 
- Did it turn out as you expected it to? 
- Are you especially happy or unhappy with any aspect of your work in progress?

## What we’re looking for

While we work with you, we’ll be interested in learning about the following traits, which we believe are important for engineers at Culture Amp:

- Collaboration
- Technical communication
- Problem-solving
- Attention to detail
- Proficiency with chosen programming language

But again, please don't feel pressure to demonstrate a level of mastery or experience that you do not have. Remember: "Have the courage to be vulnerable". Say when you need help or don’t know. You might know why something like test-driven development is desirable, and how you'd go about attempting this if given the opportunity, even if you don't have the hands-on experience to demonstrate this to us in this exercise.

We recognise that many technical skills are easy to pick up on the job. We're seeking to understand your *potential*. Talk us through where you're at, then show us how you currently work.

We look forward to working on this with you!
