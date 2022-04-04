---
layout: default
title: IMMERSE Log
---

If you want to see IMMERSE Logs for past semesters, click one of the options below!

[IMMERSE (Fall 2021)](https://thedhcreator.github.io/pages/log-fall2021/)

[IMMERSE (Summer 2021)](https://thedhcreator.github.io/pages/log-summer2021/)

## WINTER SEMESTER 2022 BEGINS

### Week 1: January 7th, 2022

* **Friday**: It was a good first week back, but not without its setbacks. I accidentally missed the CCL meeting yesterday because I thought they would resume next week, and I communicated with Dr. Goeders on when he and I will be meeting now that Jarom is gone. I did make a pretty decent amount of progress this week, however. I ran through some tests on the single port asynchronus BRAM design and found that with the original cells_sim definition, it wasn't equivalent because of extra things being included. A second definition (that right now I don't exactly remember where I got it) got through the entire process was there was still some unproven cells at the end. For next week, I need to figure out where I got that newer and smaller cells_sim definition and hopefully in the next week or so finally get these designs up to speed and pushed out so I can get working on whatever phase of the project is next.

### Week 2: January 14th, 2022

* **Friday**: It was another great week! I jumped right back into the work and I have a brand new game plan when it comes to my work for the semester. I have taken over what Jarom was working on with equivalence checking. It turns out what he was working on is going to be essential for our equivalence checking process moving forward. My current plan now is to update the yosys scripts to use equiv_struct and to get all our current basic designs to get up to speed and back to equivalent with this new process. If I can get it with them, I can get it (hopefully) with the BRAMs. I met with Dr. Goeders this week to discuss this new game plan and it seems like it is a very good one. I accidentally missed the CCL meeting again, but I will not miss the rest going forward. SHREC is next week and I may attend for a few hours at a time during the few days. So mucb good work is coming, and I feel like I'm back on top of things for the first time in a while. Hopefully the Yosys people will respond as to how I can update our Yosys script further to encompass all the designs with the equiv_struct/equiv_simple method. We shall see what next week brings.

### Week 3: January 21st, 2022

* **Friday**: Pretty good week if I have to say so myself. After being in communication with some folks at Yosys, I now have a functioning script using equiv_simple and equiv_struct that proves equivalence for our 3 most basic designs. The ones with registers/reset signals still have yet to prove equivalence so I will still work on that. Attended a bit of SHREC this week on my own and during the CCL meeting which went great. I accidentally forgot to clock out after finishing up my work week last night so I have to get that taken fixed. I will be more responsible and less forgetful when it comes to my time card in the future.

### Week 4: January 28th, 2022

* **Friday**: A bit of a slower week, but that is all right. I have yet to hear back from the Yosys people on the add4_r and add_r_rst designs I sent them so hopefully they respond back soon with changes to the script to prove design equivalency. Meeting with Dr. Goeders went very well this week. By our meeting next week, I am going to try to look at the BRAM designs a little closer and get the Yosys script to show the actual designs in images. I have yet to still figure that out. Once I get those working I will keep working on updating the new Yosys script so all designs will be passing soon. Next week will be crazy, but I'm looking forward to it.

### Week 5: February 4th, 2022

* **Friday**: I didn't write this update last Friday, but I am writing it today. Last week, hardly anything was accomplished. I finally heard back from the Yosys people on Monday about a working script for add_4_r. I replied and asked them if there was a version of this ongoing script we've been working on that could account for all of our designs and also ensure a better form of equivalence checking overall with equiv_struct. Waiting to hear back from them still. I got COVID last week so my productivity went in the toilet and nothing really else got done. I am feeling better as of writing this (2/7) and this upcoming week will go much better.

### Week 6: February 11th, 2022

* **Friday**: Things returned back to proper form this week. I was out of quarantine, I got back to a full 20-hour work week, and I think the new equivalence checking script is almost finished. I didn't get to meet with Dr. Goeders because he had other meetings during our normal time. However, I did attend the CCL meeting, and it was really fun and informative! I hope the Yosys people reply to my inquiry about a one-size-fits-all script for our designs, and if they do, there should be an updated yosys.ys file pushed to BFASST by end of next week. Also, I found out today that my pay was raised to 15 bucks an hour, and that's incredible!!! I am so so thankful for whoever made this change, and it is going to be a huge blessing for me going forward. I will not waste this wonderful opportunity to work even harder.

### Week 7: February 18th, 2022

* **Friday**: Another good week for the books. Because of its business, Dr. Goeders and I actually forgot to meet, but that's okay. We had plenty of communication throughout the week about which direction our current part of the project should go. Because of our new plans (figuring out how to make all netlists contain LUT6s so equiv_struct can actually work), the issue with Yosys from the last few months was finally closed tonight. Since I have been doing work on the bram branch, I am making a new equivalence checking branch where more work will be done. CCL meeting was great on Thursday as always. I likely won't work next Monday so I can take the day off. Until next week.

### Week 8: February 25th, 2022

* **Friday**: A little strange week because of its shortness, and it was pretty crazy. Our CCL meeting was unfortunately cancelled, and because of exams and papers due this week for me, I wasn't able to meet with Dr. Goeders. However, before the week concluded, I sent him over the different LUT strucutres of three of our different designs. Starting next week, we will go through them and determine how best to revamp our Yosys equivalence checking script for the last time so all designs can work WITH equiv_struct as the main source of checking. I need to make sure I am focusing as much on my studies as I am on my work. I will do my best to keep doing better to find balanace.

### Week 9: March 4th, 2022

* **Friday**: March is upon us, and we are back to the regularly scheduled program. This week was very busy school-wise, and not much was done with the current sub-projects. However, a few good things still did happen. The CCL meeting was great as always. Dr. Goeders approved and merged my two pull requests: the current working version of the yosys.py script is now on a new branch and the basic folder got cleaned up. I also sent Dr. Goeders some of the netlists so we can compare them next week and figure out how to get equiv_struct to work with them. The work moves forward!

### Week 10: March 11th, 2022

* **Friday**: The weeks seem to keep counting down quicker and quicker, don't they? Changes made by Dr. Goeders were merged into BFASST master this week, including a final version of our yosys.py script (for now) because we need to work on fixing errors in larger designs. The CCL meeting was a good practice run for Corey, and I went to his thesis defense today. Dr. Goeders and I were unable to have a regular meeting again, but we communicated through Slack about what I need to do next. I am to go back where Jarom left off on Fasm2bels CI tests for more designs and pick up the work there. I investigated a bit of where I am to begin next week. IMMERSE Summer 2022 is fast approaching!

### Week 11: March 18th, 2022

* **Friday**: I was able to explore more of the future designs and started running some scripts in conformal to see if they were already equivalent with no changes. So far, every design in the bubblesort folder and the counter folder in the base directory are equivalent! Eureka! Dr. Goeders was out of town for the radiation testing trip, so we weren't able to have our one-on-one meeting, but I was able to go to the CCL meeting. I am going to ask him about if there are other things he wants me to do with the fasm2bels CI stuff or if we just want to work on getting more designs to be equivalent. Till next week!

### Week 12: March 25th, 2022

* **Friday**: There was some return to normalcy this week. After running extended tests with Conformal and Yosys just with the verify fasm2bels yaml files, I discovered that many designs in the base folder, when using Conformal, are already equivalent! When using Yosys, many are not equivalent, but we are working on that. I was able to finally meet with Dr. Goeders once again this week and discuss for a bit what we should do next. I am going to work on doing fasm2bels CI tests for an 8 to 1 MUX and a UART transmitter. Jarom did a 32-bit adder on the Symbiflow/fasmbels repo many months ago, so I am going to follow the same pattern he did with the MUX first and then the transmitter next. I started looking for MUX designs, and hope to have those tests completed by the middle of next week. Things are getting crazier, and Summer IMMERSE will soon begin. Until next week.

### Week 13: April 1st, 2022

* **Friday**: This week was one of struggle, and that's not an April Fool's joke. I looked into how Jarom added tests on the fasm2bels page for our 32-bit adder design, and I viewed past Slack messages with him to figure out how to begin the process. I also scowered the web for an 8 to 1 MUX design, since that is the one I'll be working on first. I ran into issues with my Symbiflow repos, not knowing if the one I have cloned is our fork or the actual fasm2bels fork. I am going to figure that out. There was no CCL meeting this week and no personal meeting with Dr. Goeders. Finals are ramping up, and so is Summer IMMERSE 2022. I will do my best to do what I can to get these new fasm2bels test done. Now, on to General Conference!

### Week 14: April 8th, 2022

* **Friday**:

### Week 15: April 15th, 2022

* **Friday**:

### Week 16: April 22nd, 2022

* **Friday**:

## WINTER SEMESTER ENDS AND IMMERSE SUMMER 2022 BEGINS