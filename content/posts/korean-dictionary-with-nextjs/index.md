---
title: "Korean Dictionary With Nextjs and React Native"
date: 2023-08-13T14:26:22+09:00
draft: false
---

This app was created as a way to experiment with some modern front end technologies that support the NextJS and React Native stack, while at the same time, providing a tool which i could use to learn Korean.

It's a simple dictionary lookup which is quick and to-the-point. The current dicitonary service provided by Naver is great but it often has a lot more information than i need as a Korean learner. Not to mention, its mobile app is just the embedded web app which is clunky and slow.

<!-- {{< github repo="suejon/hanbyte" >}} -->

Check out the live version of the mobile app here
https://apps.apple.com/us/app/hanbyte/id6471039631

The backend and web app is a NextJS app hosted on vercel, and the mobile app hooks into this backend using TRPC. This stack was based on the T3 turbo stack in this repository:

<!-- {{< github repo="t3-oss/create-t3-turbo" >}} -->

It was a great starting point for creating an end-to-end typesafe application where i could learn about some smart ways to structure projects to faciliate code sharing.

The app is basic at this stage, no doubt about that. But this is a work in progress which i hope to add more capabilities as time goes on.

### Roadmap

{{< timeline >}}

{{< timelineItem icon="github" header="UX Improvements" badge="In progress" subheader="Make it less ugly" >}}
{{< /timelineItem >}}

{{< timelineItem icon="code" header="More Examples" badge="Not started" subheader="Add natural conversations and images using generative AI" >}}
{{< /timelineItem >}}

{{< /timeline >}}
