---
layout: essay
type: essay
title: "ICS 314: Software Engineering I"
date: 2024-12-18
published: true
category: "reflections"
labels:
  - Project Manapement
  - Coding Standards
  - Design Patterns
  - Software Engineering
  - Web Application Development
---

Throughout ICS314, what we worked on was considered web application development. This may seem rather odd in a class titled 'Software Engineering I'. However, the concepts that we have learned are applicable to more than just web application development. Reflecting on the course material thus far, I recognise some ideas that applied to projects I have done previous to this class. 

# Reflecting on Applicable Concepts

One of my most significant and recent non-programming projects was a [spreadsheet calculator](https://jaydenontalancapistrano.github.io/projects/spreadsheetcalculator.html) for a mobile game. The point of the spreadsheet was to calculate spell and character stats. There are ideas we learned in class that I unknowingly applied to the project--to some extent.

## Agile Project Management (APM)


APM is an approach to project management that breaks the work into smaller and manageable pieces. Issue-Driven Project Management (IDPM) emphasises priority in addressing issues and tasks to keep the project organised and adaptable.

<div style="text-align: center;">
  <strong style="font-size: 24px; padding-top: 24px;">List of Issues</strong>
  <br>
  <img src="../img/ics314reflection/issues-list.png" alt="List of Issues Sheet" width="250" style="padding-top: 16px; padding-bottom: 24px;" />
</div>

In the spreadsheet project, I had a list on the first sheet that kept track of things that needed to be done. For example, portions of the calculator that were still not implemented, issues that I noticed with the game, issues in the calculator, etc. With this approach, I was able to identify and slowly work out many kinks one at a time. If I had not tracked down different issues, I likely would have burnt out far earlier in the development of the calculator. Breaking it down allowed me to slowly build the calculator up step by step--assuring robustness.

## Coding Standards

Coding with Standards is following rules and conventions to maintain consistency. As mentioned, the spreadsheet calculator was not a software project, but I still followed rules and conventions. For background, the fields of my spreadsheet are labelled. Doing this makes it easy to implement into more complex formulae. If I implemented this without naming conventions, I would struggle to find, use or understand a variable. Implementing labels improved my ability to read and understand formulae in the long run--when I did not have time to work on it--and allowed me to easily implement more complex formulae easily.

## Designing Patterns

Design patterns are best practices used to avoid common problems when designing systems. For example, a modular structure. This emphasises smaller parts making up a project by having independent but smaller functions; it is more easily maintainable.

<div style="text-align: center;">
  <strong style="font-size: 24px; padding-top: 24px;">Item's Front-end</strong>
  <br>
  <img src="../img/ics314reflection/items-front-end.png" alt="Item's Front-end Sheet" width="650" style="padding-top: 16px; padding-bottom: 24px;" />
  <br>
  <strong style="font-size: 24px; padding-top: 24px;">Item's Back-end</strong>
  <br>
  <img src="../img/ics314reflection/items-back-end.png" alt="Item's Back-end Sheet" width="650" style="padding-top: 16px; padding-bottom: 24px;" />
</div>

In the spreadsheet, I separated all pages into front and back ends. The back end broke up, organised, or held the needed data to be used in more complex areas. Items are mixed up on the front-end items page, so I strived to reorganise them on my back-end page.

<div style="text-align: center;">
  <strong style="font-size: 24px; padding-top: 24px;">Spell's Back-end</strong>
  <br>
  <img src="../img/ics314reflection/spells-back-end.png" alt="Spell's Back-end Sheet" width="650" style="padding-top: 16px; padding-bottom: 24px;" />
</div>

I have the basic and more advanced values in the Spells back end needed for stat calculations. By having them on their own in the back-end with no to minimal functions, I can update values with significantly less effort. I am not required to read a 250-character formula to decide what value I am supposed to change.

<div style="text-align: center;">
  <strong style="font-size: 24px; padding-top: 24px;">Main Back-end</strong>
  <br>
  <img src="../img/ics314reflection/main-back-end.png" alt="Main Back-end Sheet" width="650" style="padding-top: 16px; padding-bottom: 24px;" />
</div>

The main back end page has the final stat calculations for the character broken up into smaller pieces. Another pro to modular coding is expanding the types of implementations available. Some of these were core focuses I wanted with my calculator.

# Conclusion

Although the tech stack we worked on in ICS 314 made it seem like a web development course, the concepts we learned extended far beyond that. Agile Project Management, CodingStandards and Design Patterns are applicable elsewhere, let alone in other spheres of software engineering. Reflecting on this course with my old spreadsheet calculator in mind assisted me in realising how applicable the skills we learned are. 