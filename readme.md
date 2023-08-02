# Distributed Systems

# About

Are you interested in distributed systems, high scalability, bottlenecks, microservices, architecture, tools, and frameworks? If so, you are part of a community of like-minded tech enthusiasts where we discuss building distributed systems and the related concepts.

## **Frequency**

We catchup monthly over meet (or live at times in coffee shop) - **PST/PDT timezone**

> 📌 **Please share your email in [this form](https://forms.gle/yhgVCQaX8mBbVUj86) so we could invite you to the future events.**

## Format

We follow the [Lean Coffee](https://leancoffee.org/) format, where we share topics of interest, vote, and discuss the most popular topic with a moderator keeping each topic to a specified time.

We’ll be gather the topics, vote and discuss on this [Trello Board](https://trello.com/invite/b/3xNrmYD6/ATTIdeadf6a3dc375f103d12349e880e7b54EF080836/distributed-systems-coffee-chat-02).

Topics which are frequently discussed in this space,

- Monolith vs Microservices
- Event Driven Architecture
- Deployment practices & Production readiness
- Handling Failures & Scaling
- System Design & Architecture
- Kubernetes, Docker, Cloud, etc
- Automation & DevOps
- CAP

## Books

- Building Data Intensive Applications, Martin Kleppman
- [Building Microservices, Sam Newman](https://samnewman.io/books/building_microservices_2nd_edition/)


### Interesting Problems

Some problems / theories are interesting and hard to solve and it’s applicable to distributed systems and captures the essence of failures or ways we need to handle.

- **Byzantine General's Problem**
- Two general’s problem: [YT video by Tom scott](https://www.youtube.com/watch?v=IP-rGJKSZ3s&t=438s&ab_channel=TomScott)
- **Time synchronization**
- **Exactly Once**

If you’re into papers, PapersWeLove have a great [list](https://github.com/papers-we-love/papers-we-love/blob/main/distributed_systems/README.md), especially one’s by Leslie Lamport are great.

## Organizer

Dineshkumar \
Founder @ Scalescape, Inc \
Built high scale systems at Gojek, Elasticsearch. \
Co-organized [Golang-Bangalore](https://www.meetup.com/golang-bangalore) and [Distributed-Systems Bangalore](https://www.meetup.com/distributed-systems-bengaluru/) meetup. Have shared my experience actively in conferences & meetups. Checkout my past [talks](https://devdinu.github.io/talks.html) and [recordings](https://www.youtube.com/@relyonmetrics/videos) where i’ve discussed distributed systems, kafka and Go. \
[LinkedIn](https://www.linkedin.com/in/dinesh-kumar) | [Twitter](https://twitter.com/devdineshkumar)

## Call for Volunteers, Speakers, and Hosts
- We’re looking for volunteers and moderators who wants to be part of the community.
- If you’ve worked in production systems with experience in this space, let us know, so we could schedule a sessions where you can share more on your expertise.
- If you’ve a space to host or willing to sponsor future events please reach out to us

# Events

## 03 Live Meet 14-Aug-2023

[Distributed Systems Chat #03 - In Person · Luma](https://lu.ma/dsys03)

## 02 Virtual 10-May-2023

[Distributed Systems Chat #02 · Zoom · Luma](https://lu.ma/dsys02)

## 01 Live Meet 06-Apr-2023

We discussed around distributed-systems, horizontal scaling, migration to GO, downtime and production readiness.

<details>
<summary><b>Meeting Notes</b></summary>

### Distributed systems at high scale without k8s (pain points)

- k8s was able to scale easily for the need
- using EKS was frustrating
- warm up instances, and use containers
- pain points of k8s at high scale
- without k8s scaling based on usage was tricky

### Horizontal scaling vs vertical scaling
- vertical scaling for storage
- horizontal scale for applications (CPU/Memory)
- something which allows us to scale down
- business case  - indexing

### Migration to go and personal experience
- Proxy - picked go where we neded an alternate and it worked out well so far
- Helped us reduce infrastructure cost, deployment time and increased performance

### Downtime experience - Complex distributed systems

### Production readiness
exponential backoff, timeouts
Auto scaling based on requests

### Tools / Key terms
envoy, k8s, production-readiness

</details>

[Linkedin post: #leancoffee #go #distributedsystems #meetup #go #reliability](https://www.linkedin.com/feed/update/urn:li:activity:7050327145415405568/?updateEntityUrn=urn:li:fs_feedUpdate:(V2,urn:li:activity:7050327145415405568))

<img src="https://media.licdn.com/dms/image/D5622AQGsOsOrYXN_IA/feedshare-shrink_1280/0/1680928978733?e=1694044800&v=beta&t=oyDOEgvmjQ7QKz9XSSCkyJmDBhutpDHto2NFHjkUUNA" width=50%>
