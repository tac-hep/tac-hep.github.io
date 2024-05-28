---
permalink: /docs/new-trainee.html
layout: default
title: Information to add or update fellows
pagetype: doc
---

### Adding a New Fellow Page to TAC-HEP

#### TAC-HEP website
In order to add your information, we request you to please supply a photo ( First_Name-Last_Name.jpg or .png - 320x240 pixels) and a paragraph summarizing your project’s goals.
You should submit a pull request with the photo, a markdown file with the summary information above, and your proposal to [this](https://github.com/tac-hep/tac-hep.github.io) repo.

* Add a photo named `First-Last.jpg` or `.png` to the [assets/images/team folder](https://github.com/tac-hep/tac-hep.github.io/tree/main/assets/images/trainees). It should be 320x240 pixels and in general should be 150kB or less.
* Add a "`<your github username>.md`" file to the [fellows folder in the website repository](https://github.com/tac-hep/tac-hep.github.io/tree/main/_trainees). See the example below.

*Please Note*:  In the markdown file you create, ensure you set the “active” attribute to True – (i.e.  active: True).  Otherwise, your entry will not appear on our Fellows page.

Be sure to include your project summary in the project_goal field.

You can leave the “presentations” and “current_status” fields blank for now.  (Make sure to include the fields)

```yml
---
layout: fellow
pagetype: fellow
shortname: <your GitHub user id>
permalink: /fellows/<your GitHub user id>.html
fellow-name: <Your Name>
title: <Your Name> - TAC-HEP Fellow
active: True
dates:
  start: <start date>
  end: <end date>
photo: /assets/images/team/<First name>-<Last name>.jpg
institution: <Your institution>
e-mail: <Your email>
focus-area: <Focus Area - ia,ssl,ssc,doma,as,osglhc>
project_title: <Project title>
project_goal: >
    Short description of your project
mentors:
  - <Mentor Name (<Mentor Institution>)
proposal: /assets/pdf/fellows-2022/<find-your-file>
presentations:
  - title: "<Presentation Title"
    date: "Presentation Date"
    url: <Presentation materials link>
    meeting: <Meeting name>
    meetingurl: <Meeting url - indico link, etc.>
    recordingurl: <Recording url> (Optional)
    focus-area: <Focus Area - ia,ssl,ssc,doma,as,osglhc>
current_status: >
  A placeholder for status updates
github-username: <Your git-hub username>
---
```

### Dates
Date format for start and end dates should be -- YYYY-MM-DD -- i.e. 2021-12-31

### Presentations

The meaning of the fields is the following:

  * title - the title of the talk: you made need to place it in double quotes, if certain characters like a colon (":") are included in the title
  * date - the date on which the presentation was made, in the numeric format "YYYY-MM-DD"
  * url - this should be a direct URL to the presentation or page containing the presentation. For Indico, link to the contribution, not the PDF or other links.
  * meeting - the name of the meeting
  * meetingurl - the URL for the meeting in which the presentation was made
  * focus-area - optionally list the relevant focus area for this presentation, using its short name, i.e. one of [ia,ssl,ssc,doma,as,osglhc]. Must be a yaml list if more than one is present.


