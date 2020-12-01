## Magno Sescon

[![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/MrSescon)](https://github.com/MrSescon)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/magno-sescon-168141115/)](https://www.linkedin.com/in/magno-sescon-168141115)
[![Whatsapp Badge](https://img.shields.io/badge/-Whatsapp-4CA143?style=flat-square&labelColor=4CA143&logo=whatsapp&logoColor=white&link=https://api.whatsapp.com/send?phone=5522988319470&text=Olá!)](https://api.whatsapp.com/send?phone=5522988319470&text=Olá!)
[![Gmail Badge](https://img.shields.io/badge/-Gmail-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:magnosescon@gmail.com)](mailto:magnosescon@gmail.com)

#### Salut!!! Je suis un Developeur Full-Stack et au-dessous les technologies que je suis habitué à utiliser. 

- 💻 <b>Programming Languages</b>: 
    </br>
  <a href="https://www.typescriptlang.org/"> ![TypeScript Badge](https://img.shields.io/badge/-TypeScript-black?style=flat&logo=typescript&logoColor=blue)<a/>
  <a href="https://www.javascript.com/"> ![JavaScript Badge](https://img.shields.io/badge/-JavaScript-black?style=flat&logo=javascript&logoColor=yellow)<a/>
  <a href="https://docs.oracle.com/javase/8/docs/technotes/guides/language/index.html"> ![Java Badge](https://img.shields.io/badge/-Java-black?style=flat&logo=java&logoColor=c21325)<a/>
    
- 💻 <b>Front-End</b>: 
    </br>
  <a href="https://pt-br.reactjs.org//"> ![React Badge](https://img.shields.io/badge/-React-black?style=black&logo=react&logoColor=61DAFB)<a/> 
  <a href="https://redux.js.org/"> ![Redux Badge](https://img.shields.io/badge/-Redux-black?&style=flat&logo=redux&logoColor=4C35E3)<a/>
  <a href="https://pt-br.reactjs.org/docs/hooks-intro.html"> ![Hooks Badge](https://img.shields.io/badge/-Hooks-black?&style=flat&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjggOCAxOTAgMTkwIj48ZyBmaWxsPSIjRkZGIj48cGF0aCBkPSJNMTQuNiA1Ni4ySDE3NXYxMTguN0gxNC42ek03Ny4yIDguN2gzNS4ydjM1LjZINzcuMnoiLz48cGF0aCBkPSJNMTAwLjcgMzIuNGgxMS43djM1LjRoLTExLjd6TTIuOSAxMTEuNmgyMy41djM1LjZIMi45ek0xNjMuMiAxMTEuNmgyMy41djM1LjZoLTIzLjV6Ii8%2bPC9nPjxnIGZpbGw9IiM1NTUiPjxwYXRoIGQ9Ik01Ny43IDExNS41bC03LjktNy45LTcuOCA4IDE1LjcgMTUuN0w4MSAxMDcuNmwtNy44LTh6TTEyNC4xIDExNS41bC03LjgtNy45LTcuOCA4IDE1LjYgMTUuNyAyMy41LTIzLjctNy44LTh6Ii8%2bPC9nPjwvc3ZnPg==
@greysteil
 
Contributor
Author
greysteil commented on 21 Feb 2018 • 
I want to use it for Dependabot, which creates badges on its PRs like the ones here and here. We'd been using the base64 format until recently, but it appears the API for it changed slightly recently as the logos stopped appearing.

@paulmelnikow paulmelnikow added the service-badge label on 3 Mar 2018
@paulmelnikow
 
Member
paulmelnikow commented on 3 Mar 2018
We'd been using the base64 format until recently, but it appears the API for it changed slightly recently as the logos stopped appearing.

Separately from the discussion in this PR, could you open an issue for that so we can fix it? I'd really appreciate that!

@paulmelnikow
 
Member
paulmelnikow commented on 3 Mar 2018
Dependabot looks really cool! Is there an API? I would love to have a badge that projects could include, to show off their likelihood of compatibility.

@RedSparr0w I'm fine with including some logos that don't have badges. We'd need a guideline, though. How about, if they are tools that are widely used by developers?

@PyvesB
 
Member
PyvesB commented on 4 Mar 2018
Should we add something along the following lines to the Logo section in Contributing.md?

In general we only accept logos that have a corresponding badge on the homepage (e.g. an Eclipse logo because we support service badges for the Eclipse Marketplace), but we may also approve logos for tools widely used by developers (e.g. our Slack logo).

I'm happy to open a pull request if we're all on the same page here. 👍

@greysteil greysteil mentioned this pull request on 4 Mar 2018
Encoding of logos has changed #1540
 Closed
@greysteil
 
Contributor
Author
greysteil commented on 4 Mar 2018
Separately from the discussion in this PR, could you open an issue for that so we can fix it? I'd really appreciate that!

Done - #1540.

Is there an API? I would love to have a badge that projects could include, to show off their likelihood of compatibility.

No, but I could easily add one! The badges show how compatible a new dependency release is with a previous version, based on all the update PRs Dependabot has created between those two version. So, for example, a 95% compatibility score between Rails 5.1.0 and Rails 5.1.4 would mean 95% of people who updated from Rails 5.1.0 to Rails 5.1.4 had all of their tests passing with no code changes required. Could be a useful thing for dependency authors to put in their changelogs, as well as to be included on Dependabot PRs.

@paulmelnikow
 
Member
paulmelnikow commented on 5 Mar 2018
So, for example, a 95% compatibility score between Rails 5.1.0 and Rails 5.1.4 would mean 95% of people who updated from Rails 5.1.0 to Rails 5.1.4 had all of their tests passing with no code changes required. Could be a useful thing for dependency authors to put in their changelogs, as well as to be included on Dependabot PRs.

That sounds like it would be really useful! A great use of a badge too, since that data changes over time.

We do have a great tutorial for adding badges, if you're up for taking that on.

@greysteil
 
Contributor
Author
greysteil commented on 6 Mar 2018
We do have a great tutorial for adding badges, if you're up for taking that on.

Totally up for that in a few weeks, when I've gotten on top of a couple of other things!

@chris48s chris48s mentioned this pull request on 6 Mar 2018
How do you add your own image to custom badges? #1548
 Closed
@PyvesB PyvesB mentioned this pull request on 6 Mar 2018
Updated contributing guidelines #1551
 Merged
@greysteil greysteil mentioned this pull request on 15 Jun 2018
Add [dependabot] SemVer compatibility badge #1734
 Merged
@greysteil
 
Contributor
Author
greysteil commented on 15 Jun 2018
Badge added in #1734, using the great tutorial. I've included the logo there, because it's move obvious than merging this separately.

Thanks for your help everyone!

@greysteil greysteil closed this on 15 Jun 2018
@MrSescon

 
 
Leave a comment
Nenhum arquivo selecionado
Attach files by dragging & dropping, selecting or pasting them.
Remember, contributions to this repository should follow its contributing guidelines and code of conduct.
 ProTip! Add comments to specific lines under Files changed.
Reviewers
@PyvesB PyvesB

Assignees
No one assigned
Labels
service-badge
Projects
None yet
Milestone
No milestone
Linked issues
Successfully merging this pull request may close these issues.

None yet

Notifications
Customize
You’re not receiving notifications from this thread.
5 participants
@greysteil
@shields-ci
@RedSparr0w
@paulmelnikow
@PyvesB)<a/>
    
- 💻 <b>Back-End</b>: 
    </br>
  <a href="https://nodejs.org/en/">![Node.js Badge](https://img.shields.io/badge/-Node.js-black?style=flat&logo=node.js&logoColor=339933)<a/>
  <a href="https://spring.io/projects/spring-boot">![Spring Badge](https://img.shields.io/badge/-SpringBoot-black?style=flat&logo=spring&logoColor=339933)<a/>
  <a href="https://spring.io/projects/spring-security">![SpringSecurity Badge](https://img.shields.io/badge/-SpringSecurity-black?style=flat&logo=spring&logoColor=339933)<a/>
  <a href="https://spring.io/projects/spring-data-jpa">![SpringDataJpa Badge](https://img.shields.io/badge/-SpringData-black?style=flat&logo=spring&logoColor=339933)<a/>
    
<!-- - 💻 <b>Mobile</b>:
    </br>
  <a href="https://reactnative.dev///"> ![React Native Badge](https://img.shields.io/badge/-React_Native-black?&style=flat&logo=react&logoColor=61DAFB)<a/>
  <a href="https://expo.io/"> ![Expo Badge](https://img.shields.io/badge/-Expo-black?&style=flat&logo=expo&logoColor=4C35E3)<a/>
  <a href="https://redux.js.org/"> ![Redux Badge](https://img.shields.io/badge/-Redux-black?&style=flat&logo=redux&logoColor=61DAFB)<a/> -->
    
- :gear: <b>Cloud</b>: 
    </br>
  <a href="https://www.docker.com/"> ![Docker Badge](https://img.shields.io/badge/-Docker-black?style=flat&logo=docker&logoColor=blue)<a/>
    
- 🗄️ <b>Databases:</b>
    </br>
  <a href="https://www.postgresql.org/"> ![PostgreSQL Badge](https://img.shields.io/badge/-PostgreSQL-black?style=flat&logo=postgresql&logoColor=blue)<a/>
  <a href="https://www.mongodb.com/"> ![MongoDB Badge](https://img.shields.io/badge/-MongoDB-black?style=flat&logo=mongodb&logoColor=339933)<a/>
  <a href="https://www.microsoft.com/pt-br/sql-server/sql-server-downloads"> ![Oracle Badge](https://img.shields.io/badge/-Oracle11g-black?style=flat&logo=oracle&logoColor=c21325)<a/>
      
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MrSescon&theme=default&show_icons=true&hide=issues&hide_border=true" alt="magnoSescon" />
</p>
