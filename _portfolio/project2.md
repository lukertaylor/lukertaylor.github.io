---
title: Dads Joke Daily
subtitle: Get jokes at the push of a button, or a daily joke notification.
image: https://play-lh.googleusercontent.com/SXscOsQdNnxU86AR7_7JlLtsUrmLqghjUSGOqqtOrRr9Io9pW08jjEGPo-Tr8A5DI2M=w480-h960-rw
alt: Keep Exploring

caption:
  title: Dads Joke Daily
  subtitle: Get jokes at the push of a button, or a daily joke notification.
  thumbnail: https://play-lh.googleusercontent.com/SXscOsQdNnxU86AR7_7JlLtsUrmLqghjUSGOqqtOrRr9Io9pW08jjEGPo-Tr8A5DI2M=w480-h960-rw
---

### Introduction
The main aims for this project was to continue to build my mobile app development skills, adding 100% line coverage for unit tests, in-app banner advertisements and push notifications.

### Solution
Dad Jokes Daily gets its jokes from the [icanhazdadjoke.com](https://icanhazdadjoke.com/) dad joke API. The app is integrated with Google AdMob for advertisements. Google Firestore is used to hold push notification configurations,  and store submitted jokes. Firestore has additional security enabled using Google App Check to ensure that only the Dad Jokes Daily app can access the Firestore database, and the device accessing Firestore has not been tampered with.

The push notifications make use of a Google Cloud Function (Node.js) to control sending out notifications using the Google Firebase Cloud Messaging service.
