---
title: Turning the plan into a clear MVP
date: 2026-05-17
author: Xiangfei SUn
summary: In this post, I move from general planning into a more practical definition of the prototype by narrowing the MVP, deciding which pages matter most, and thinking more carefully about how users will move through the site.
tags:
  - mvp
  - prototype planning
  - user flow
  - image sharing community
---
Following the completion of the wireframes, DDDs, and ERD, I could already identify one major issue with the design, which is that the whole community hub concept was still too broad. Planning ahead has indeed helped me gain a better understanding of the system as a whole, but it also allowed me to realize just how much content was being considered for inclusion within the platform simultaneously. Although posts, events, questions, resources, hubs, memberships, and tags all seemed like great concepts individually, the inclusion of all of them within the system would prove to be problematic in building an MVP prototype.

The most valuable aspect of ERD is that it helped me understand which elements of the system interact most intensely. Examining these interactions, I understood that posts should be made the most central content type. Posts interact organically with users, hubs, tags, and comments and are compatible with the general model of interaction that includes browsing, reading, and commenting. On the contrary, events and resources are also good concepts, but they add extra features that seem excessive for a first iteration of the project. Events include date, time, location, and save status features. Resources and Q&A have answer status, file management, and advanced tag logic options.

As such, I thought that MVP should be about building a community hub for image sharing. Although this approach would not deviate from the basic concept of building a community, it would help the project have more clarity in terms of direction. Rather than build all possible functionality, the project could focus on allowing members to share images complete with captions and tags while engaging in interactions around such images. In turn, the main process flow would involve signing in, looking through images shared recently, reading comments, and posting one’s own image.

Once I had made that decision, it was easy to determine what the main pages would be. The homepage is a feed of recent posts featuring images. Every post card must feature an image, some text, tag labels, author and timestamp information. Once the user clicks on the card, they can view the detail page of the post. It must include the large image, text, tags, comments, and interactive area. In addition, there must be a place for uploading a new image post complete with text and tags. A basic user profile is a necessity, yet only in the form of a list of the posts he/she created.

This way, the process allowed me to distinguish between “must haves” and “can wait.” When thinking about the initial version of the product, I believe that browsing posts, opening posts, uploading images, tagging posts, and posting comments should come first as these elements transform the hub from just a gallery into a true community-oriented product. While liking/favoriting posts could also be included into the first list, they are less crucial compared to comments. As for notifications, collections and search they can definitely wait.

I also feel that it is technically a better way to go too. The functionality fits in nicely with the course-stack flow as the core functionality lends itself to creation and viewing of material with a little more interaction via HTMX. It also makes responsive and accessible design a lot easier too, as there would be fewer pages to deal with.

Now, at this stage, things seem to be far more settled than they were previously. At the start, I was still trying to figure out what kind of content the hub would be able to hold. Now I can see where it will begin more clearly.
