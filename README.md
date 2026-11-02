# Nested Group Chat

A unique group chat program that allows users to create Reddit-like threads for better organization of different conversation topics.

## The Problem

In group chats with lots of people, its common to have multiple different conversations happening at once. People are trying to send their own updates, reply to others, read other's stories, and read the replies of other people's stories. In an ordinary, linear group chat, it can be difficult to understand what's going on.

## How It Works

My proposed solution is to combine normal group chat features with Reddit-like threads. When people are sending short, simple messages, they can use the group chat like a normal one. But if someone is trying to send a longer story or an update about their life, they can create a thread. Threads will appear as links in the main group chat, and when users click on them, they will be taken to a seperate page that contains the thread creator's story as well as everyone else's replies. This allows for better organization in your group chats.

![[docs/system-diagram.png]]

### MVP Scope

For the MVP, I will be creating a local group chat program with my nested threads idea added to it. Upon running the program, you will be able to choose a group member account to send messages through (for testing) and then view the entire group chat's history thanks to the JSON storage. You will be able to send messages, create threads, and reply in threads.

## Future Plans

Once the MVP is complete, I plan to create a network as well as login system. These additions will further shape this project into a real group chat application. Afterwards, you can expect more features such as sending images, audio recordings, videos, threads inside threads, and more.

## Tech Stack

- **Languages:** Java
- **Libraries:**
	- Swing
	- JSON
	- JUnit
- **External Tool:** GitHub

## Setup

More on this when the project is further updated.