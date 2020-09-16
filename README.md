# Project Farfalla

A startup near you is undergoing a digital *transformation*. The UX-focused redesign of their web services is documented here and will be updated over time. 

This is a break down of the **design process** for recreating a digital experience. This repository is for internal use for members of the team to see the steps involved and see where they want to be involved. 

### Contents

1. [Introduction](#introduction)
1. [Start with the Users](#start-with-the-users)
2. [What does the business want?](#what-does-the-business-want)
3. [User Journeys and Solution Architecture](#user-journey-and-solution-architecture)
4. [Wire-frames + Copy](#wire-frames--copy)
5. [Prototype](#prototype)
6. [User Stories for Development](#user-stories-for-development)
7. [Perfect - Testing and refining the Solution](#testing-and-refining-the-solution)

## Introduction

![Metamorphosis][morph]

> ### Web design is dead. Long live experience design.

A user experience is the user's perception of a company across *one moment* of contact **and** *all moments* of contact. This project has the aim of designing the holistic experience of the users of a vocational learning platform.

For a more detailed introduction to the **key concepts** I have gathered from my *brief* time working in User Experience design, and a break down of the processes involved in a design project [see my Hackpad](https://hackpad.com/UX-Basics-bqKIa5C6FIc#:h=Introduction).

#### Project Success:

Users distinct concerns are met with a personalised value proposition which is attractive and engaging. The platform is simple to understand and pleasing to use. The platform accurately meets the goals of the users which include discovering content and connecting with other users.

#### Project Failure:



## Start with the Users

- Get data on the users:
    * Demographic data
    * Usage analytics

- Build out User Personas:
    - For every side of business
    - For every demographic
    - For potential and actual

User personas will define each user's broad wants and goals considering their wellbeing (*economic, financial and mental....*)

#### Example User Persona

![User Persona][persona]

The user personas act as a _"Common Currency"_ between all departments of the team. They allow all individuals to talk about the requirements and constraints of the platform in terms of users. Doing so also allows me to ensure the I am designing for the people using the platform and not for myself.

## What does the business want?

Defining this will require reference to the project success and failure criteria _i.e. what does the business want to achieve?_

Definitive Business Requirements will form:

- the constraints of the project (e.g. sign up before you can do that)
- the hoops through which users will have to jump to achieve some of their goals
- the way that achieving goals will be facilitated

## User Journey and Solution Architecture

To visualise the logical result of the materials that have been created so far, the following will be created:

- Site map based on the most logical progression from entry to goal - user journey.
- Process Flow the details of the user journey: decision making and conditionals.

If the progression through the user journey is logical, fits the behavioural requirements set out by the personas, and offers something that might be considered a positive and un-anxious experience then the interface is ready to be designed and prototyped.

Moving from here to the next step 

## Wire-frames + Copy

Wire-frames can be anything from a sketch on a piece of paper to a sophisticated photoshop rendering. I will be using Omni-Graffle to create template designs and working closely with the other creative forces in the team to decide the language.

These designs will be created constantly and in an iterative loop of feedback, redesign, feedback, redesign. In our scenario the wireframes will probably go up on the office walls for the whole team to see and critique. Team members will be invited to write notes or attach sticky notes.

Eventually this process of refinement will leave us with an ideal solution to the problems exposed earlier. Once we have something that everyone is happy with and has received sign-off from the Product Owner, I will create a working prototype.

## Prototype

I will build a prototype using a static site generator to be determined closer to the time. Pages will be built in HTML CSS and JS (to mimic end to end functionality). This will be presented for testing with a *User Group* who will provide feedback on their experiences. _The scripts for testing the prototype will be written at the time._ For more on User-testing [see here](./user-testing.md).

Creating a prototype in the languages that will actually be used in the development process will streamline the development cycle and plays to my strengths. 

Moving to the next stage - the first development sprint will depend on the results of the user tests and require final sign-off from the Product Owner. 

## User Stories for Development

This must be kept clean and there must be a process in place for writing stories. [Our process for adding stories.](./story-writing.md)

Ideally Increment the numbers as they go into the PM tool, however, Pivotal Tracker doesn't provide for this :(

The developers and the Product Owner need to be involved in writing the user stories. This will hopefully take the form of a full day workshop. 

### Start with the Epics

As a user I want to do this broad thing e.g.
As a potential learner I want to take a course about engineering 

As far as the user stories are concerned, this means that you can avoid things like: 

> "AS A user I WANT TO get better at French SO THAT I can live in France"

Sure, that's a story about the user and reflects their wants and needs but it is not do-able. Here, the definition of done is impossible to measure. 

### Break down Epics
By limiting the user's wants and goals to the needs of the business - force the user to accept that this is the way it has to be - stories can become more granular, testable, and the definition of done is more binary. 

```
AS A user
I WANT TO do a thing
SO THAT to achieve a goal
```

### Add Acceptance Criteria

- Automated code tests are passing
- User Tests are Passing
- Sign-off

[More information on writing user stories (GOV.UK)](https://www.gov.uk/service-manual/agile/writing-user-stories.html)

## Testing and refining the Solution

*There is always room for improvement.*

Were the problems defined actually solved?

Are the users happy?

_To allow the UX to continue to improve over time, feedback must be collected from the users as they use the platform and regular test groups should be arranged._

[morph]: img/Metamorphosis.jpg "Metamorphosis"
[persona]: img/persona.jpg "User Persona"
