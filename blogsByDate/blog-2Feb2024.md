# Travis Lamberte - Dev Log is a Blog

## Date: 2/2/2024

## Title: Software Project that Didn't land a job! - Tilt3D

### Relevant Links: [Tilt3D!](https://travis.lamberte.com/tilt3dMenu/index.html)

I've been hashing over my journey to find a software job over the past 2 years, and I'm wondering what it is about 'me' that isn't 'hireable'?

I want to do several more blogs on this topic, and that is Software Projects that didn't land a job. There's a lot of prep to do in order to land a job in tech. From leaning the the basics of programming (what language to use and why, JSON, packaging, IDE's, package managers), technologies that are universal to software production environments like (Github, docker, kubernetes) and even how to interact with other programmers (scrum master, teams, CD/CI, UX/UI, mood boards). The list of stuff you need to know and know well goes on and on. But it's not only necessary to know all these things, you also have to show that you know them. So If you don't have a degree in CS (like me) and you don't have 5 years of experince (like me) then the best way to show off is with projects. And I'm not saying that projects are bad. I really like them. Its a way to flex the brain muscles, and to create something that didn't exist before. So in the early days of my coding journey I started developing some software projects that not only would show off my skills as a computer programmer would magically get me a job that I so desperately need. The very first project is Tilt3D written in JavaScript. Good old vanila JS.

I should first start by saying that I choose to study JavaScript because it's easier to build a project that can be distributed to a job seeker. What do I mean by this. When you have a website all the job seeker has to do is open the webpage in their browser. This is the easiest way to get your work in front of them, but for some reason I have no idea if it's working. So I leanred JS and build Tilt3D and threw it up on a static web page and put the link on my resume. What is Tilt3D? let's check it out.

When you go to the website you're greeted with a very nice 1980's style game menu. Isn't it nice?

![](../images/Tilt3D_Menu.png)

The game it's self is a table top skill based game modelled after Jenga in which a user has to use skill to get points. Here's a screen shot. of course if you want to play it you can it's online, free, and there's no ads.

![](../images/Tilt3D_Gameboard.png)

The technical:

The game is written in JavaScript, HTML, and CSS. I used the Vite framework, and ThreeJS to render the game pieces, lights, shadows, and environment and I used CannonES for the pyhisics engine. I don't want to make it sound like I'm some sort of smart guy, but all of this work is not easy, it requires a bit of skill. I really thought a recuiter would appreciate the amount of skill that I needed to have in order to build this project. There's saying that it taked a lot of work to make something look like it took no work at all. The tiles are simple cubes with textures applied to each side. I added 2 dozen different wood textures and applied the randomly to the sides of the blocks then added my lamberteDesign logo to the sides. The blocks are stacked in a way that they'll just settle in such a way that they settle with out the tower falling over. It may seem like the CannonES physics engine is has duplicated real world physics... but no. it's not even close. It's like another universe. There's free energy at play that's always trying to make the tower shake apart. Gravity on earth is harsh. Things fall so fast. No one would like it if I set the gravity in the game to real world gravity. It's not what you think it would be like. All of these things I had to experiment with and tweek until I had a working game.
