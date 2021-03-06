# Fedora Happiness Packets - Google Summer of Code 2018

* Project link: https://pagure.io/fedora-commops/fedora-happiness-packets/
* Site: https://happinesspackets.fedorainfracloud.org/
* Commits: https://pagure.io/fedora-commops/fedora-happiness-packets/commits?author=ms.annaphilips@gmail.com
* Bonus commit:
https://github.com/Algogator/mozilla-django-oidc/commit/106eea57735af0fd0e5bfbcef4bb26365d4e828f
* Blog posts: https://blog.annaphilips.com/category/gsoc/feed/
* FLOCK 2018: https://blog.annaphilips.com/flock-2018/

Primary deliverables
------
**Done:**
* Push the application upstream
* Add back-end support for Ipsilon authentication: 

   https://pagure.io/fedora-commops/fedora-happiness-packets/c/23227b73439cb3b0c306a320eb7c883250b934e6?branch=master
   
   https://pagure.io/fedora-commops/fedora-happiness-packets/c/8127e6668dbefd71f316c67bf8dbd9a535aff759?branch=master
   
   https://pagure.io/fedora-commops/fedora-happiness-packets/c/21973341c838145f5a87c4e90257396d4d76f2ce?branch=master
   
* Integrate fedmsg publishing - https://pagure.io/fedora-commops/fedora-happiness-packets/c/c0b7d04dffcc478ebf73c66f7c46cd9ea2fd6c77?branch=master

* Usability testing at FLOCK 18 - https://pagure.io/fedora-commops/fedora-happiness-packets/issue/44

**TODO:**
* Create Fedora Badge rule file to automatically award badge - https://pagure.io/fedora-badges/issue/627

Secondary deliverables
------
**Done:**
* Explore major social media APIs (for example, Twitter, Facebook, Reddit) to allow sharing on social networks

   https://pagure.io/fedora-commops/fedora-happiness-packets/c/b49f7df96b67fe73b78bad9263d7eab6af030ee4?branch=master
   
   https://pagure.io/fedora-commops/fedora-happiness-packets/c/22c8a87bc8b6acc3376239af1942f644a7dab1a3?branch=master
   
   https://pagure.io/fedora-commops/fedora-happiness-packets/c/6b2c4ea19b05773aca1b684fb7d5b212533bca2d?branch=master

**TODO:**
* Add support for video messages - https://pagure.io/fedora-commops/fedora-happiness-packets/issue/29
* Add support for emojis - https://pagure.io/fedora-commops/fedora-happiness-packets/issue/30
---
    
1. What was the problem/challenge/feature/goal you set out to solve that defined your project.
    
    Open source communities work because of the time and effort put in by volunteers and a heartfelt thank-you can go a long way. We all know the benefits of practicing gratitude (even in the workplace) yet we don't do it as often as we should. A recent study shows that people underestimate the impact their positive appreciation has on its recipients; they feel too awkward or question their competency in delivering their message of gratitude to the other person, and this in turn could discourage them from doing it in the first place. This is where Happiness Packets comes in, Fedora Happiness Packets is an open source platform to spread gratitude and appreciation among contributors in the community. For Fedora appreciation week, setting up Fedora Happiness Packets will encourage and make it easier for people to send positive feedback to their peers (anonymously if they like). 

3. How did you solve it?  What was the process like?  What worked well, what didn't?  What did you learn?
 
   We wanted to integrate Happiness Packets into the Fedora ecosystem to make it easier for Fedora contributors to submit Happiness Packets. One way we would do this is to allow users to login with their FAS (Fedora Accounts System) IDs and create a new Fedora badge to reward contributors who send a Happiness Packet. 
 
   During community bonding period I did some reading up on Django, not a lot of Fedora projects use Django (Flask seems to be the standard), and attended the weekly CommOps meeting. I was rushed for the first evaluation but made all the contributions in time luckily. When we made the proposal, I was advised to not bite off more than I could chew and to leave some buffer days for "unexpected events", which I'm glad I did. 

   The second half of GSoC, went a bit more smoothly, I knew what was expected of me, planned my time and work better and I knew where to search for answers. Worked mostly on the deceivingly simple fedmsg and  explored Postgres, Nginx and Gunicorn. 

   Spent the final weeks mostly deploying everything to production and catching up on tickets, writing reports, running to Houston for the VISA and usability testing at FLOCK where we did 1 on 1 interviews with attendees. We gathered feedback on what can be improved before launch at Fedora Appreciation Week.
   
   **What worked well:**

      Having two awesome mentors who are active in the community with "friends" on the inside and can direct you to people who can help you if they can't. Jona and Bee brought their own unique style of mentoring which helped me at various stages of GSoC. The weekly calls kept me on my toes and they were always patient with my questions on IRC. These past three months I have been pushed out of my comfort zone: giving my first talk at a conference, Getting my code reviewed for the first time, collaborating remotely with people in different time zones and writing blog posts.
    
   **What I could have done differently:**

      During the community bonding period I restricted my interactions to the CommOps team, when I should have been bonding with the wider community, especially the infra and design team, since I had to open some tickets with them. I wish I had done a mini usability testing session before GSoC started, the one we did at FLOCK was eye-opening and there were a lot of good ideas I would have liked to work on for the summer.  
      
4. What's next for you? In Fedora? In general?

   I plan to work on the feedback we received at FLOCK 2018, to have the site ready for Fedora Appreciation Week and in the mean time submit a proposal for Fedora Women's Day.

