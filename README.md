# ManagersAndMorePegboard
A simple, bare-bones way to track which managers are in the office for the day.

Here's the deal: I currently work at a car dealership as a receptionist. I have calendars for when various salespeople are working, but *not* one for the managers. There are 10-12 people that I might take calls for but will need to track if I know they are in that day. There's nothing like getting an angry call from a customer that hasn't received a call back after they left a voicemail at a desk I transferred them to not knowing the person wasn't there that day.

We have a non-tech solution, a simple table on our bulletin board with pushpins next to names of people who are in. However, this takes 10-12 pushpins and makes Swiss cheese of our bulletin board. 

So I thought I would make a thing. A pegboard or pushpin board but on the front desk computer.

My problems:
-I am not part of the IT department
-I am not an admin on the front desk machine 
-I am not able/ allowed to download any programs onto said machine
-My guess is that making something that accesses information outside the company's network would be a violation of our IT policy
-The front desk machine is running Windows 7 Pro (not entirely relevant, but somewhat noteworthy)

So, I could just make a local file, right? In theory, yes. And I have. Using Notepad. And VSCode, while at home. I emailed the file to myself once, but since then I've simply used Github (accessed through an incognito window) to see the code in both places.

To keep security and privacy concerns to a minimum, this is what I have done:
-The names on Github are different than the actual managers (Master Detective Clue FTW)
-The code does not access *anything* outside the local machine:
  -No jQuery
  -No Bootstrap
  -No online database
  -**vanilla JS, CSS Flexbox, and local storage** *(not even cookies)*

I have done a *lot* of research (while answering phones).

As of 2/6/2020, the minimum viable product has been up and running for some time: There are buttons with each manager's name that change color when clicked and change back when clicked again.

But I want this to outlast me at this job, which means I need it to be able to be updated by people who are Not Me. 

I need a form. I need to generate buttons with id, text, and class from an array. I need to be able to update that array. And I need to make it all usable by people who don't know about alt+tab.

This is the challenge I have given myself.

In the meantime, and when I am done, all one should need to use this code for themselves is to:
1. Copy code into a Notepad file
2. Save file as .htm
3. Open file using Chrome (the only browser I've used so far)

Final note: as of 2/6/2020, I do not have the state of the buttons being saved into local storage, nor do I really plan to. My thinking is to keep the data usage small.

