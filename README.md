# AAMP-Chats

**AAMP-Chats** is a GitHub project focused on learning multiple programming languages and frameworks through the development of a chat application. Short for **"All Around Multi-Platform Chats"**, it's a simple yet functional app where users can:

- Create an account  
- Connect/befriend other users  
- Send messages (including files)  
- Create group chats  
- Remove connections  
- And more features typical of a modern chat app  

This repository contains various implementations of AAMP-Chats using different programming languages and frameworks.

---

## Programming Languages and How to Start Them

To start the project, you usually need to run both a **front-end** and **back-end**, unless the framework supports both (like **Next.js**).  
You also will need to run the dockerfile present in the root directory to run the mongodb database and the websocket for direct updates for chats, etc.

If this is your first time setting up the project, make sure to **install dependencies** in the `ws` folder for the websocket service by running:

```bash
cd ws
npm install
```

Afterward, you can proceed with starting the project.

The table below lists each version of the project, its role (front-end, back-end, or both), and the command to start it in development mode. This helps you know what parts are needed to get each version running.

| Programming Language     | Framework (if applies) | Type  | Command to Run in Dev Mode           |
|--------------------------|------------------------|-------|---------------------------------------|
| JavaScript + TypeScript | Next.js               | Both  | `(cd nextjs && npm run dev)`          |

*(More entries to come as the project expands)*

---

## Why a Chat App?

I chose to build a chat app for several reasons:

1. It challenges me to think: *"How would I implement this in a given language or framework?"*
2. A chat app is well-suited for many of the technologies I want to learn, such as:
   - ASP.NET / C#
   - Ruby on Rails
   - Angular
   - And more...
3. It strikes a balance: the project is large enough to be meaningful but not so overwhelming that I’ll lose focus.

---

## Why Multiple Languages and Frameworks?

I’ve always had a strong interest in expanding my programming knowledge. By building the same app in multiple ways, I get to:

- Explore different front-end and back-end ecosystems  
- Learn language-specific best practices  
- Compare and contrast various development approaches  

Each implementation helps me grow as a developer and deepens my understanding of the tools and languages I use.

---

## Can You Use This Idea Too?

Definitely! In fact, when people ask me how to start learning programming, I often recommend building something like this.  
You are free to use this repository in any way you like (as long as it follows the included license).

You can:

- Study how I implemented features  
- Improve on my approaches  
- Use my code as reference when you're stuck
