# Project 2 Proposal

## Project Description

My app is called Astronomy Picture of the Day or APOD, for short. It is an Astronomy app, that generates a random image that relates to Astronomy, from around the world. With each image, the app will provide a brief description of its significance and an explanation of what you are viewing. Users can select previous APOD's from the previous days or they can search specific dates.

## Wire Frames

**Initial Landing View**

![Screen Shot 2020-07-28 at 7 54 48 AM](https://media.git.generalassemb.ly/user/28784/files/c2878a80-d0a7-11ea-854a-46f2d17a450e)

## User Stories

#### MVP Goals

- As a user, I want to see the APOD, with a description of what I am viewing and other relevant information.

- As a user, I want to be able to look up specific dates, to see what the APOD was, for that specific day.

- As a user, I want to be able to be able to easily navigate the screen, without getting confused.

#### Stretch Goals

- As a developer, I want to create a more dynamic search functionality, so that if you're interested in seeing a specific event, you can search for those specific pictures.

- As a developer, I want to incorporate a secondary API, that provides realtime images of earth.

#### API

GET https://api.nasa.gov/planetary/apod

{
copyright: "Ariel L. Cappelletti",
date: "2020-07-28",
explanation: "Dark shapes with bright edges winging their way through dusty NGC 6188 are tens of light-years long. The emission nebula is found near the edge of an otherwise dark and large molecular cloud in the southern constellation Ara, about 4,000 light-years away. Born in that region only a few million years ago, the massive young stars of the embedded Ara OB1 association sculpt the fantastic shapes and power the nebular glow with stellar winds and intense ultraviolet radiation. The recent star formation itself was likely triggered by winds and supernova explosions, from previous generations of massive stars, that swept up and compressed the molecular gas. The featured image accumulated over 10 hours through a backyard telescope in Córdoba, Argentina and was false-colored using the Hubble palette highlighting emission from sulfur, hydrogen, and oxygen atoms in red, green, and blue hues. The field of view spans about four full Moons, corresponding to about 150 light years at the estimated distance of NGC 6188.",
hdurl: "https://apod.nasa.gov/apod/image/2007/N6188_Cappelletti_4508.jpg",
media_type: "image",
service_version: "v1",
title: "NGC 6188: The Dragons of Ara",
url: "https://apod.nasa.gov/apod/image/2007/N6188_Cappelletti_960.jpg"
}

#### Component Hierarchy

![Screen Shot 2020-07-28 at 7 57 42 AM](https://media.git.generalassemb.ly/user/28784/files/07132600-d0a8-11ea-8fb2-40acbd0771e7)
