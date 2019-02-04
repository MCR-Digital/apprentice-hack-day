<!--- ORGANISER THINGS TO CONSIDER 
- Which technical competencies, behaviours and knowledge module topics does the bootcamp cover/meet
- Structuring retros so that they can inform thinking for individual's personal learning records (off the job training record tab in their learning logs)
- Introducing some sort of test or quiz on basic concept learning points from the bootcamp to validate that they have taken stuff in, and provide organisation mentors with results to help them focus follow ups
--->

## Competencies, Behaviours and Knowledge units

* TC1 logic, 
* TC14 Applying Maths, 
* TC3 Data, 
* TC2 UIs, 
* TC11 Continuous Integration/Version Control, 
* USABs: Complexity, Influence, Autonomy

## Resources 

* Laptops
* Internet access
* Post-its
* Pens / sharpies
* Whiteboard / paper
* Presentation Screen

## Mentors / Languages
 
One Mentor per Hack Team (five teams total).

Mentors will be available via Slack in the run up to the event to offer advice/guidance in planning.

Mentors will support their team on the day of the Hack.

## Prep-work for apprentices

Plan an idea for the Hack - based on the information in the brief. Come ready to hit the ground running on the day, but do not wirte any code beforehand. 

https://github.com/MCR-Digital/apprentice-hack-day/blob/master/docs/Hack%20Challenge%202019.docx

### Follow-on tasks

Organisation mentors should look to exercise the knowledge we’ve covered in the boot camp. Below are suggestions for tasks that would do this, but please use your own judgement to work out what to do. There is no need for anything to be returned to MD or the presenters—it’s just a learning exercise.

* Review what was achieved on the day and look at ideas for enhancements / how it could be improved with more time. 

## Further reading / learning resources

<!--- For end of boot camp: Signposting for apprentices self study, further learning, online resources, practice etc. --->

* TBC
 
## Brief

###Context

A key part of a software engineers’ role is to process data into information, to turn data points into a format that businesses can use to make informed decisions on future strategy and where to focus their efforts. In 2010 the UK Government set up a website to help people find data published into the public domain. In 2018 they introduced the “Find open data” service to make it easier to find data published by central government, local authorities and public bodies, and provided links to download the data. 

###The Challenge

Using data from the UK’s Open Data Initiative (https://data.gov.uk/), process a datafile of your choice to create an answer to a question that you devise. 
 
###Guidance for Attendees
* Review the types of data available on https://data.gov.uk/
* Think about the answers that you can create for the data that would be interesting (or fun) to you, your community, or your employer


## Exercises

* Hack Participation
* Presentation of POC
<!--- 
* Setting up CI?
* Branching and creating Pull Requests?
* Resolving, tracing, telneting?
---> 

# Boot Camp Summary


## Planned

9am - 12pm: Hack Coding\
12pm - 1pm: Lunch\
1pm - 4pm: Hack Coding\
4pm - 5pm: Presentations and Voting


# Briefing for organisation mentors

* N/A

# Working with the slides

The slides are stored as Markdown files in `docs/_posts` and are presented using a combination of Jekyll and [reveal.js](https://revealjs.com/#/). A [remote Jekyll theme](https://github.com/autotraderuk/jekyll-revealjs) is used to help make changes to the Jekyll code centrally.

The easiest way to preview your changes locally is to use docker to run Jekyll. To do this, [install docker](https://www.docker.com/get-started) if you haven’t already and run `docker-compose up` from the root of this project in a terminal. Your changes will be visible on <http://localhost:4000/>. Any changes you make to the slides will be reflected in your browser—there’s no need to restart docker. You can hit `ctrl-c` to stop the process.

Once you push your changes the slides will be published using GitHub Pages automatically (see the link at the top of the repository).
