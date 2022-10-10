
# CHAPTER TWO

## 2. LITERATURE REVIEW

### 2.1 INTRODUCTION

The content of this chapter summarises the literature and information
about online lecturing that will be the foundation for designing our
project.

This chapter aims to:

- Summarise the history and development of online classrooms.

- Examine existing systems being used by UPSA for online lecturing.

- Compare the proposed system with the existing system being used by UPSA.

### 2.2 GENERAL BACKGROUND OF THE STUDY AREA

<p class="underline_text">

History of Virtual Learning

</p>

Virtual learning was first practised by the University of House in 1953.
The university started offering televised college classes on KUHT (today
called Houston PBS). KUHT aired the classes for 13-15 hours each week,
accounting for approximately 38% of the channel\'s total broadcast time.
They aired these courses in the evening to benefit learners who worked
during the day.

The invention of personal computers and the web revolutionised distance
education. In 1989, the University of Phoenix launched the first fully
online university that offered both bachelor's and master's degrees.

Since the making of these complete online schools, distance learning has
kept on growing. Today we enrolled 1 out of 4 undergrads in one online
class. In 2003, the Blackboard Learning System staff declared 40,000
educators were showing 150,000 online courses to over 6 million
understudies across 55 nations. This pattern appears to proceed later
on: as of now, 83% of all U.S. organizations that offer online courses
say they expect an expansion in online enlistment in the coming decade
(*Virtual Classroom Software to Deliver Live Teaching and Training \| WizIQ*, n.d.).

<p class="underline_text">

Components of a live online lecturing platform

</p>

Building a live online lecturing platform involves a lot. A live online
lecturing platform requires knowledge and skills in video streaming, web
development, how the web works, and database management (*Virtual Classroom Software to Deliver Live Teaching and Training \| WizIQ*, n.d.).

<p class="underline_text">

Video Streaming

</p>

Video streaming is the continuous transmission of audio or video data or
files from a server to a client. Video streaming allows the user to
download video content while watching it simultaneously (*What Is Video Streaming and How Does It Work? \| Akamai*, n.d.).

Video Streaming comprises video-on-demand streaming (VOD) and live
streaming.

- Live streaming is streaming real-time or live video feed to an audience retrieving the media stream over the internet. For example, YouTube, Facebook Live, Periscope, and Twitch are live streaming services (*What Is Streaming? \| How Video Streaming Works \| Cloudflare*, n.d.).

- Video-On-Demand (VOD) enables the audience to watch or listen to media stream content upon request. In simple terms, we store VOD contents remotely on cloud storage. An archived live stream can be video-on-demand. For example, Netflix and Hulu are on-demand streaming services (*What Is Streaming? \| How Video Streaming Works \| Cloudflare*, n.d.).

Streaming media over the internet for an audience to watch requires
adopting a streaming technique such as Adaptive Bitrate streaming or
Multi-Bitrate streaming, on the media server.

<p class="underline_text">

Web Development
</p>

Web development is the planning, designing, building, and maintenance of
websites. A website is a collection of publicly accessible, interlinked
**web pages** published on the internet. Web development includes
aspects such as web design, web programming, database management, and
web publishing (*How the Web Works - Learn Web Development \| MDN*, n.d.).

A web developer designs website interfaces using front-end tools like
HTML, CSS, and JavaScript but uses server-side scripting languages like
Python, PHP for writing the logic for the server.

The tools for building a website are many, but the web developer must
decide on which tool to use in developing their websites. Examples of
tools used for web development are HTML, CSS, Python, PHP, JavaScript,
Ruby and more.

<p class="underline_text">

How the Web Works

</p>

Client and server computers connect to the web. **Clients** are the
typical web user\'s internet-connected devices such as PC or phone and
web-accessing software available on those devices like Firefox or
Chrome. **Servers** are computers that store web pages, sites, or apps.

When we open a browser and enter a web address, the following steps
occur:

- The browser goes to the DNS server and finds the actual address of the server that the website lives on.

- The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client.

- If the server approves the client\'s request, the server sends the client a \"200 OK\" message, which means \"Obviously you can view the website\", and sends the website\'s files to the browser as a series of small chunks.

- The browser assembles the small chunks into a complete web page and displays it to you (*How the Web Works - Learn Web Development \| MDN*, n.d.).

<p class="underline_text">

Database Management

</p>

A database is a standardised set of data saved and accessed electronically from a computer system (*What Is a Database \| Oracle*,
n.d.).

Database Management is the data storage tasks and security practices of
a Database Administrator (DBA) throughout the life cycle of the data
(Knight, 2018). Administering a database involves modelling,
implementing, and protecting stored data to expand its value.

There are various types of databases used for storing different
varieties of data which includes centralised database, distributed
database, relational database, non-relational database, network
database, object-oriented database, and hierarchical database.

We will limit our study to two (2) database types. The two (2) types are
**relational database (structured)** and **non-relational database
(unstructured and semi-structured)**.

A **relational database** contains multiple tables of data (relations)
with rows (tuple) and columns (attributes) that relate to each other
through special key fields (*Types of Database System \|
Nibusinessinfo.Co.Uk*, n.d.). Relational databases use Structured Query
Language (SQL). Examples are MySQL, PostgreSQL, SQLite, Oracle, and
MariaDB.

A **non-relational (NoSQL)** **database** takes a variety of forms and
allows you to store and manipulate large amounts of unstructured and
semi-structured data (*Types of Database System \|
Nibusinessinfo.Co.Uk*, n.d.). NoSQL database provides high scalability
and enables good productivity in application development. We can divide
NoSQL databases into four (4) groups. They are Key-value storage,
Wide-column stores, Graph Databases, and Document-oriented databases.
Examples are MongoDB, Couchbase, Firebase, Redis, and Amazon Dynamo DB.

**Database Management System (DBMS)** is software for storing and
retrieving data from the database while considering appropriate security
measures (Peterson, 2021). It comprises a group of programs that
manipulate the database. The DBMS accepts the request for data from
application and instructs the operating system to provide the specific
data. Examples are MySQL, MongoDB, Oracle, and Redis.

### 2.3 REVIEW OF THE EXISTING SYSTEM

The outbreak of the COVID-19 pandemic made it impossible for teachers
and students to conduct in-person meetings. Because of that,
institutions including UPSA adopted the use of a video conferencing app
called **Zoom** for conducting online lecturing.

**Zoom** is a cloud-based video conferencing service you can use to meet
virtually with others - either by video or audio-only or both, all while
conducting live chats - and it lets you record those sessions to view
later. Zoom Video Communications, Inc. created zoom (Tillman, 2021).

![Figure 2.1: Zoom App Logo](images/chapter_2/figure2_1.png){class="center_align"}

<p markdown class="text_align_center">

***Figure 2.1: Zoom App Logo***

</p>

Zoom has become the preferred video conferencing software because of the
following features. They are:

- Huge meeting participant capacity -- Zoom can host up from 100 to 500 participants when you subscribe to the large meeting plan

- Impressive features -- Includes features like whiteboard, screen-sharing, and chat room

- Records meeting sessions--Host can record meetings

- Low-latency -- optimised to process data with minimal delay

According to Wikipedia, Zoom has faced public and media scrutiny related
to security and privacy issues because of unexpected usage. Although it
has some recommendable features, the research team deems it as a
general-purpose video conferencing app and not an app designed for
online lecturing (Wikipedia, 2021).

Although is a functional software, it has certain limitations and
challenges (Tillman, 2021). These limitations are:

- Zoom requires a high-end computer or mobile specifications

- Requires download and installation of software by the user

- Requires download of periodic updates by user

- Inefficient use of device power supply (i.e., high-consumption of battery)

- The user interface is difficult to understand

- Does not provide attendance report

- Slow in adapting to network bandwidth

- Allocates a minimum time (40 minutes) to meetings scheduled using the free tier

- High consumption of data bandwidth

Based on the limitations stated above, the research team proposes to
build a system for small-medium groups to conduct an online lecture.

### 2.4 COMPARATIVE STUDY OF REVIEWED SYSTEM

<p class="underline_text">

The Proposed System

</p>

The proposed system by the research team is a web-based streaming
platform called **iStream**. We built iStream using modern web and
streaming technologies.

The proposed system has the following features:

- Access from any internet browser

- Lower consumption of data bandwidth

- Not requiring download, installation, and periodic updates of software by the user

- Easy, user-friendly, and accessible user interface

- Not requiring users to have a computer or mobile device with higher specifications

- The system records class attendance

- Increase engagement with real-time audio-video and textual communication

- Ultra-low latency--The streaming engine used to build iStream processes data with a very minimal delay

- Adaptive streaming of media using WebRTC technology

- Adapts quickly to network bandwidth

- Improving video performance and quality

The table below gives a vivid comparative difference between the
proposed system and the existing system.

|     | **PROPOSED SYSTEM (iStream)**                | **EXISTING SYSTEM (Zoom)**                    |
|:----|:---------------------------------------------|:----------------------------------------------|
|1\.  | iStream requires users to have a computer or mobile device with an internet browser which most students possess. | Zoom requires a high-end computer or mobile specifications which most students do not possess (Zoom Help Center, 2021). This results in fewer students joining meetings.|
|2\.  | iStream being a web-based platform does not require a download, installation, and periodic updates of software by the user. | It requires download, installation, and periodic updates of software by the user.|
|3\.  | The team optimised the system to process media data with ultra-low latency. | Optimised to process media data with low latency.
|4\.  | It has an easy, user-friendly, and accessible user interface. | The user interface is difficult to understand, so users do not utilise most features (Tillman, 2021). |
|5\.  | It shows participants and records class attendance for each meeting. | It shows participants but does not record and print attendance. |
|6\.  | Adapting to network bandwidth changes is fast because of the WebRTC technology being used (Graves, 2018). | Slow in adapting to network bandwidth.|
|7\.  | iStream ensures it encrypts data by putting in security measures like streaming only on HTTPS protocol, one-time passwords for hosts, sanitising data before inserting in the database, usingsecured database management systems, and setting HTTP security headers like HSTS, X-XSS-Protection, etc. on HTTP Responses. | Although, Zoom has been criticised for security lapses, poor encryption practices, and poor design choices (Wikipedia, 2021). Zoom offers a range of authentication methods such as SAML, Two-Factor Authentication (2FA), OAuth, and/or Password-based which can be individually enabled/disabled for an account.|
|8\.  | It consumes less data bandwidth because of the adaptive bitrate streaming technique and WebRTC technology being used (*Adaptive Bitrate Streaming (ABR) \| Video Streaming Definition*, n.d.). | Zoom consumes high data bandwidth. If there is high network coverage, an average zoom can consume 800 MB up to 1.64 GB. If the network is slow or average, it might consume around 300MB per hour (Aachri, 2021).|
|9\.  | iStream does not allow recording of meeting video to prevent high usage of data bandwidth. | It allows the host to record and save meetings. Recording and saving meetings will require additional use of data bandwidth since the meeting video has to be converted into a playable format like mp4 before they save it on the user's computer or online storage.|

<p markdown class="text_align_center">

***Table 2.1: Comparing the proposed system with the existing system***

</p>

### 2.5 CONCLUSION

In conclusion, the literature review brings to light an overview of the
history and development of online classrooms and the contribution of
people and organisations to online classrooms. The research team
examines the existing system used by UPSA for online lecturing and
compares the proposed system with it. The proposed system seeks to
address the challenges of the existing system by developing a specific
application system for online lecturing.
