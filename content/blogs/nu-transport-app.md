---
title: "✧･ﾟNU transportation app interface"
date: 2025-06-01
draft: false
tags:
  - ux research
  - ui/ux design
---

## background

in an increasingly digital age, there are plenty of transportation apps on the market. some examples of which include tripshot, an app providing info about upcoming buses or trains, and NUTransit, an app that provides rides for northwestern students around campus. for my human-computer interaction class, i interviewed a classmate for a project where i designed an interface for a transportation app, finding out their needs and pain points in the process.

## research process

for this project, i was tasked with interviewing a classmate about their transportation habits. i did this in the form of an unstructured interview, where i had a general list of questions that i wanted to ask but let the conversation guide itself. i found out, that at northwestern, they use the following forms of transport:

- bus
    - uses an app called tripshot
    - buses on campus don’t really come in early hours, moreso in afternoon/evening
    - probably it’s free for us students and there’s more of an incentive to use transportation when it’s later/darker out
    - interviewee wishes it operated during earlier hours
- NUTransit
    - can't use the app until 7 pm
    - they find this policy pretty reasonable, because not many drivers + free for students

##### walkthrough of NUtransit

NUTransit, formerly known as saferide, is an app that allows drivers to drive students around campus after 7 pm. once you open the app, you should see a prompt showing your current location, asking you to put in your desired location. you will see rides that will help you get there, as well as their corresponding arrival times. however, a pain point that i found out from my interviewee is that ridesharing, although more efficient than solo rides, causes delays in pickup. my interviewee wishes that feature could be more reliable in terms of timing and also doesn't like the fact that they can't change the number of passengers. they believe that adding a ~5 min "buffer time" would make the time estimate more realistic and would prefer knowing if their ride was cancelled rather than being "left on limbo".

##### walkthrough of tripshot

tripshot is an app that provides info about upcoming buses or trains, providing possibles ways to get to a certain destination. it also tells about potential lane closures/warnings, which is a feature lacking on most map apps. my interviewee said that they like that tripshot shows options to get to a particular location but doesn't really look at those since they find it hard to memorize the bus stop closest to the location. they also would like closure regarding delayed buses/trains, and thinks that a feature allowing them to edit the number of passengers on a bus/public transport app is a bit redundant. they also feel like the app is almost copying google maps in some respect, such as adding options for driving.

##### interviewee needs

- clarity
- closure
- relevant features only
- to be able to get across campus without walking too much

##### feature ideas that i came up with:
<div id="carouselExample" class="carousel slide" data-bs-ride="carousel" style="max-width: 50%; margin-top: 5%; margin-bottom: 5%; margin-left: 25%;">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="/images/ideation/1.png" class="d-block w-100" alt="Project 1">
    </div>
    <div class="carousel-item">
      <img src="/images/ideation/2.png" class="d-block w-100" alt="Project 2">
    </div>
    <div class="carousel-item">
      <img src="/images/ideation/3.png" class="d-block w-100" alt="Project 3">
    </div>
    <div class="carousel-item">
      <img src="/images/ideation/4.png" class="d-block w-100" alt="Project 3">
    </div>
    <div class="carousel-item">
      <img src="/images/ideation/5.png" class="d-block w-100" alt="Project 3">
    </div>
    <div class="carousel-item">
      <img src="/images/ideation/6.png" class="d-block w-100" alt="Project 3">
    </div>
    <div class="carousel-item">
      <img src="/images/ideation/7.png" class="d-block w-100" alt="Project 3">
    </div>
    <div class="carousel-item">
      <img src="/images/ideation/8.png" class="d-block w-100" alt="Project 3">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
  </button>
</div>

##### which ideas did i choose to move forward with?

i decided to combine multiple ideas into one interface: the +/- buttons, the cancellation message, and the upcoming ride matching algorithm.

i chose these because it provides my user with a sense of closure if their ride gets cancelled, and the matching algorithm guarantees them another ride so they can get across campus without walking too much. this design allows them to edit the number of passengers, so it addresses most of their needs and pain points.

##### my first prototype, on paper:
<img src="/images/prototype.png" class="mx-auto d-block" style="max-width: 50%; margin-top: 5%; margin-bottom: 5%;">

##### user testing

for user testing, i used a thinkaloud, reading out a script like a second-person story, asking the user to imagine themselves getting out of the library at 9 pm after a long study sesh, calling a saferide and adjusting the number of passengers. i then ask them to imagine their ride being canceled and the algorithm matching them up with another ride, displaying info about their new ride. after my thinkaloud, i gather feedback from my user.

##### feedback

the user really liked it!

they think it sufficiently addressed all their needs. however, one thing i could have done better was adding paper flaps to the prototype to imitate buttons, scrolling, and changes of screens, allowing the user to interact with it more realistically.

##### final prototype (figma)

here is my final prototype, done on figma, to mimic what it would actually look like on a phone screen:

<div style="max-width: 50%; margin-top: 5%; margin-bottom: 5%; margin-left: 35%;">
    <iframe
        src="https://embed.figma.com/design/wAuBDtKiUjtUa8D5EDGBVC/Untitled?node-id=0-1&embed-host=share"
        allowfullscreen>
    </iframe>
</div>