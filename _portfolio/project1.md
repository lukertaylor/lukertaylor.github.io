---
title: Pocket Open Access
subtitle: Access 200 million open access research articles from you pocket!
image: https://play-lh.googleusercontent.com/OSGRPjJEW3fzJYV3zcYGGGMifntRQeEI4ZTTscR59JJXT0qnw3MQL-O4W4P94xT_IA=w480-h960-rw
alt: Pocket Open Access logo

caption:
  title: Pocket Open Access
  subtitle: Access 200 million open access research articles from you pocket!
  thumbnail: https://play-lh.googleusercontent.com/OSGRPjJEW3fzJYV3zcYGGGMifntRQeEI4ZTTscR59JJXT0qnw3MQL-O4W4P94xT_IA=w480-h960-rw
---

### Introduction
The main aims for this project were to improve my mobile app development skills (interacting with remote API's, accessibility and multilingual support), and create an app that will be valuable for users.

Around the world, there is an inequality regarding access to published research - students and researchers who are affiliated with large Universities and colleges, those that can afford to pay publishers subscriptions for journals, get access to a wealth of research. But people who are either affiliated with organisations who cannot afford journal subscriptions, or are not affiliated with any organisation, cannot afford to buy access to research.

Open Access research works on a pay-to-publish model instead of the traditional pay-to-read model. Researchers, or more usually their organisation or the research funder, pay the publisher to publish the research article as Open Access, which is then available to all. [Core](https://core.ac.uk/) is the world's largest collection of Open Access research papers with over 200 million Open Access articles.

Many users in developing countries don't have ready access to a laptop or desktop, but they do have an Android smart phone. Many of these users do not have regular internet access.

### Solution
[Pocket Open Access](https://play.google.com/store/apps/details?id=com.pocket_open_access) is an Android app that allows its users to search the Core collection and view research articles through a PDF reader. Articles can be downloaded for offline access.

The app searches the Core API using Elasticsearch syntax. Articles are shown in a PDF viewer sourced from [Syncfusion](https://www.syncfusion.com/). Downloaded articles are stored locally on the user's phone filesystem and the article metadata is stored in a Hive database.

The app was built using the Flutter framework, with BLoC for state management.
