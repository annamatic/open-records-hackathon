Hello! Here's my submission to the Open Records Hackathon February 25, 2017, a short UI/UX analysis and wireframes for the Open Records FOIL Request site. This submission addresses all 3 challenges: 1) Making a Request, 2) User Introduction/Guidance (the emphasis is on the homepage) and 3) Search, View, Track Past Requested Records, but is primarily focused on Challenge 2.

### Table of Contents
* [What I Did](#what-i-did)
* [User Roles](#user-roles)
* [User Stories and Personas](#user-stories-and-personas)
* [User Flows](#user-flows)
* [User Goals](#user-goals)
* [Some Recommended Features](#some-recommended-features)
* [Wireframes Clickthrough PDF](#wireframes-clickthrough-pdf)
* [Wireframes PNGs](#wireframes-pngs)

### What I did:
After analyzing the current site and researching other sites like <a href="https://www.foiamachine.org/" target="_blank">FOIA Machine</a>, <a href="https://foiamapper.com/" target="_blank">FOIA Mapper</a> and <a href="https://www.muckrock.com/" target="_blank">Muckrock</a>, I drafted definitions for two types of user roles (Newbie and Pro), and wrote stories and personas for 4 different users. With the Open Records challenges and these 4 "people" in mind, I envisioned the ideal user flow that would not only simplify the Make a Request process, but also increase the quality of resulting Requests so that both agencies and users could benefit. I then used these flows as a basis for constructing wireframes for key pages of Open Records.

### User Roles:

| Newbie Requester | Pro Requester |  
|------------------|------------------|
| Someone who has has never made a FOIL Request before on- or off-line. The Newbie Requester may lack knowledge of: how city agencies work or interact, which agency would address his concerns, and/or what kinds of information are held in agency records. *Examples of a Newbie Requester: Crime Victim, Neighborhood/Community Advocate (for ex. neighborhood crime watch group), Concerned Parent.* | Someone who has made FOIL records requests before, most probably as a part of his or her job. The Pro Requester may be new to requesting online. *Examples of a Pro Requester: Attorney, Investigative Journalist, Neighborhood or Community Advocate Groups (for ex. Straphangers Campaign, See Through NY)* |

### User Stories and Personas:

| **A. Mr. Chan, 67** | **C. Mr. Smith, 48** |
|------------------|------------------|
| *would like a copy of the police report he made for a broken window on his storefront for his insurance company.* | *is seeking any past disciplinary records for two police officers M.B. and L.K.* | 
| <small>Mr. Chan owns a grocery store in Ridgewood. His window was broken several years ago too, and that time he remembers he filled out some kind of paper form to get copy of the police report for insurance. This time he wants to do it online because "the Internet is faster." He's "not so good at the Internet" so his teenage son is helping him. Together they Googled and came across Open Records.</small> | <small>Mr. Smith has made many FOIL Requests before, but this is his first time using the Open Records site to do it. He is an investigative journalist with 15 years experience. Mr. Smith's FOIL Requests have been mostly to the Police Department and the Office of the Medical Examiner via printed and mailed letters. He keeps a spreadsheet tracking his FOIL requests.</small> |

| **B. Ms. Nelson, 43** | **D. Ms. Oslow, 35** |
|------------------|------------------|
| *would like to see personnel records for a specific teacher at the zoned middle school in her neighborhood.* | *is seeking all 311 complaint records for 3 different buildings managed by XYZ.* | 
| <small>Ms. Nelson is a part of a parents' group in her neighborhood in District 24. Her son will be attending their zoned middle school next year. She has heard 2nd-hand that many other parents had complained about one of the teachers, but the schoool's parent coordinator would not confirm it. She might put her son in the nearby Catholic school next year because of her concerns. Because she works full-time, she has to do her online research at night.</small> | <small>Ms. Oslow is a young attorney with 5 years experience. Sometimes her paralegal assists her with FOIL requests and sometimes she does them herself. In the past, she has emailed her FOIL Requests to the relevant Records Officer, but she thinks that doing it on Open Records might help her keep track of them. She is currently representing a client in a personal injury lawsuit against a building management company.</small> |

[Back to top](#table-of-contents)

### User Flows:
The proposed user flow is based on the typical structure of a technical or customer support website, prioritizing a Knowledge Base (so users can search and browse pertinent information) and View Requests list (that can easily be filtered, sorted and scanned for information). For Newbie users, by prioritizing, anticipating and answering many of their questions on-site, Open Records can "filter out" users who in fact don't need file a FOIA request and "prime" other users with quality information that will help them write better Requests. Pro users can skip these steps and easily proceed to View Requests or Making a Request. After a Request has been made, a confirmation screen gives feedback to the user that their Request has been sent, and provides a tracking number. Notifications sent by Open Records can be used to alert users who have made Requests when information in the Request has been updated. It is possible to introduce a login/password at this point for users to view more secure information related to their Requests, but this part of the flow has not been mapped for this project.

![Open Records User Flow](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords-Drawio-UserFlows.png)
[Open the User Flow Diagram in Draw.io](https://www.draw.io/?lightbox=1&target=blank&highlight=0000ff&edit=_blank&layers=1&title=OpenRecords-Drawio-UserFlows.xml#Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fannamatic%2Fopen-records-hackathon%2Fmaster%2FOpenRecords-Drawio-UserFlows.xml)

Note: While it could be technically possible to make numerous different Make a Request forms, each one with fields specific to the needs of each agency (ex. NYPD: Precinct #, Offense, Victim, Date) helping Newbies immensely, this would probably introduce too much friction into the form submission process for Pro users, and would be difficult to maintain and update should agencies update their processes. For this reason, I propose providing basic informational articles and links to resources in an easily searchable Knowledge Base, to allow users to inform themselves.

[Back to top](#table-of-contents)

### User Goals:

**On the Homepage, I can...**
- see that this is a website to submit Requests for documents from the city government.
- search for information about how to submit a Request.
- see a link to view current and past Requests.
- see that I can make my own Request.

**On the Search Results and in the Knowledge Base, I can...**
- find information about which city agency supply the records that I’m looking for.
- tell that not all requests are successful and that this has something to do with what information I put in the request.
- see that there is advice available about what information to include in my specific request to improve my chances of success.
- see what other people have searched for.

**On the View Results page, I can...**
- track an existing Request by FOIL ID#.
- determine if one of these listed Requests is the same as the Request I want to make, and if so whether the files are available here.
- determine if one of these listed Requests is similar to the Request I want to make, and if so what information I can learn from it to improve my chances of making a successful Request.

**On the Make a Request page, I can...**
- tell how many steps there are in this form.
- understand what information is required for each step, and why.
- see which steps might require information that I can glean from the Knowledge Base.
- tell whether information from each step will be public or private.
- understand how far along in the form submission process I am.
- tell when I am done, and confirm that the Request has been delivered.

[Back to top](#table-of-contents)

### Some recommended features
| Homepage | Search Results & Knowledgbase | View Results | Make a Request |
|-----------|-------|-------|-------|
| Priorite a search field to encourage Newbie users to find information about their Request before beginning the Make a Request Process | Create and organize content about city agencies, their Subject Matter Lists, and recommendations about the FOIL Request submission processes for each. Compile a list of external links to those agency FOIL information pages. Compile a list of city record requests that are commonly mistaken for FOIL Requests and redirect users to those relevant websites | Standardize the visual communication for "Open" vs. "Closed" status. Standardize the visual communication for outcomes, such as "Open: Waiting", "Open: Processing", "Closed: Completed" and "Closed: Denied." | Use progressive disclosure to let user focus on 1 step at a time, and allow user to skip ahead in the form. Change label from Title to Summary and provide guidance on how to fill out this field, so as to improve scannability of View Results page |
| ![Prioritized search](https://github.com/annamatic/open-records-hackathon/blob/master/images/BigSearchField.png) | ![Organized content](https://github.com/annamatic/open-records-hackathon/blob/master/images/Knowledgebase.png) | ![Open: Waiting](https://github.com/annamatic/open-records-hackathon/blob/master/images/StatusOpenOutcomeWaiting.png) ![Open: Processing](https://github.com/annamatic/open-records-hackathon/blob/master/images/StatusOpenOutcomeProcessing.png) ![Open: Processing](https://github.com/annamatic/open-records-hackathon/blob/master/images/StatusOpenOutcomeProcessing2.png) ![Closed: Completed](https://github.com/annamatic/open-records-hackathon/blob/master/images/StatusClosedOutcomeCompleted.png) ![Closed: Completed](https://github.com/annamatic/open-records-hackathon/blob/master/images/StatusClosedOutcomeCompleted2.png) ![Closed: Denied](https://github.com/annamatic/open-records-hackathon/blob/master/images/StatusClosedOutcomeDenied.png) ![Closed: Denied](https://github.com/annamatic/open-records-hackathon/blob/master/images/StatusClosedOutcomeDenied2.png) | ![Organized content](https://github.com/annamatic/open-records-hackathon/blob/master/images/Summary.png) |

[Back to top](#table-of-contents)

### Wireframes Clickthrough PDF
[Download the PDF here and open in Acrobat Reader. Yellow areas are clickable.](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords_Clickthrough_Annamatic.pdf)

### Wireframes PNGs:
| Homepage | Search Results & Knowledgbase | View Results | Make a Request |
|-----------|-------|-------|-------|
| ![Open Records Homepage](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords-Drawio-Homepage-Annamatic.png) <a href="https://www.draw.io/?lightbox=1&target=blank&highlight=0000ff&edit=_blank&layers=1&title=OpenRecords-Drawio-Homepage-Annamatic.html#Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fannamatic%2Fopen-records-hackathon%2Fmaster%2FOpenRecords-Drawio-Homepage-Annamatic.html" target="_blank">Open the Homepage wireframe in Draw.io</a> | ![Open Records Knowledgbase](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords-Drawio-Knowledgebase-Annamatic.png) | ![Open Records View Requests](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords-Drawio-ViewRequests-Annamatic.png) | ![Open Records Make Request 1](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords-Drawio-MakeaRequest1.png) |
| | ![Open Records Search Results](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords-Drawio-SearchResults-Annamatic.png) | ![Open Records View Requests Agency Closed](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords-Drawio-ViewRequests2-Annamatic.png) | ![Open Records Make Request 2](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords-Drawio-MakeaRequest2.png) |
| | | | ![Open Records Make Request 3](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords-Drawio-MakeaRequest3.png) |
| | | | ![Open Records Make Request 4](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords-Drawio-MakeaRequest4.png) |
| | | | ![Open Records Make Request 5](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords-Drawio-MakeaRequest5.png) |
| | | | ![Open Records Make Request 6](https://github.com/annamatic/open-records-hackathon/blob/master/images/OpenRecords-Drawio-MakeaRequest6.png) |

[Back to top](#table-of-contents)
