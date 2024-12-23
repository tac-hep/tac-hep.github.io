---
permalink: /docs/new-trainee.html
layout: default
title: Information to add or update trainee webpages
pagetype: doc
---

### Adding a New Trainee Page to TAC-HEP

All TAC-HEP Trainees should create and then maintain a page

#### TAC-HEP website
In order to add your information, we request you to please supply a photo ( First_Name-Last_Name.jpg or .png - 320x240 pixels) and a paragraph summarizing your project’s goals.
You should submit a pull request with the photo, a markdown file with the summary information above, and your proposal to [this](https://github.com/tac-hep/tac-hep.github.io) repo.

* Add a photo named `First-Last.jpg` or `.png` to the [assets/images/trainees folder](https://github.com/tac-hep/tac-hep.github.io/tree/main/assets/images/trainees). It should be 320x240 pixels and in general should be 150kB or less.
* Add a "`<your github username>.md`" file to the [trainees folder in the website repository](https://github.com/tac-hep/tac-hep.github.io/tree/main/_trainees). See the example below.

The markdown file has a part a the top (delimited by "---") called the frontmatter. This is described below. In the main body of the markdown file you should have the following sections:

  * Biography and Interests - Biographical information such as where you were an undergraduate and when you started graduate school, plus information about your interests (physics, analysis, software and computing)
  * Project - this should be a description of the project you are working on as a TAC-HEP trainee
  * Recent Accomplishments - this may be blank ath beginning, but should eventually grow to a bullet point list of things you accomplished on your project (including links to related presentations, repositories in github, etc.)
  * Mentors - this should be a bullet point list of your mentors (name and institution). It should include both someone at your university and someone at one of the DOE labs.
  * Traineeship dates - date at which your traineeship began and is expected to end


### Frontmatter

```yml
layout: collaborator
shortname: <your GitHub user id>
name: <Your Name>
active: True
dates:
  start: <start date>
  end: <end date>
photo: /assets/images/trainees/<First name>-<Last name>.jpg
institution: <Your institution>
e-mail: <Your email>
networks:
  - <which of [cms|atlas|vro|dune|etc] is appropriate>
github-username: <Your git-hub username>
presentations:
  - title: "<Presentation Title"
    date: "Presentation Date"
    url: <Presentation materials link>
    meeting: <Meeting name>
    meetingurl: <Meeting url - indico link, etc.>
    recordingurl: <Recording url> (Optional)
    focus-area: <Focus Area - ia,ssl,ssc,doma,as,osglhc>
---
```

### Notes

  * In the markdown file you create, ensure you set the “active” attribute to True – (i.e.  active: True).  Otherwise, your entry will not appear on our Trainees page.
  * The date format for start and end dates should be -- YYYY-MM-DD -- i.e. 2021-12-31

### Presentations

When you start, you just need to include the "presentations:" line. The subsequent indented lines above can be omitted. They are included above so that you can see the structure when you have a presentation to add.

The meaning of the fields is the following:

  * title - the title of the talk: you made need to place it in double quotes, if certain characters like a colon (":") are included in the title
  * date - the date on which the presentation was made, in the numeric format "YYYY-MM-DD"
  * url - this should be a direct URL to the presentation or page containing the presentation. For Indico, link to the contribution, not the PDF or other links.
  * meeting - the name of the meeting
  * meetingurl - the URL for the meeting in which the presentation was made
  * focus-area - optionally list the relevant focus area for this presentation, using its short name, i.e. one of [ia,ssl,ssc,doma,as,osglhc]. Must be a yaml list if more than one is present.


