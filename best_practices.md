# Best Practices

This page provides guidance on running a new Cloud Native Community Group based on the experience of existing ones. 
The diagram below outlines common steps for organizing a meetup. 
Depending on the size of your meetup, additional steps may be required.

```mermaid
flowchart TB
    create[0. Create a Cloud Native Community Group] --> start[1-Start planning the event]
    start -.- speakers[Find speakers] & sponsor[Find a sponsor]
    sponsor -.- location[Event location] & food[Food and drinks]
    start --> schedule[2-Schedule the event]
    schedule --> announce[3-Announce the event]
    announce --> run[4-Run the event]
    run --> wrapup[5-Post event]
    run -.- setup[Setup Location] & welcome[Welcome attendees] & program[Conduct program]
    wrapup --> start
    wrapup -.- retro[Retro] & resources[Share documents and pictures]

    classDef mainPath fill:#6A5ACD,stroke:#4747FF;
    class create,start,schedule,announce,run,wrapup mainPath;
```

Each of the steps above is now described in more detail.

- [0. Getting Started](#0-create-the-cloud-native-community-group)
- [1. Start planning your event](#1-start-planning-you-event)
  * [Find Speakers](#find-speakers)
  * [Sponsorships](#sponsorships)
- [2. Schedule a new event](#2-schedule-a-new-event)
  * [Booking](#booking)
- [3. Announce the event](#3-announce-the-event)
- [4. Run the event](#4-run-the-event)
  * [Preparation](#preparation)
  * [Event Introduction](#event-introduction)
  * [Hosting the event](#hosting-the-event)
- [5. Post event](#5-post-event)
- [CNCF Community Groups Host and Organizer Checklists](#cncf-community-groups-host-and-organizer-checklists)
  * [Host Checklist](#cncf-community-groups---host-checklist)
    + [Confirm event details](#confirm-event-details)
    + [Set up the event space](#set-up-the-event-space)
    + [Plan food and refreshments](#plan-food-and-refreshments)
    + [Assist with event check-in](#assist-with-event-check-in)
    + [Foster a welcoming and inclusive atmosphere](#foster-a-welcoming-and-inclusive-atmosphere)
    + [Coordinate with speakers and organizers](#coordinate-with-speakers-and-organizers)
  * [Organizer Checklist](#cncf-community-groups---organizer-checklist)
    + [Manage communications ahead of the event](#manage-communications-ahead-of-the-event)
    + [Manage time during the event](#manage-time-during-the-event)
    + [Facilitate audience engagement](#facilitate-audience-engagement)
    + [Post-event tasks](#post-event-tasks)
- [General notes](#general-notes)
  * [CNCF swag](#cncf-swag)
  * [Ask for help](#ask-for-help)

## 0. Create the Cloud Native Community Group

CNCF staff is responsible for creating the Cloud Native Community Groups. For detailed instructions, refer to the [README.md](../README.md) file and the official [Bevy documentation on how to create a chapter](https://help.bevylabs.com/article/454-create-a-chapter).
It is helpful to create a community Slack channel, such as `#cloud-native-<city name>` for event coordination ([CNCF Slack](https://app.slack.com/client/T08PSQ7BQ/C015WPLD3F1)).

The **description** of the group is at the discretion of the organizers. You may include a brief description of the CNCF and the Cloud Native approach using text from the [Cloud Native Definition](https://github.com/cncf/toc/blob/master/DEFINITION.md).

The most important aspect is to maintain an **active group** with frequent events (ideally once a month or at least once every 90 days). Regular online or in-person events are encouraged.

Managing a group can be challenging. Ideally, you should have a team of passionate and committed co-organizers. Joining forces helps distribute the workload and expand the network.

## 1. Start planning your event

### Find Speakers

Provide a **form** to allow people to submit their talk proposals. You can use a template similar to this [Speaker Proposal Form](https://docs.google.com/forms/d/1V2Y03YMOrIor0M796_WMbYx-fdsn80ngaT-PIum8gUU/edit).

> **_Note_**: Make a copy of the form! Please do not edit the template.

Pro Tip: Sessionize offers a community license if you host free community events. [Read more](https://sessionize.com/playbook/community-license)

Review presentations carefully and always abide by CNCF's values to remain vendor-neutral.

> **Vendor neutrality** in the context of a conference session refers to the principle of maintaining an impartial and unbiased environment during the session, particularly when discussing products, services, or solutions offered by different vendors. The goal is to ensure that the content presented is free from any undue influence, endorsements, or promotional activities related to specific vendors. By adhering to the concept of vendor neutrality it fosters an environment where knowledge sharing and learning take precedence over commercial interests, benefiting both attendees and the broader industry.

Attend **conferences** (e.g, DockerCon, CloudNativeCon, etc.) to find potential speakers and network with individuals involved in CNCF projects who may be interested in joining your group.

### Sponsorships

Contact local technology companies as many are interested in sponsoring events. 
Aim for a central location to make it more accessible to attendees. 
If on a budget, consider cold dishes and provide vegan and vegetarian options.

What to offer the sponsors in return:
* Thank your sponsors by highlighting them in the "Sponsor" tab within your Bevy event settings. You can do this by uploading their logo and adding a link that takes people to their website.
* Allow them to set up a small table at or near the event location for engagement with the audience.
* Provide up to 15 minutes of stage time for sponsor presentations, but ensure they are NOT the main content.

## 2. Schedule a new event

Set up a detailed agenda for the event. Each talk description should include:

```
- A short bio of the speaker
- An attractive title
- A paragraph describing the content of the presentation/demo
```

If you're planning a hands-on demo, ensure that the WiFi can handle the number of attendees.

Also, check for any quotas or limitations imposed by your cloud provider.

The choice of date and time matters. Most meetups are held on Tuesdays, Wednesdays, or Thursdays after work, but adjust based on local culture.

### Booking

If the room capacity limits you, you should do an **overbooking**.

Most of the time, 30% of people who RSVP never show up. Recent KCDs (1 to 2 day summit-like events) have shown a 92% show rate.

Send a **reminder** message to the meetup group to encourage those who cannot attend to free up their spot.

## 3. Announce the event

The following steps can be useful to attract more attendees to your event:

- Reach out to meetups in your area asking them to share your event (don't forget to return the favor)
- Post on social media channels and notify the CNCF to bump your message. This can be done in the Slack workspace via the #socialmedia channel. Tag Katie Meinder and she will amplify from the CNCF main accounts, provided your post is vendor-neutral.
- Place your event in newsletters and podcasts
- Write an 800-word CNCF blog post and submit it for review at pr@cncf.io.


## 4. Run the event

Here are a few tips you should look out for when running the event:

### Preparation
- **Guide attendees to the event location**: Ensure clear signage from the street to the event venue.
- **Prepare the speaker room**: Conduct a technical check and arrange chairs and equipment.
- **Guide attendees at the venue**:  Label pathways to restrooms, elevators, and other relevant areas. Clearly mark restricted areas.
- **Food**: Set up a designated area for food and label ingredients for allergens and dietary preferences (e.g., vegan, kosher, halal...).

### Event Introduction

When introducing the event, here are common recommendations you should cover:

- **CNCF Code of Conduct**: As a CNCF Community Event, you adhere to the [code of conduct](https://www.cncf.io/conduct/) which you can summarize to be "excellent to each other".
- **Photography disclaimer**: Inform attendees that photos will be taken and some may be shared publicly.
- **Thank sponsor(s)**
- **Welcome feedback**: Provide contact information for attendees to ask questions and share feedback.

### Hosting the event

Some learnings when facilitating the event:

- **Hosting**: It is useful to select one of the organizers as host to give the event introduction, introduce speakers and in general provide guidance to the audience during the event.
- **Speaker times**: It often happens that a talk takes a little longer than anticipated or the audience is asking many questions. In smaller meetups you can be flexible about it, in bigger events you should interrupt and stick to the schedule.

## 5. Post event

If possible, you should record videos of the presentations and take pictures for social media and the event page to share afterward.

You should also **share** the slides with all members after the event. Optionally, please submit them to the [CNCF Presentations repo](https://github.com/cncf/presentations) on GitHub.

It is also recommended to meet with the other organizers for a debrief to discuss what went well and where to improve for the next meeting.

## CNCF Community Groups Host and Organizer Checklists

These checklists are designed to support you in your role as a venue host or organizer for the CNCF Community Groups event. They provide a guide to help you prepare and manage the event effectively.

### CNCF Community Groups - Host Checklist

Thanks for being our venue host! This checklist will assist you in preparing the event space and ensuring a smooth experience for attendees.

#### Confirm event details

- [ ] Confirm event date, time, and location.
- [ ] Ensure the venue is available and suitable for the event size.
- [ ] Check if any permits or permissions are required for hosting the event.

#### Set up the event space

- [ ] Arrange seating, tables, and any necessary presentation equipment (e.g., projector, screen, microphones).
- [ ] Test all equipment to ensure proper functionality.
- [ ] Provide clear signage directing attendees to the event space, including a map showing washrooms.

#### Plan food and refreshments

- [ ] Coordinate with the organizers on the type and quantity of food and drinks to be served.
- [ ] Ensure that dietary restrictions and allergens are considered and labeled accordingly.
- [ ] Plan for the timely arrival of food and refreshments, ideally at the start or during a designated break.

#### Assist with event check-in

- [ ] Welcome attendees as they arrive and check them in, if necessary.
- [ ] Provide any necessary information about the venue (restrooms, emergency exits, etc.).
- [ ] Distribute name tags or other identification materials, if applicable.
- [ ] Address accessibility needs at the venue, such as wheelchair access or sign language interpreters.

#### Foster a welcoming and inclusive atmosphere

- [ ] Create a welcoming environment for all attendees, ensuring inclusivity and respect.

#### Coordinate with speakers and organizers

- [ ] Review the event agenda and communicate any last-minute changes.
- [ ] Ensure speakers have everything they need for their presentations (e.g., clicker/slide advancer, possibly USB and USB-C adapters for different machines).
- [ ] Offer assistance in setting up and troubleshooting any presentation equipment.

### CNCF Community Groups - Organizer Checklist

As an organizer, you play a crucial role in managing various aspects of the event. This checklist will guide you through the necessary tasks before, during, and after the event to ensure its success.

#### Manage communications ahead of the event

- [ ] Send speaker logistics ahead of time, including presentation time and setup requirements.
- [ ] Request the speaker's headshot and preferred bio.
- [ ] Ask to review their slides in advance to ensure there are no vendor pitches.
- [ ] Specify screen dimensions (considering 4:3 or 16:9 slide aspect ratio).
- [ ] Allocate Q&A time and any networking opportunities.
- [ ] Build a survey for attendee feedback during the event and generate a QR code.
- [ ] Create housekeeping slides to loop at the beginning and end of the event, including the QR code for the survey.

#### Manage time during the event

- [ ] Serve as the emcee to address light housekeeping items and introduce speakers.
- [ ] Monitor the event's schedule and gently remind the speaker(s) of time limits.
- [ ] Assist with transitions between speakers or activities to maintain the event flow. Use this opportunity for housekeeping announcements.

#### Facilitate audience engagement

- [ ] Encourage attendees to participate in discussions or activities.
- [ ] Assist with Q&A sessions, if applicable.
- [ ] At the end of each session, ask attendees to take time to review the session by filling out the survey you provided on the housekeeping slides.
    - [ ] Note: Asking for feedback while attendees are still seated and the content/experience is fresh in their minds tends to yield better feedback.

#### Post-event tasks

- [ ] Assist with clean-up and restore the event space to its original state.
- [ ] Gather any lost-and-found items for attendees to retrieve.
- [ ] Thank the attendees for their participation and invite them to future events.
- [ ] Upload any videos or photos for post-event promotion.

## General notes

### CNCF swag

If you're a **newly** created meetup and added to community.cncf.io, you have the opportunity earn swag! If you have hosted at last two events within a 90-day period, please reach out to community-groups@cncf.io for a complimentary $100 swag certificate to the [CNCF Store](https://store.cncf.io). Just link to the two events of yours that are in reference.

### Ask for help

If you have any other questions, you can ask them in the [CNCF Slack](https://cloud-native.slack.com/archives/C015WPLD3F1).
