---
layout: article
date:   2020-09-06
title:  Xierumeng's Guide to R&eacute;sum&eacute; Creation
note:   This is for making r&eacute;sum&eacute;s geared towards software development postings (and similar jobs).
categories: guide
permalink: /resources/resume-guide
---
With thanks to Gibstick (UW CS 2019), [Anonymous0] (UW CE alumnus), Kristopher Sousa (UW CE 2021), PuffyPanda (UW CE 2024), Sage Hall (UW MGTE 2024), and my Patrons.

When I give r&eacute;sum&eacute; feedback I essentially reiterate the content here. Also, remember that this is a guide, and everything I write here is only a suggestion.

# Conflicting Advice

As with all research and advice, it is important to have multiple sources, and those sources may conflict. Paraphrased from Sage Hall: Everyone giving advice on your r&eacute;sum&eacute; is doing so with the intention of giving you a better chance of being employed. Of course, the source of the advice is also important to consider:

* Classmates

* Upper year or alumni (and whether they are in the same field as you)

* Employer:
    * In the same field?
    * Hired co-ops before?

* Professor:
    * Research experience?
    * Industry experience?
    * The above in the same field?
    * Hired students before?

* Other: CECA, family, etc.

And you have to weigh conflicting advice from one source against another. But always remember: **Your r&eacute;sum&eacute; is YOUR r&eacute;sum&eacute; and you are free to accept or reject any advice**.

# Creation

There are many r&eacute;sum&eacute; templates out there that you can adapt for your own use. Typically r&eacute;sum&eacute;s are created in LaTeX or Microsoft Word and then exported to PDF format. Personally, I developed my own style using Microsoft Word 2010&copy; over several years, starting from a blank page.

TODO Links to templates

## Parsers

PuffyPanda had this experience: "I've compared identical resumes across MS Word (Exported to PDF), Google Docs (Exported to PDF) and Latex (Exported to PDF) and there was a notable difference in how the auto-resume-parsers worked. The order from best to worst was in that order."

PuffyPanda also claims that Google Docs' PDF export has weird spacing for letters and can cause issues with parsing, so it may be better to export to *.docx and check.

Not all parsers will exhibit this behaviour; some might do better on certain types of r&eacute;sum&eacute;s and worse on others. There are several r&eacute;sum&eacute; checkers that will run your r&eacute;sum&eacute; through some common parsers and inform you of the result. You can also use a PDF viewer's search tool to see if the text is being generated correctly, and when you apply, you can tell if your r&eacute;sum&eacute; is being successfully parsed by the applicant tracking system (ATS).

TODO Parser checker links

# General

These are the basics.

> An office. On a desk, a stack of r&eacute;sum&eacute;s from hopeful applicants. The employer sitting behind said desk starts its work on screening potential interview candidates by picking up half the stack and tossing it into the recycling bin. "I don't hire unlucky people," it states, before looking over the first survivor.
> <footer class="blockquote-footer">Xierumeng joke</footer>
{: class="blockquote" cite=""}

Employers will spend between 10 and 60 seconds looking at your r&eacute;sum&eacute;, looking at possibly hundreds of them over several days. Therefore, your r&eacute;sum&eacute; should be able to tell your story and convey eligibility in this extremely short period. Flow and organization are very important.

* Length - The length of your r&eacute;sum&eacute; should be at most one page. If you find yourself running out of space, you should remove content or re-arrange formatting and layout.

* Consistency - Inconsistent formatting will throw the employer off (e.g. if some points have periods at the end while others don't).

* Professional - Your r&eacute;sum&eacute; should be professional. This means no spelling or grammar mistakes, no vulgarity, etc. It should not be in first person.

* Images - There should be no images (other than perhaps icons).

## Layout

* Columns - I prefer one column layouts over two column layouts, because when I look at two column layouts I'm not sure where to look which is very distracting. Automated scanning systems will also most likely screw up on two column layouts.

* Margins - I recommend margins of 15 mm to 25 mm. Gibstick recommends margins of at least 25 mm: "The majority of r&eacute;sum&eacute;s I see have tiny ass margins that make it unreadable cause your eyes have to travel five miles across the page". Just don't make them too narrow.

* Spacing - Make sure the spacing between lines is good.

* Separation - Make sure each section and sub-section are properly separated.

* Placement - Order your sub-sections by importance, not chronologically. A good older project should be higher than a mediocre new project.

## Font

* Type - I prefer sans-serif fonts because they have less clutter, but both serif and sans-serif are fine. You should avoid monospaced fonts or fonts that are similar to monospaced fonts.

* Size - Don't make it too small.

* Colour - Some colour adds personality to your r&eacute;sum&eacute;. However, make sure that it will appear alright if converted to greyscale (most likely through a printer). Also make sure colouring is consistent. I'm not a fan of multiple colours on a single line.

* Bolding - Personally I don't like bolding in the points, as I find it distracting. If you are bolding, less is more. If you choose to bold, only bold important keywords such as languages and technologies used.

# Header

* Some r&eacute;sum&eacute;s have light text on dark background. I find it distracting as it makes the r&eacute;sum&eacute; feel "top-heavy". Also RIP ink usage if it's printed.

* Name - The name should be big and centred (maybe even bolded).

* Year and program - Possibly redundant information. Kristopher thinks it's worth keeping if you're applying through WaterlooWorksn't, as the application package will have your year and program. Otherwise, your Education section will be first (as stated below). Up to you.

* Contact and information - Icons can be used as separators and they look nicer than (e.g. "Email:"). Make sure to hyperlink, but for the displayed text you can drop the protocol ("https://" and "www") (e.g. [linkedin.com/](https://www.linkedin.com/) links to https://www.linkedin.com/).

    * Email - This should be your UW email, and should be "first.last@uwaterloo.ca" or something similar. You can set this in WatIAM. Link it with mailto:.

    * Phone - Self-explanatory but not necessary. No hurt in including or excluding it. Can be hyperlinked with tel:.

    * GitHub - GitHub or another code hosting website is a great way of showcasing your projects.

    * LinkedIn - I never found a good use for LinkedIn other than an obligatory timeline of my life. I have it mainly because it's generally expected.

    * Website - If you have a website, it's another great way of showcasing your projects. You can also add personal touches (such as hobbies) that would otherwise not be appropriate on GitHub or your r&eacute;sum&eacute;.

    * Address - Not needed.

# Sections

* Titles - The titles should be large enough that they are distinct from the sub-titles and body text, but not in a way where they completely overshadow the content (i.e. don't make them too big). It should also be different (e.g. bold and/or uppercase). Horizontal lines/underlining can be used to help separation.

* Types - I recommend four sections. More detail in each one below.

    * Skills - Rather than "Summary of Qualifications". This should be at the top. [Anonymous0] writes to move this to the bottom once you have experience.

    * Projects - Depending on your side projects vs work experience, either Projects or Experience should be before the other.

    * Experience - Rather than "Relevant Experience".

    * Education - If you're applying through WaterlooWorksn't, this goes last. Otherwise first.

    * Awards/Achievements - If you've won any large awards (e.g. Loran) then it may be worthwhile to include them.

## Skills

This section should be a very brief summary of your familiarity with different tools, and is basically consisted of keywords. Do not bother putting soft skills, as employers already expect you to have them and they should be implicit in your points (e.g. no "good at time management, hardworking, fast learner, team player").

* Languages - Programming languages you are familiar with.

* Tools - This could be "technologies" or "libraries" or "frameworks", essentially all the tools you are familiar with (e.g. "Git").

If you're applying for jobs in the government or in a foreign country then it may be useful to list the relevant human languages you know (e.g. "French"). Won't be useful most of the time.

A summary of qualifications (using sentences to describe your skills and what you did) is a waste of space and words. There is no need for a table of contents for a single page.

## Experience

This section contains any relevant work and volunteer experience. If you have no/very little relevant experience, add one or two irrelevant experiences in this section (something is better than nothing). This section should not be missing or empty.

### Sub-sections

* Sub-titles - Name of company, position title, languages/tools used, location (optional). This can be two lines.

    * Position title does not necessarily need to match what the company gave you. You can use them to show what you did (e.g. "Android Developer" over "Software Developer"). Do note that using "Engineer" is illegal; replace it with "Engineering".

    * Avoid the @ symbol as it looks ugly.

* Dates - Include the start and end date ("present" if it is ongoing when you submit your r&eacute;sum&eacute;). I put the dates on the right margin. The format I use is "Abbreviated month year - Abbreviated month year" (e.g. "Jan. 2005 - Dec. 2008").

    * There are multiple ways of abbreviating the months: Jun. vs June, Jul. vs July, Sep. vs Sept. Just keep it consistent throughout (e.g. if September is abbreviated to "Sept." then abbreviate all instances in the same manner).

* Points - There should be two to five points in each sub-section. More detail about points below.

## Projects

This section contains any side projects you've worked on in your free time. Make sure to include projects that have enough complexity to be interesting; they should be doing something.

Small high school/university assignments aren't usually worth putting on your r&eacute;sum&eacute; unless you've extended them since submission or you have no other technical experience (something is better than nothing). Also be careful putting university assignment code online, as policy 71 (academic integrity) may be invoked on you. You do not want to be hit with the policy 71 hammer.

This is mainly because assignment questions tend to be re-used with little change, but I've also seen the [argument](https://uwaterloo.ca/math/code-sharing-policy) that the professor also has a claim to the intellectual property as it is them who wrote the assignment question and marked the submitted code (i.e. your assignment code wouldn't have existed without the assignment).

Douglas Harder also has an [article](https://ece.uwaterloo.ca/~ece150/Resumes/) about sharing course code.

### Sub-sections

* Sub-titles - Name of the project, languages/tools used. This should be one line. You can also add a link to GitHub here.

* Dates - I used to have dates and then I removed them because they weren't important.

* Points - There should be two to five points in each sub-section. More detail about points below.

## Education

This section contains your education. Don't bother including high school.

* Name of school - "University of Waterloo".

* Degree and program - If you don't currently have a degree, you are not supposed to write it. However, you are working towards a degree, so prefixing with "Candidate for" is fine (e.g. "Candidate for B.A. in Meme Engineering").

* Dates - Include the start and end date. If you are still in the program, add "expected" to the end date which should still be in the future.

* Courses - You can put any course names you think are relevant (e.g. "Algorithms and Data Structures"). Don't put course codes as employers won't bother looking those up.

* School awards - You can put any awards that you think are worthwhile. However, President's Scholarship is one that you shouldn't as pretty much everyone got it.

# Points

Points are the details that the employer will look at after the initial screening. Each point is a small story about a task you accomplished, and should have a reason for being on your r&eacute;sum&eacute;. They should be concise, direct, relevant, and cover one item. If a point can be split into two points, you should use two points instead of cramming it into one. Yihong (UW CE 2023) has a [guide](https://simple-script-8f5.notion.site/Resume-Guide-debb3905247f489b86034ed7481827f0) on how to word points to convey information.

Points should not have brackets/parantheses, nor semi-colons, nor common initialisms such as "e.g." or "etc." as it breaks the flow.

"etc." is probably one of the worst things to use as it hides information, creates vagueness, raises red flags, etc.

* Action verb - Every point must begin with an action verb. Examples of good action verbs include "developed", "designed", "applied", "modelled", "enhanced", "improved", "documented", "implemented". Use strong action verbs over weaker ones (e.g. not "used", "demonstrated", "leveraged", "built").

* What-How-Why/What-Why-How - Every point should have this model. Sometimes the How can be deferred to another point below.

    * What - What did you do? What action did you take? What was implemented?

    * How - How did you do the action? Did you use any tools?

    * Why - Why did you take the action? What was the result/impact? What was the goal?

* Quantification - If at all possible, quantify the results/impact of your actions.

* Skill demonstration - The action/result/impact in a point should imply the demonstrated skill. The skill should not be explicitly stated nor a point started with one.

* Sentence - Each point should be able to be a valid sentence when prefixed with a pronoun or name.

* Placement - Order your points from most important to least important. However, the first point could be a summary of what you did over the term.

* Length - Points should be able to fit on a single line. Very rarely would a point occupy two lines. Five is right out.

Often I see students leaving the "why" part out of their points. Employers not only want to see what you did and how, but also the reasoning behind the action or the impact/results that occurred because of the action. Otherwise it just seems like you were just told to do something and then went and did it.

## Example 1

*Implemented a matrix solver with the [math] library to generate a correction from identified pixels in images*

* Action verb - "Implemented".
* What-How-Why.
    * What - "Implemented a matrix solver".
    * How - "with the [math] library".
    * Why - "to generate a correction …".
* Quantification - None.
* Skill demonstration.
    * Linear algebra - "matrix".
    * Usage of external tools - "[math] library".
    * Computer vision - "identified pixels in images".
* Sentence.
    *  [Xierumeng] implemented a matrix solver ….
* Placement - N/A.
* Length - Fits on one line in my r&eacute;sum&eacute;.

## Example 2

*Wrote [#] unit tests in log collection bash scripts to validate regex scrubbing of personally identifiable information*

* Action verb - "Wrote". Personally I think it's a bit weak. A better one would be "Created".
* What-How-Why.
    * What - "Wrote [#] unit tests in log collection bash scripts".
    * How - "bash scripts".
    * Why - "to validate regex scrubbing …".
* Quantification - "[#] unit tests".
* Skill demonstration.
    * Unit testing - "unit tests".
    * Bash scripting - "bash scripts".
    * Regular expressions - "regex scrubbing".
* Sentence
    * [Xierumeng] wrote [#] unit tests ….
* Placement - N/A.
* Length - Fits on one line in my r&eacute;sum&eacute;.

Possible improvement: *Validated regex scrubbing of personally identifiable information by writing [#] unit tests in log collection bash scripts*

Possible improvement: *Validated regex scrubbing in log collection by writing [#] unit tests in order to comply with data protection laws*

## Example 3

*Demonstrated knowledge of physics engines by implementing semi-implicit Euler integration math and quaternions for rotation to simulate ship movement*

The action verb is weak, and by explicitly stating the skill, the more interesting part of the point is moved into the passive voice. A better point would be:

*Developed a physics engine using semi-implicit Euler integration math and quaternions for rotation to simulate ship movement*

The action verb is better and the skill demonstrated has been improved (not only knowledge of, but how to implement a physics engine). Plus it's more concise.

## Example 4

*Developed a physics engine and resource manager to simulate ship movement, internal systems*

This is an example where this point should have been broken into twain: Physics engine for ship movement, resource manager for internal systems.

Possible improvement: *Developed a physics engine to simulate ship movement* and *Implemented a resource system to manage internal ship state*

## Example 5

*Queried and updated the message status of events with SQLite to find incomplete events on agent start-up*

Too specific, what is a message status of an event? What does SQLite have to do with it? Events can be incomplete (why?)? What does agent start-up have to do with events? What is this agent, what does it do?

# External Resources

* [Good starting r&eacute;sum&eacute;](https://www.careercup.com/resume) but it could definitely be improved.
* [Engineering Society r&eacute;sum&eacute; resources](https://www.engsoc.uwaterloo.ca/resources/resume-help/).
* [UW Computer Science Club Resources](https://docs.google.com/document/d/1xGLrG-VBXuUpfL5MUuieKtuJyAhJoC7X9pWzg7PRfjo/edit).
* [EngSoc R&eacute;sum&eacute; Bank](https://drive.google.com/drive/folders/1N8uq1BJFV8ik5fyas3_ip7CGS6nOMVIq).
* Go to critique sessions hosted by the Engineering Society and the ECE Society.
* Bug some upper years and alumni.

# Patrons

* Ali Naqvi
