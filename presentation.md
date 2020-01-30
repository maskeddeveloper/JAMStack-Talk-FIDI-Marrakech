---
marp: true
title: Getting Started with JAMStack
description: Understand why it exists and how to get started
theme: uncover
paginate: true
_paginate: false
---

![bg](./assets/gradient.jpg)

# <!--fit--> Getting Started with JAMStack

Understand why it exists and how to get started

<style scoped>a { color: #eee; }

</style>


---
![bg](#123)
![](#fff)
# WHO AM I?
- I'm Mehdi Hamime
- I work as a Full Stack developer @Deloitte
- I'm a JavaScript & Open Source enthousiaste

---
# What is 

<style>
img[src*="#img"] {
   width:100%;
   height:100%;
}
</style>

![JamStack Logo](https://d33wubrfki0l68.cloudfront.net/0e10c97634da0242be91bec4f6a198a78dd68f99/b5de5/img/jamstack-full-logo.svg#img)

---
**JAM stands for JavaScript, API & Markup**

>A modern web development architecture based on client-side JavaScript, reusable APIs, and prebuilt Markup
Mathias Biilmann (CEO & Co-founder of Netlify).

---
![bg](#000)
![](#fff)

![Jam Arch](assets/jam.png#img)

---


![bg right 70%](https://user-images.githubusercontent.com/4727/38117842-2d270f22-336c-11e8-8413-e5daf9ae41e9.png)

## **JavaScript**

 Dynamic functionalities are handled by JavaScript. There is no restriction on which framework or library you must use.

---


![bg right 70%](./assets/api.png)

## **APIs**

 Server side operations are abstracted into reusable APIs and accessed over HTTPS with JavaScript. These can be third party services or your custom function.

---


![bg right 70%](./assets/markup.png)

## **Markup**

Websites are served as static HTML files. These can be generated from source files, such as Markdown, using a Static Site Generator.

---

![bg](#123)
![](#fff)

#### BENEFITS

##### 👉 Faster performance : 
- Serve pre-built markup and assets over a CDN

##### 👉 More secure : 
- No need to worry about server or database vulnerabilities
  
##### 👉 Less expensive : 
- Hosting of static files are cheap or even free

---

![bg](#123)
![](#fff)

#### BENEFITS

##### 👉 Better developer experience : 
- Front end developers can focus on the front end, without being tied to a monolithic architecture. This usually means quicker and more focused development

##### 👉 Scalability : 
- If your product suddenly goes viral and has many active users, the CDN seamlessly compensates




--- 
![bg](#123)
![](#fff)

#### BEST PRACTICES

##### 👉 Content delivery network : 
- Since all the markup and assets are pre-built, they can be served via CDN. This provides better performance and easier scalability.


##### 👉 Atomic deploys : 
- Each deploy is a full snapshot of the site. This helps guarantee a consistent version of the site globally.


--- 
![bg](#123)
![](#fff)

#### BEST PRACTICES

##### 👉 Cache invalidation : 
- Once your build is uploaded, the CDN invalidates its cache. This means that your new build is live in an instant.



##### 👉 Everything in version control : 
- Your codebase lives in Version Control System, such as Git. The main benefits are: change history of every file, collaborators and traceability.


--- 
![bg](#123)
![](#fff)

#### BEST PRACTICES

##### 👉 Automated builds : 
- Your server is notified when a new build is required, typically via webhooks. Server builds the project, updates the CDNs and the site is live.

--- 

![bg right 70%](https://assets.zeit.co/image/upload/front/assets/design/now-black.svg)

## **[ZEIT Now](https://zeit.co/now)**

#### Ready to write & host your deck!

[![Deploy with ZEIT Now h:1.5em](https://zeit.co/button)](https://zeit.co/new/project?template=https://github.com/yhatt/marp-cli-example)

---

### <!--fit--> :ok_hand:

