---
layout: default
title: IMMERSE Log (Fall 2021)
---

### Week 1: August 30th, 2021

* **Friday**: Didn't work too many hours this week, was getting adjusted to the new school routine. Was only able to experiment with Fasm2bels a little more, didn't get the page done and was waiting to schedule next meeting with Professor Goeders. Will get fasm2bels page done next week along with furthering its testing.

### Week 2: September 6th, 2021

* **Friday**: Got the fasm2bels page finally done this week (there were a lot of great updates done by Professor Nelson and Professor Goeders) and now there is a fasm2bels folder attached to the bootcamp website. Met with Professor Goeders on Thursday to catch up on what's going on (will meet with him again next week when Jarom can join us) and I did fasm2bels tests on designs from the FASM bootcamp page. Going to work on the BRAM/ROM designs next week.

### Week 3: September 13th, 2021

* **Friday**: Had to go back to the basics to figure out the issues BRAM/ROM were initially giving (spent so long on fasm2bels I kinda forgot all the issues). There are still unexplained black boxes. Had a meeting on Thursday with Professor Goeders and Jarom to discuss the current state of our projects. I haven't been able to figure out how to use the Xilinx files that contain the RAMB18E1 code and put that into cells_sim.v. I am going to keep working on this. Hope that both designs can be equivalent and fully working on BFASST by the end of the week next week. Much more hopeful good work to come.

### Week 4: September 20th, 2021

* **Friday**: I thought I would get more done this week but the black box issue continues. I finally routed the Xilinx RAMB18E1 file along with the cells_sim.v and it was no good. I will give it one more go on Monday and actually copy the contents of that file into cells_sim.v and see what happens at that point. Other than that, the IMMERSE dinner was Thursday night and it was a great more casual time with everyone. I will prioritize doing more time in the lab next week as opposed to at home.

### Week 5: September 27th, 2021

* **Friday**: The work of the BRAM/ROM designs continues. I worked more on it this week with the Cadence Conformal GUI, feeding in different versions of cells_sim.v and including the corresponding Xilinx BRAM file. Currently, the RAMB18E1 definition in cells_sim.v is removed and the Xilinx file is there to take it's place but now it is complaining of multiple clocks in the design and incomplete verification. The long process continues. I am also going to be reviewing a paper for Dr. Goeders hopefully during some lulls in Conference this weekend. I want these designs working and I want them soon. More updates to come next week.

### Week 6: October 4th, 2021

* **Friday**: This week was a good week. The Work of BRAM/ROM designs continues but there is progress being made. I am going to try and make my own definition of the RAMB18E1 to simplify it and feed it in to the cells_sim.v to see if that can take care of the black box and help with finally getting the designs to be equivalent. We also had our first CCL meeting in a while on Thursday for a grad student presentation. Our next meeting will be every other Wednesday. I will try my best to get these designs finally finished this week so we can work more on other facets of the BFASST project.

### Week 7: October 11th, 2021

* **Friday**: Another week gone by, a good one, but a quick one. The BRAM/ROM problems continue, but it's not the problems I was expecting. After doing some inspection on the impl files with Dr. Goeders, it was determined that there may be a problem with Vivado instead of Conformal where things are being assigned to constants instead of the proper memory addreses. That problem will need to be looked into more next week. We had our biweekly meeting with Dr. Goeders on Wednesday and discussed the current state of our projects. It was a very good and informative session. Things in the semester are getting crazier so it's harder to find the time to do the work, but it's not impossible. I couldn't attend the CCL meeting on Thursday due to committments with my wife. Hoping I can find this Vivado issue and fix it next week to get these designs one step closer to equivalency.

### Week 8: October 18th, 2021

* **Friday**: These weeks seem to be getting shorter and shorter. I did what I could this week to run these designs I'm having issues with through Vivado. Since my issues seem to be solely with Vivado now, I need to make sure that after going through Vivado that I run it with the right part, then run bit2fasm, then fasm2bels and then check for equivalency. I will be doing more of what I can on this next week. The CCL Meeting yesterday went very well. I am glad that we are still having them. And I'm thankful to still have this job. It was a long day today, and a long week. Things should get better, and these designs should hopefully be dealt with soon enough.

### Week 9: October 25th, 2021

* **Friday**: EUREKA!!! I finally was able to make headway on these designs for the first time since Summer! I kept looking for designs that could satisfy our BRAM cases for BFASST, but I was only finding ones that dealt with BRAM18. I found some designs that dealt with BRAM32s and they passed with Conformal! After feeding in the Xilinx files to see if they would be equivalent in Yosys they came out as such! I completely spaced the CCL meeting but I will go next week. Going to try and edit the Yosys script next week so that both of the new designs work just as well in Yosys as Conformal.

### Week 10: November 1st, 2021

* **Friday**: This week was all over the place. I wasn't able to get as much done on working on the Yosys as I wanted to. Classes were crazy and I could not for the life of me figure out how to edit the Yosys script. The script for testing things in Yosys on my CAEDM machine is much simpler and I understand that. I will have to look into it more next week. I went to the CCL Meeting and it was very good. Crazy week all around but progress is still achievable.

### Week 11: November 8th, 2021

* **Friday**: Another week has gone by and a lot of failed tests have shown me ways on how to NOT get the Yosys side of things working for the BRAM designs. I tried messing with the Yosys.py script and feed in the Xilinx definition files, tried replacing the definitions in cells_sim with the Xilinx ones, and still to no avail. My plan next week may very well be to make the simplest BRAM design I can and only test it in Yosys until I have it working. Then, I may be able to find why the bram_sp has 4 unproven cells and the bram_dp has 8. Time for another weekend. Freshman Ambassador/Professor Meet and Greet next week!!

### Week 12: November 15th, 2021

* **Friday**: This week was kind of a bust. I wanted to work on the yosys part of the BRAM files, but the only time I did was failed test after failed test after failed test. I am completely stumped as to if I should be changing the definitions in cells_sim to simpler ones, or the Xilinx ones, or starting with a new base simple design all together to see if I can address the problem. I think both designs face the same problem, just on a different scale. The Meet and Greet went very well and I think it will be come a tradition that the Ambassadors will host every year. School is also getting crazier so I don't know how productive I am going to be going forward for the next few weeks. I will try my best.

### Week 13: November 22nd, 2021

* **Friday**: The downward trend of work versus the upward trend of how much classwork I need to complete before the end of the semester is staggering. Because of the Thanksgiving Holiday I did not get very much work in this week. Any meetings were cancelled for the week except the SymbiFlow one, but there was nothing new to report. Hoping next week will be better.

### Week 14: November 29th, 2021

* **Friday**: This week was really similar to last week. I had to spend a lot of time on school work, and as a result, did not get to do very much more testing on the Yosys part of the BRAM designs. I feel like I've tried just about everything and I'm continuing to run into walls of no good results. I keep trying until I get this.

### Week 15: December 6th, 2021

* **Friday**: I only was able to put in a very little amount of hours this week because I was finishing my last school projects. Going to ask Dr. Goeders for recommendations on how to proceed at next week's meeting because this week it was cancelled. I'm going to get back into the groove but I feel bad for not working more the last few weeks. I will do better.

### Week 16: December 13th, 2021

* **Friday**: Finals have come and gone, and unfortunately, Jarom will soon be gone as well. This leaves me as the only one for this project until the summer time. We were able to have one more meeting with Dr. Goeders before we left and Jarom talked about his progress with the Yoysys equiv and his communications with the Yosys people. I now have a better idea of how to attack my problem and will do what I can next week.

### Week 17: December 20th, 2021

* **Friday**: Merry Christmas Eve! My process for working on this Yosys issue will be the following: I will run Yosys manually in a terminal and paste all the commands from the yosys.py script for one of the designs and follow each and every step until it breaks. I honestly don't know why I didn't go about it this way until now. I wasn't able to make as much progress as I wanted to since it is the week of Christmas, and I will be taking a small vacation next week with my wife to visit some relatives. Once the New Year and semester starts, it's gonna be a whole nother different ball game with classes and with this project. I hope I will be able to do it all and I am going to get this problem fixed one way or another and take over Jarom's work in the process. Merry Christmas to all, and to all a goodnight.

### Week 18: December 27th, 2021

* **Friday**: Did not put in any hours this week. Was visiting relatives for a short vacation.


This website is created using [Jekyll](https://jekyllrb.com/) and hosted using [Github Pages](https://pages.github.com/).