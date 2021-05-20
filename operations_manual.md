# Operations Manual - SPSCAR group

1. [About](#About)
2. [Contacts](#Contacts)  
3. [Meetings](#Meetings)
    1. [Announcment](#Announcment)
    2. [Invitation](#Invitation)
    3. [At meeting](#At-meeting)
    4. [After meeting](#After-meeting)
    5. [New meeting](#New-meeting)
    6. [Circulate minutes](#Circulate-minutes)
4. [New member welcoming](#New-member-welcoming)
5. [shinyapps.io](#shinyapps.io)
    1. [Deploying apps](#Deploying-apps)


## About

This manual contains all the necessary information to run the **Scotland public sector communicating analysis with R** group meetings and the [scotland.shinyapps.io](https://www.google.com/url?q=https%3A%2F%2Fwww.shinyapps.io%2Fadmin%2F%23%2Fapplications%2Fall&sa=D&sntz=1&usg=AFQjCNHsH-iEy9lIP7jY7yE5eJ2pSgEXCw) account.

**No passwords or login details should be included here.**

The group was set up in December 2017 by three people representing three different organisations (National Records of Scotland, National Services Scotland and Scottish Government). Since then we have held monthly meetings attended now by around 20 people and more organisations have joined in (NHS Health Scotland, Improvement service and Scottish Parliament Information Centre).
 
Meetings have been useful to discuss common issues and to help each other in an informal way and some guidelines have been created to ease the learning process for new users. The group is now considering to move to meetings every other month and to a more structured type of meeting where someone will present and lead on a specific topic discussion.
 
Some of the challenges this group is facing are:
Each organisation has different access to R versions and updates and has different restrictions to access the shinyapps.io server.
The expertise within each organisation is limited (although this group helps it to be galvanised). It might be a good idea to procure some advanced training for group members.

## Contacts
Send emails to:
* Joseph Adams - from National Records of Scotland and the Scottish Government  
* Jaime Villacampa - from Public Health Scotland  
* Nick Cassidy - from Improvement Service  
* Damon Davies - from the Scottish Parliament  
* Gregor Welsh - from the Scottish Fire and Rescue Service  
* Joshua Bird - from the Scottish Funding Council  
* Rachael Fairley  - from Registers of Scotland  
* May Shirkhorshidi - from Scottish Natural Heritage  
* Laura Allen - From UK Department International Development  
* Faith Chung - from Food Standards Scotland  
* Nicola Potts - from sportscotland  
* Graeme West - from Audit Scotland  

Copy this into the to: email field:  
joseph.adams@nrscotland.gov.uk; jaime.villacampa@phs.scot; nicholas.cassidy@improvementservice.org.uk; Damon.Davies@parliament.scot; Gregor.Welsh@firescotland.gov.uk; jbird@sfc.ac.uk; Rachael.Fairley@ros.gov.uk; May.Shirkhorshidi@nature.scot; L-Allen@dfid.gov.uk; Faith.Chung@fss.scot; Nicola.Potts@sportscotland.org.uk; gwest@audit-scotland.gov.uk

Then they would forward emails on to their R users groups.
* Joseph Adams to RUserGroupDL@gov.scot
 
## Meeting
### Announcment
1. Two/four weeks before the meeting, send email with meeting announcement. This also acts as a reminder.

**Announcement email**
Subject: `Scottish public sector Communication Analysis with R - July meeting`
```
Hi all,

This is a reminder of our next meeting to be held on **25th July from 1-3 pm** on MS Teams.

Please fill in this form if you are interested in attending: https://goo.gl/forms/thYwiWXRgvsLBb2D3. 

Please see in the link below minutes from the last meeting and draft agenda for the next meeting: https://docs.google.com/document/d/1-hf0jTUxqqQOXeSXhp0eH4bxgt5CDo6-wvTVNQ2aaUo

We would like this group to be run by its members, which relies on people getting interested and involved – to that end, if anyone wants to present their app to the group or discuss any topic, please get in touch. It would be much appreciated.

Thanks,
**NAME**
```
### Invitation

1. Create a meeting in Outlook calendar
2. Send invites to people who signed up using the form: https://docs.google.com/forms/d/1bReJpvTL0UKbXklnQUavUxDcfcDqW47151z4qvfBXuQ/edit I send meetings invites as people sign up (or as soon as I realise someone else has signed up). Not the most effective way. Ideally, I would like to do this just once, but I worried that if people don't see the meeting in their calendars, they might forget. I wish we could automate this but I don't know how to.
3. If meeting is held at Meridian Court (Glasgow) a list of attendees has to be provided prior to the meeting. It is probably better to do this the day before as we expect last minute registrations
4. Ask speakers to send links/slides or any other material they would like to use in advance.

**Meeting invitation**

Subject: `Scottish Public Sector Communicating Analysis with R - **MONTH** meeting invitation`

```
Hi all,
 
You are receiving this email because you expressed your interest in attending the Scottish public sector R/Shiny group meetings.
 
Here is a link to the previous meeting minutes, and agenda for the next meeting:
https://docs.google.com/document/d/1-hf0jTUxqqQOXeSXhp0eH4bxgt5CDo6-wvTVNQ2aaUo

We are still updating the agenda, so let us know if you would like to present an app or would like anything to be added to the agenda.

If you are presenting, please send any links, slides or any other material you would like to use to the organiser in advance.

Thanks,
**NAME**
```

### At meeting

* Arrive 15 minutes earlier to set everything up.
* Thank people for attending the meeting at the beginning and at the end of the meeting.
* Start meeting with a round of introductions (only if not online). 
* Ask attendees about date for next meeting.

### After meeting

1. Update minutes: https://docs.google.com/forms/d/1bReJpvTL0UKbXklnQUavUxDcfcDqW47151z4qvfBXuQ/edit
2. When required add files to Google drive folder: https://drive.google.com/drive/folders/1MhxQnZVp5FN__N0zIH2GsPMbVRKC4i6T
3. Naming convention for new files. So far I've been using the fields below separated by space hyphen space (' - ')
4.   
    | Type of document | Meeting date | Author/source | Title        |
    | :-------------   | :----------: | :-----------: | -----------: |
    |  Slides          | YYY-MM-DD    | Name Surname  | _Title_      |
    |  Code example    |              | Organisation  |              |
    |  Guidance        |              |               |              |
5. Within a week after the meeting, email attendees with link to minutes for them to add their notes (see email template below)
6. Set up next meeting

After-meeting email to attendees (within a week after the meeting)

Subject: `Scottish public sector R/Shiny meeting - May meeting - MINUTES`
```
Hi all,

Thanks for attending last meeting. Your presence and input is what makes this whole thing worthwhile.

I’ve updated the minutes with my notes: https://docs.google.com/document/d/1-hf0jTUxqqQOXeSXhp0eH4bxgt5CDo6-wvTVNQ2aaUo

Some of you were meant to send over links and other content to be added to the minutes. If you give me your gmail account, I can give you edit permissions or you can send it to me and I’ll add it. Happy with both options.

Once you get back you me, I’ll share these minutes more widely.

Thanks,
**NAME**
```

### New meeting

1. Set up a meeting every three months. Currently:
    * Edinburgh: April, October
    * Glasgow: January, July
2. Consult with potential attendees to find the most suitable date
3. Book room
4. Update attendance form with details for next meeting: https://docs.google.com/forms/d/1bReJpvTL0UKbXklnQUavUxDcfcDqW47151z4qvfBXuQ/edit
5. Venues
    * New Register House, 3 W Register St, Edinburgh EH1 3YT. Room: The Dome. It can hold up to 36 people. This is a public room and doesn't need a list of attendees to be sent prior to meetings.
    * Meridian Court, 5 Cadogan St, Glasgow G2 6QQ. Depending on the room, it can hold up to 20 people. A list of attendees will need to be sent prior to meetings.
6. Remove responses from form before sharing it 
7. Update agenda: https://drive.google.com/open?id=1-hf0jTUxqqQOXeSXhp0eH4bxgt5CDo6-wvTVNQ2aaUo


### Circulate minutes

1. 1-2 weeks after the meeting, and once next meeting has been set up, email everyone to circulate minutes and next meeting details (see email template below)

**After-meeting email to everyone** (1-2 weeks after the meeting)

Subject: `Scottish public sector R/Shiny meeting - May meeting - MINUTES`
```
Hi all,

See below link to minutes from last meeting and draft agenda for next meeting:
https://docs.google.com/document/d/1-hf0jTUxqqQOXeSXhp0eH4bxgt5CDo6-wvTVNQ2aaUo

Next meeting will be on **DATE & TIME** on MS Teams. Please fill in this form if you are interested in attending: https://goo.gl/forms/thYwiWXRgvsLBb2D3

We would like this group to be run by its members, which relies on people getting interested and involved – to that end, if you want to present your app to the group or discuss any topic, please get in touch. It would be much appreciated.

Thanks,
**NAME**
```

## New member welcoming
Is there anything people should know when they join our meetings?

## shinyapps.io
This is the list of people who have login details and password for scotland.shinyapps.io

**SG**
* Jaye Ware (jaye.ware@gov.scot)
* Euan Shields (euan.shields@gov.scot)
* Jeremy Darot (jeremy.darot@gov.scot)

**NRS**
* Victoria Avila (victoria.avila@gov.scot)
* Joseph Adams (joseph.adams@gov.scot)

**NHS**
* Jaime Villacampa (jaime.villacampa@phs.scot)
* Russell McCreath (russell.mccreath@phs.scot)
 
There will be only one pair token/secret at a time that will be changed every 6 months.  
* Last change: December 2018  
* Next change: June 2019


### Deploying
When someone gets in touch about deploying an app to scotland.shinyapps.io:  
1. Send them link to technical guidelines: https://docs.google.com/document/d/1krCnJW1DwvI5FvE0BHsqKTp5sV_chSSfiYSOUiFTThw
2. Check app has been added to apps catalogue: https://goo.gl/forms/ixgmEZ1MTq4cZPh53
3. Send them token and secret as attachments in two separate emails. Remind them not to share token/secret with anyone.

**Email template**

```
Hi,  

I’ll send you the secret and token as attachments in two separate emails shortly. Please remember not to share these with anyone.  

Thanks,  
NAME 
```


**NOTE:** https://www.gov.scot/publications/govscot-domains/#namings-committee-and-jisc-services-ltd  
Link to SG naming policy for gov.scot domains. Read and see how much we can harmonise. 
