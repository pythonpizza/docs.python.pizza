# 🍕🍕🍕 Python Pizza Recipe 🍕🍕🍕 

# Introduction

This manual provides guidance on organizing Python Pizza, sharing what worked for us and offering tips on how you might approach it. However, you don’t need to follow our steps exactly—feel free to be creative\!

Since this documentation is open-source, we welcome all contributions or improvements.

# Ingredients

Before announcing your event, there are a few key things to figure out:

* Build a team  
* Secure the pizza  
* Decide if your event will be onsite only or onsite with streaming  
* Ensure you have promised funds to cover the minimum costs  
* Choose a venue  
* Set a date  
* Set up a website

There is a Github Organisation and a Discord server.

If you need an invitation, reach out to any of the current or previous organizers.

## Build a Team

Build a team of ideally 3-5 people. Don’t do it alone. 

## Secure the Pizza (and beverages)

Pizza is the second most important thing in the Python Pizza event.

Make sure to:

* Choose a good pizza place to make and deliver your pizza  
* Include vegetarian, vegan and gluten free options  
* Have enough pizza for everyone

If you’re organizing a whole-day event, keep in mind you will also need tea, coffee, water and other beverages.  
You probably also want some snacks for coffee breaks.

## Set a Date

Make sure to not collide with any other nearby events. Check python.org events calendar [https://www.python.org/events/](https://www.python.org/events/) and python organizers calendar: [https://github.com/python-organizers/conferences](https://github.com/python-organizers/conferences) also local meetups, etc.

Python Pizza works very well as a 1-day Saturday event.  
Another good option is to organize a half-a-day evening event.

## Funding Your Event

### Sponsorship

#### Outreach

The easiest way to secure funding is by reaching out to sponsors of local Python events, like PyCon, PyData, meetups, or similar gatherings.

Here are some ideas for what you can offer sponsors in return:

* Display their logo on the event website.  
* Place their rollup banners at the venue.  
* Feature their logo on intermission slides.  
* Mention them on LinkedIn, Mastodon, and Twitter.  
* Acknowledge them during the opening and closing sessions.  
* Provide free tickets to the event.

#### Contracts

Every situation is different. Please consult with local lawyers and relevant organizations.  
In general we recommend having a local Python NGO to handle all the paperwork with sponsors and venues.  
More details in the Legal section below.

### Grants

In addition to commercial sponsors, consider applying for grants from the EuroPython Society (EPS) or the Python Software Foundation (PSF). For the PSF, you'll need to have your event schedule finalized, and should apply at least 8 weeks in advance.

### Tickets

When planning a Python Pizza event, you'll need to figure out if it will be free or paid.

You don't have to worry about the ticket price just yet, but it's important to know which legal entity will be responsible for selling the tickets.

# Venue

When choosing a venue, make sure it:

* Can comfortably accommodate all attendees
* Has a projector for presentations
* Offers suitable conditions for streaming and recording  
* There is enough space to comfortably eat the Pizza (and other catering)

There are no restrictions on the type of venue—you can choose a company office, a co-working space, or a local university, whatever works best for your event.

# Email

You will need some way to communicate with the participants, sponsors, etc.  
One of the ways to do it is to create a shared account on gmail.

For example for Prague Python Pizza we used [praguepythonpizza@gmail.com](mailto:praguepythonpizza@gmail.com). This account also owned all the documents on google drive.

In the future we would like to use official @python.pizza emails, however there is no python.pizza Google Workspace organization (yet).

# Website

## Domain

All python pizza websites use the python.pizza domain with this format: **https://\<city\>.python.pizza**  
To have your city added, simply ask in the **\#random** channel in Discord.

## Repository

Next, you’ll need to create a repository. All Python Pizza source code is hosted on GitHub under the "Python Pizza" organization. 

[https://github.com/pythonpizza](https://github.com/pythonpizza)

To be added to the organization, request access in the same \#random channel.

You can start by using one of the templates or duplicating one of the previous websites.  
All previous websites are written in React, however there is also a jinja-based version in development.

## Main python.pizza Page

Finally, update the main Python Pizza page with information about your event.  
You can find an example of a merge request (MR) here: [https://github.com/pythonpizza/python.pizza/pull/842/files](https://github.com/pythonpizza/python.pizza/pull/842/files) 

Make sure any photos you use are copyright-free. Unsplash [https://unsplash.com/](https://unsplash.com/) is a good source for such images.

# Project Management and Planning

We've created a template folder with various templates, so you don’t reinvent the wheel. The folder is read-only, so please duplicate it and use whatever you need.

Link: [https://drive.google.com/drive/folders/1c4U3Wn0A6dbhFZND8L54-BcKLDCo3Z-Z](https://drive.google.com/drive/folders/1c4U3Wn0A6dbhFZND8L54-BcKLDCo3Z-Z) 

## Task Visualization

We recommend visualizing all upcoming tasks to ensure you have enough time for everything. To help with this, we’ve prepared a template spreadsheet that you can duplicate and customize to fit your needs. It’s in the folder under the name “plan template”. 

## Timeline Planning

For your timeline, ensure that your Call for Proposals (CfP) is open long enough. If you’re applying for funds from the PSF, your event schedule should be finalized at least 2 months in advance. The template includes a "timeline" tab where you can adjust the dates, and the timeline will automatically update.

## Budgeting

**First rule of budget: Make sure that your income is higher than your expenses. 🙂**

Your biggest expenses will likely include:

* Venue rental  
* Catering  
* Accommodation and travel for organizers  
* Accommodation and travel for keynote speakers  
* Merchandise, stickers, or other marketing materials  
* Pretix and Stripe fees

Most of your income will likely come from sponsors, with some additional funds from ticket sales.  
Sponsors can also donate venue space, catering, etc.

#### Prague Python Pizza 2024

To give you some context about the budget: the total income of Prague Python Pizza 2024 was \~90K CZK, and total expenses were \~75K.

## Legal

### Requirements by Country

#### Czech Republic:

In the Czech Republic, Pyvec is your friend. For details please see: [https://docs.pyvec.org/operations/runbooks.html#jak-si-nechat-neco-proplatit](https://docs.pyvec.org/operations/runbooks.html#jak-si-nechat-neco-proplatit) 

# Code of Conduct

Code of Conduct is mandatory for all Python Pizza event   
You can reuse Prague Python Pizza CoC: [https://prague.python.pizza/\#coc](https://prague.python.pizza/\#coc) 

# Program Development

Python Pizza events usually consist of 10 minute long talks with \~2 minute breaks in between. The talks are grouped in 2-3 blocks, with longer breaks between them.

## Keynote Speakers

Keynote talks are typically longer than other sessions. For keynote speakers coming from abroad, it's common to offer reimbursement for travel and accommodation if you have the budget.

Announcing Keynote Speakers early can help your CFP and ticket sales.

## Calls for Proposals (CfP)

We recommend using a Google Form to manage submissions—it's easy to set up and track. After duplicating the form template, make sure to link it to your own spreadsheet.

CFP is a very deadline-driven activity, so expect most of the proposals to show up last minute.  
Make sure to advertise the deadlines.

Once the CfP closes, go to the "Programme Voting" tab in the “plan template” spreadsheet. Copy all the data and have each committee member (in our case, all the organizers) rate the talks using the following scale:

* \+10 \= Must see   
* \+5   \= Like to see  
* \+2   \= Maybe  
* \-1    \= Nope

### Prague Python Pizza 2024:

The Call for Proposals ran for 47 days, with a 45% acceptance rate. Most proposals arrived on the last day.  
The CFP Closed roughly two months before the event.  
The programme was announced shortly after the CFP finished, around the same time we opened the ticket sales.

## Speaker Management

### Accepted Talks Tracking

Once you've selected the talks, copy them to the "Accepted Talks" tab. This tab will serve as your central hub for all the necessary speaker information. At this point, you'll need to send out two emails:

* Accepted Talk: Use the template under the name “For accepted”  
* Rejected Talk: Use the template under the name “For rejected”

Both templates are in the “Speaker Communication” document: [https://docs.google.com/document/d/1hlo_L0Ty1eVrfo6VhrGV-upqTu8Xjh4-Lk6Qe_9XPkA](https://docs.google.com/document/d/1hlo_L0Ty1eVrfo6VhrGV-upqTu8Xjh4-Lk6Qe_9XPkA). 

Columns Legend:

* Sent Confirmation Email: Track who has received a confirmation email and who hasn't
* Confirmed Participation: Update this field once speakers confirm their participation  
* Sent Photo: Note whether a speaker has provided a photo; otherwise, use a pizza placeholder  
* Sent Voucher: Keep track of which speakers have received their vouchers  
* Claimed Ticket: Monitor who has purchased their ticket 
* Live Demo: Protip: Schedule live demos after coffee breaks to reduce the risk of technical issues

### Backup Speakers

After a few days, you'll start receiving confirmations. 

Have a few backup speakers, as cancellations can happen at the last minute.   
For backup speakers, you can use the template under the name “For waitlist”. 

### Master of Ceremonies (MC)

You'll need an MC to moderate the event. Instruct the MC to stop speakers if they go over their allotted 10 minutes. While we didn’t have any issues with speakers running over time, it's good to be prepared. For speakers with demos, arrange for them to test their setups during lunch or coffee breaks.

We also asked all speakers to send us their slides in advance. To streamline the process, we used a single computer for all presentations, ensuring smooth transitions. Allow two minutes between each speaker for setup.

### Publishing and updating the Programme

You can (manually) export the data to the JSON schema supported by the website. See this PR for inspiration: [https://github.com/pythonpizza/prague.python.pizza/pull/12/files](https://github.com/pythonpizza/prague.python.pizza/pull/12/files) 

# Media Management

## Emails

Python Pizza doesn’t have a centralized newsletter. For the Prague Python Pizza edition 2024, we collected emails from those interested in updates. 

We sent them two reminders:

1. Schedule announcement & Tickets Sale  
2. Last few tickets available 

If you'd like to send reminders, you'll need to collect the emails again and ensure users accept the privacy policy.

## Social Media

We use three social media platforms for all communication: 

1. Twitter/X: [https://x.com/pythonpizzaconf](https://x.com/pythonpizzaconf)  
2. LinkedIn: [https://www.linkedin.com/company/python-pizza](https://www.linkedin.com/company/python-pizza)  
3. Mastodon: [https://fosstodon.org/@pythonpizza/](https://fosstodon.org/@pythonpizza/)

In order to receive access to these accounts, ask on Discord. 

## Post / Campaign Templates

For social media posts we have templates in Canva. In order to use it, please duplicate the design and fill in templates as needed. 

Link to templates: [https://www.canva.com/design/DAGPavfLrtQ/fZPjwfF7Bi7UCh-6OFyStw/edit](https://www.canva.com/design/DAGPavfLrtQ/fZPjwfF7Bi7UCh-6OFyStw/edit) 

## Media Timeline

In the template spreadsheet, there's a "media" tab with a table that includes example announcements. You can choose the platform, set start and end dates, assign a responsible person, and check the "done" box once it's published.

# Tickets and Attendee Management

## Ticket Setup

### Czech Republic:

For ticket sales, we used Pretix through the Pyvec account.

#### Refund Policies

We did issue a few refunds, but keep in mind that refunds sometimes come with additional fees.

### Attendee Communication

Before the event, it’s important to send attendees essential information. The template that we usd in named “Participant email for on-site participants”: [https://docs.google.com/document/d/1hlo_L0Ty1eVrfo6VhrGV-upqTu8Xjh4-Lk6Qe_9XPkA](https://docs.google.com/document/d/1hlo_L0Ty1eVrfo6VhrGV-upqTu8Xjh4-Lk6Qe_9XPkA) 

## Streaming and Online Interaction

### Setting Up Discord

If you plan to stream the event, you'll need a platform for participants to communicate with you.  
Setting up a Discord server is a straightforward option. There’s already a participant server for some past Python Pizza events, so you’ll just need to add a new channel for your event.

### Setting up streaming

Streaming well is harder than it sounds.  
Audio in particular is hard to do well.  
Consult your local streaming professional.

# Toppings

There are a few things to do after the event is finished.

1. Process the reimbursements  
2. Publish a write-up about your event. See this example for inspiration: [https://blog.python.cz/prague-python-pizza](https://blog.python.cz/prague-python-pizza)   
3. Post conference feedback form. See example here, form “Survey”: [https://drive.google.com/drive/folders/1iDcWwoGl3fwLDOSD5MZlyrGKLdEj_VKM](https://drive.google.com/drive/folders/1iDcWwoGl3fwLDOSD5MZlyrGKLdEj_VKM)
