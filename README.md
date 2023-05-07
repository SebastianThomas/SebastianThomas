# 👋 Hi, I’m @SebastianThomas

## 👀 I’m interested in...
-  sports, maths and programming. 
 
In terms of programming, I started with `python`, but soon I discovered `Java` and pretty much everything I could with the German book ["Java ist auch eine Insel" by Christian Ullenboom](https://www.rheinwerk-verlag.de/java-ist-auch-eine-insel/), which was just released for the Java Version 9. Reading this book and having written quite a few applications in this language (hobby and during interships), I would say this is the language I am most comfortable with. 

Furthermore, I started learning JavaScript in 2018 and began with writing frontend applications. Meanwhile, I have learned the frontend framework [`vue.js`](https://vuejs.org/) and, based on it, [`nuxt.js`](https://v3.nuxtjs.org/), which I have used for several school projects. Among these, there are two projects for my english class ([US Space Industry](https://us-space-industry.sthomas.ch/) and [McLaren Racing: History](https://mclaren-history.sthomas.ch/)), and two projects for computer sciences: [My recipe book](https://kochbuch-sebastian.herokuapp.com/) (do not comment on the colors, I know they are terrible :)) and a web project we had to do in 12th grade in pairs of two, unfortunately, the code is still work-in-progress, so private.. 
For backend development, I prefer the popular [`express.js`](https://expressjs.com/). 
What DB do I choose? That always depends on the project, and my coworker(s). I have worked with document-oriented [MongoDB](https://www.mongodb.com/) as well as [MariaDB](https://mariadb.org/) (and [MySQL](https://www.mysql.com/)) as SQL-based DBs. 

In 2021-2022, I participated in the competitition [F1InSchools](https://www.f1inschools.com/), with my team [ISH Racing](https://ishracing.de). It was great that we could attend at the German Championship in Bremen (May 7th, 2022), where we were awarded the price for the 'Best Newcomer' due to the time and effort we put into our car design (including CFD-analysis and real-life tests), portfolios, presentation and pit display. 

### ISH/Learn
In Q2/2022, our task in the informatics class at my school was to build any kind of project with a database. I worked together with @Johann-jpg to build our final product can be found as [ISH/Learn](https://github.com/ishlearn/ishlearn). 

This project was the most complex and complete that I ever participated in, using many technologies and real project management (GH Issues, PRs, the Projects Beta).

#### Technologies 
We decided to use 
- `vue.js` for Frontend, 
- `express.js` for Backend and 
- a MariaDB Database. 

Furthermore, I had fun playing around with other technologies, so that I **dockerized** our app, for the different applications we used can simply be deployed together. With docker, it was then not too difficult to build a CI workflow with GitHub Actions. 

Lastly, my honorable informatics teacher began to throw around words like redis, S3 and others, and so I tried to include all of these technologies. 
- S3 is used as file storage for the projects. It is, running in a docker container (within the compose network) much easier to use than, e.g., an own FTP-file-server. 
- Redis is used as a cache for complex queries that may take longer to compute, so that only the first user will have to wait for the result and the others' waiting time will be reduced by 99% (from 700ms to just 6-7ms).

## 🌱 I’m currently learning ...
- Java: With the new release cycle of Java, there are always new features coming, and I love exploring what is new. 
- TeX: Started in 2022 by taking notes in classes like physics and maths
- Rust: In 2023, I began learning the Rust programming language to discover low level programming

<!--## 💞️ I’m looking to collaborate on ...-->
## 📫 How to reach me ...
You can contact me either on GitHub, or write me an email (kontakt[at]sthomas.ch). 

<!---
SebastianThomas/SebastianThomas is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
