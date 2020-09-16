# Using Pivotal Tracker (Internal Notes)

> ### It's worth becoming a good story teller

![New Stories][add1]

On Pivotal Tracker the tasks that need to be completed are called **stories**. 

This nomenclature reflects the nature of functionality in software development generally and in particular in [Behaviour Driven Development (BDD)](http://guide.agilealliance.org/guide/bdd.html) which is a form of software development we will be engaging in going forward. i.e.

> ###### When this person gets to this point they want this to happen, but only if this has already happend.

It's a miniature story in the present tense!

---

This guide is intended to help you write stories that are as clear and useful to other members of the team as possible. **Remember**, when you write a story, *even if it's just for you*, try to follow best practices. 

#### Why do I need to write good stories?
    
- Your job becomes easier because you and they can just get on with the task at hand.
- There is no need to engage in a back and forth about clarifying this word or that phrase.
- There is no "down time" on important stories that are rejected due to unclear or clumsy wording.
- Well defined stories can be tested. 

---

## Writing a Story

![Add a story][empty]

#### The first thing you have to do

is decide whether your story is an Epic, a Feature, a Bug, a Chore, or a Release.

- **Epics** are very large and multi-faceted stories. They comprise multiple tasks. They cannot be completed without breaking them down further into lots of other stories. Epics are a great starting point for focusing the direction of the rest of your stories.
- **Features** are smaller, broken-down stories that provide __verifiable business value to the users__. Going forward, the "verifiable" part will be brought about as a result of thorough user research and user testing.
- **Bugs** are basically just faults or unexpected behaviour. They are very important to stay on top of so add them to the tracker as soon as you can. 
- **Chores** are stories that are necessary but of __no direct value to the users__. They might be ongoing stories that have to be done every day of a project.

---

## User Stories

#### What is a User Story?

A User Story is simply a way of writing stories.

#### User stories take this form:

```
AS A user
I WANT TO do/see this thing
SO THAT I can do that thing
```

#### Why user stories?

They encourages the writer (_and the person working on the story_) to keep the user's needs and goals in mind as they work.

#### When should I write stories like this?

If you're adding a **Feature** or an **Epic** you should definitely write a user story because these should provide value to the user. 

It is not necessary to write in this form if you're adding bugs or releases and should not be used for chores because those provide no value to the user. 

#### Let's break down the user story to understand it better.

-  `AS A user`
    - The user in this sense will be one of the defined user personas (or a group of user personas) e.g. "As a School Leaver", "As a Learner", "As an Education Sector Client"  - These user personas will be available in this repository soon [see the task](https://www.pivotaltracker.com/n/projects/1374910/stories/98097686).
- `I WANT TO do/see this thing`
    - This is the specific task that the user **needs to do** to achieve their wider goal.
        
    Don't be confused - it may well be that the user doesn't really *want* to do what the story says e.g.
    
    > As a learner I want to sign up so that I can receive updates on new courses

    Sure, maybe I would rather receive updates on new courses without having to sign up first and so I don't _really_ "want" to sign up, but that is the way the system works right now and so, to achieve my wider goal of receiving updates, I must sign up.

- `SO THAT I can do that thing`
    - This is the tangible value to the user. Adding this piece of information is extremely useful for keeping those end-goals in mind. 

---

## Start with the Epics

As a user I want to do this broad thing e.g.

> As a potential learner I WANT TO take a course about engineering SO THAT I can work for that company

> AS A learner I WANT TO get better at French SO THAT I can live in France.

Sure, that's a story about the user and reflects their wants and needs but it is not do-able. Here, the definition of done is impossible to measure. 

#### Break down the Epics

How can the broad story that you've written be broken down into more granular parts? 

This should always be the first thing you try to do. The more you can break down a story into smaller stories, the clearer it will be for other people to understand. If you're worried about losing track of all the stories Pivotal Tracker allows you to make stories part of an epic by adding a label to it and you can reference stories together using their 'unique ID' - [see example](https://www.pivotaltracker.com/n/projects/1374910/stories/99524580).

## Add Details

> If you could elaborate as much as you can in the description box I might get a better sense of what you mean by "see the images".

> If you could sketch our a crude wire-frame, take a photo of it and add it via Google Drive to the story you have written that would be *super* helpful for those particularly meta, tough-to-visualise stories.

> If you could include a little diagram that shows the pages you're referring to in the navigation that would really help me understand what you mean.

Adding additionaly details about the story you have written is essential. You don't need to include a photoshop wireframe with every story but a little bit of explanation for the lay-person goes a very long way. 

#### Add Acceptance Criteria

This can be done in the tasks section or elsewhere depending on what you feel makes most sense. You need to make it clear what the "definition of done" is. What things need to be giving us the OK before we conclude that this story can be accepted by the product owner?

## Start a Conversation

#### Do you need someone else's input?

Tag that person in a comment using the @ symbol and ask their opinion on the details of the story.

> @coderfriend Have I thought of all the things that might come up?

## My Story was Rejected! :(

#### If this happens to you

It's probably because the story was not clear enough. Don't be disheartened, though, start a conversation with someone about how it could be improved! 

*The most common reason for rejecting a story is that it can't be done. References to "the issue" or "the problem" will get you a one-way ticket to rejection town.*

[More information on writing user stories (GOV.UK)](https://www.gov.uk/service-manual/agile/writing-user-stories.html)


[add1]: img/stories/add-story.png "Click to add a story"
[empty]: img/stories/empty-story-top.png "An empty story in Pivotal Tracker"