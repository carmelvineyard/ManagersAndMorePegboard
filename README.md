# ManagersAndMorePegboard
A simple, bare-bones way to track which managers are in the office for the day.

Here's the deal: I currently work at a car dealership as a receptionist. I have calendars for when various salespeople are working, but *not* one for the managers. There are 10-12 people that I might take calls for but will need to track if I know they are in that day. There's nothing like getting an angry call from a customer that hasn't received a call back after they left a voicemail at a desk I transferred them to not knowing the person wasn't there that day.

We have a non-tech solution, a simple table on our bulletin board with pushpins next to names of people who are in. However, this takes 10-12 pushpins and makes Swiss cheese of our bulletin board. 

So I thought I would make a thing. A pegboard or pushpin board but on the front desk computer.

My problems:
- I am not part of the IT department
- I am not an admin on the front desk machine 
- I am not able/ allowed to download any programs onto said machine
- My guess is that making something that accesses information outside the company's network would be a violation of our IT policy
- The front desk machine is running Windows 7 Pro (not entirely relevant, but somewhat noteworthy)

My solution: a local html file. Written using Notepad, VSCode, and GitHub.

To keep security and privacy concerns to a minimum, this is what I have done:
- The names on Github are different than the actual managers (Master Detective Clue FTW)
- The code does not access *anything* outside the local file:
  - No jQuery
  - No Bootstrap
  - No online database
  - **Only vanilla JS and CSS Flexbox** 

I have done a *lot* of research (while answering phones).

As of 2/6/2020, the minimum viable product has been up and running for some time: There are buttons with each manager's name that change color when clicked and change back when clicked again.

For this to outlast me at this job, it'll need a form. I need to generate buttons with id, text, and class from an array. I need to be able to update that array. And I need to make it all usable by people who don't know about alt+tab.

That, however, is a project for a different repository, as I'm not sure how to do it without using local storage at a minimum.

