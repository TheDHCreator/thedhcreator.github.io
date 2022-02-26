---
layout: default
title: IMMERSE Log
---

### Week 1: April 26th, 2021

* **Monday**: Got computer set up and went through all the Linux tutorials.
* **Tuesday**: Set up VS Code and my Github website, did pushes about what I learned and did yesterday and today, and also installed Vivado.
* **Wednesday**: Had to reinstall and update Vivado onto my Linux machine. I also cloned the Ice Machine repository, went to Dr. Hawkins' Presentation, my Broader impact meeting, Bootcamp meeting and began the Git tutorials.
* **Thursday**: Worked from home today and tried setting up VS Code access on my PC, did more Git tutorials and installed Vitis/Vivado on my PC.
* **Friday**: Tried working on more errors initalizing Ice Machine, finished the Git/GitHub tutorials, and sent name and photo as a pull request to the CCL Website. After working with Jarom to get our Ice Machine make install to build successfully, we achieved that goal and ended the week on a high note! At home in the evening, I finally was able to connect to VS Code through my IP address, was able to connect to my Lab Machine (it no longer idles), and I read a little bit ahead on modules for Monday.

### Week 2: May 3rd, 2021

* **Monday**: Installed Vivado 2019.2 and 2017.2, went to Bootcamp meeting, and did more testing to get Ice Machine (now renamed to just BFASST) to work with some basic Verilog designs. We are still running into a few bugs with the Bistream Reversal tool not working properly. I finished out the day making a basic C/C++ program and going through them running in VS Code. I also began reading the modules for Make and CMake.
* **Tuesday**: Worked from home today. Had to reinstall Vivado 2020.2 again onto my PC. Spent the day working more with Prof. Goeders and Jarom on BFASST and FASM errors and finished reading through Make and CMake modules.
* **Wednesday**: Attended Bootcamp meeting and worked with Jarom on fixing errors in xray.py to hopefully have our first tests run 100%. I also learned about stdout and stderr and Python subprocess modules. We finished out the day changing the config.py file, I fixed some issues with my CAEDM SSH Keys, and Jarom and I got the add4 module to work and be equivalent after running through all the tools! Woo hoo!
* **Thursday**: Worked from home again today. I tested all the basic designs in BFASST and all equivalence checked out except for two designs: one being not equivalent because of a bug and the other producing an error. These errors are likely from bugs in the Fasm2Bels tool we're using. I finished the day working on the Make follow up activity.
* **Friday**: Attended Bootcamp meeting and made a new yosys_compare branch on the BFASST repo because the Xilinx branch was removed. I also started learning about the Yosys Synthesis Tool, worked on the CMake follow up activities, and got the first use of Yosys almost working.

### Week 3: May 10th, 2021

* **Monday**: Worked from home again today. Read and watched some Python tutorial videos, studied more of Yosys and rewatched the CMake lecture.
* **Tuesday**: Worked from home again today. I watched the Python Introduction meeting from yesterday that I missed and continued reading and watching more videos about Python. Will start Python application tomorrow when I am back in the Lab.
* **Wednesday**: Attended the DEEP DIVE Meeting, Student presentations and the Broader Impact meeting for today. I then went to the Bootcamp Meeting where we discussed Python packages, venv, and conda. I spent the rest of the day learning more about Yosys and doing Yosys equivalence tests for the basic BFASST modules. 
* **Thursday**: Worked from home again today. I rewatched the Python videos from Monday and Wednesday, learned more about the modules we are testing with Yosys and finished final website updates for the rest of the week.
* **Friday**: Did not work (helped move fiance into our new apartment and left back down to Arizona). I will be working remotely for the next two weeks in Arizona as I prepare and get married.

### Week 4: May 17th, 2021

(Working remotely from Arizona this week and next before my wedding)

* **Monday**: Struggled to get VPN to work so I just worked on my Summer Proposal.
* **Tuesday**: Finished my Technical Work/Broader Impacts Proposal and turned it in on Learning Suite. I also tested the Yosys Flow that Jarom designed to automate our modules with Yosys to make sure the ones that were working stayed working. All modules except the 16 and 32-bit adder are all still equivalent, now with the Yosys flow.
* **Wednesday**: Read through some of the Symbiflow modules to start brainstorming what I can update for my Broader Impacts Project.
* **Thursday**: No hours logged.
* **Friday**: No hours logged.

### Week 5: May 24th, 2021

(Working remotely from Arizona this week as well prior to my wedding)

* **Monday**: All I was able to do was start watching some Bootcamp lectures I had missed out on.
* **Tuesday**: Attended a meeting over Zoom with Jarom and Dr. Goeders to go over current BFASST bugs. Dr. Goders also introduced us to two new repos that we may want to start looking into more: Edalize and Fusesoc. I continued to watch some missed Bootcamp lectures.
* **Wednesday**: No hours logged.
* **Thursday**: No hours logged.
* **Friday**: No hours logged.

### Week 5: May 31st, 2021

* **Monday**: Holiday, no hours logged.
* **Tuesday**: Answered a few quick work messages for the week.
* **Wednesday**: Attended the DEEP DIVE Meeting, Student presentations and the Broader Impact meeting for today. Afterwards, I went to the FPGA Track meeting where Dr. Nelson went into great detail about Project XRay and FASM. Tried fixing my .bashrc File so I could work on testing the Edalize repo.
* **Thursday**: Attended a meeting with Jarom and Dr. Goeders to discuss Edalize, Fusesoc, and the state of the BFASST current bugs.
* **Friday**: I tested an add4.py module with Edalize after finally fixing my .bashrc file and the test was successful. I also caught up on a few Bootcamp Modules and completed Python Packages and Environments and almost finished Python Packages II.

### Week 6: June 7th, 2021

* **Monday**: I finished Python Packages II and started working on my CSV Parser. After going to the FPGA Track Meeting, I kept working on my CSV Parser and began looking at Pytest.
* **Tuesday**: I continued working on my CSV Parser and continued watching videos about Pytest and the Github CI.
* **Wednesday**: Today, I attended the DEEP DIVE Meeting and Student presentations. There was no Broader Impact or FPGA Bootcamp meetings today. After the meetings ended, I worked from home the rest of the day and caught up on a few things I was falling behind on.
* **Thursday**: Worked from home again today. I researched more about the CSV Parser and kept watching the last few lecture videos.
* **Friday**: There was no FPGA Bootcamp meeting today. I tested one of the bugs that Prof. Goeders fixed and now the 16-bit and 32-bit adders just show Not Equivalent. I finished watching all remaining lectures that I missed but I still haven't been able to finish my CSV Parser. I have been struggling with that a lot. I hope to finish it when I return from my honeymoon.

### Week 7: June 14th, 2021

(On honeymoon until June 22nd)

* **Monday**: No hours logged.
* **Tuesday**: No hours logged.
* **Wednesday**: No hours logged.
* **Thursday**: No hours logged.
* **Friday**: No hours logged.

### Week 8: June 21st, 2021

(on honeymoon until June 22nd)

* **Monday**: No hours logged.
* **Tuesday**: No hours logged.
* **Wednesday**: Attended the DEEP DIVE Meeting, Student presentations and Broader Impact Meeting. After that, I attended the last (for now) FPGA Bootcamp meeting where Professor Goeders discussed the many cool facets of Vitis in converting C code to Verilog hardware. I did some pulls into BFASST to see what was done while I was gone on honeymoon and I contacted someone to see if I can get a position to help on Chip Camp next week. 
* **Thursday**: I went in depth on the Project X-Ray today and started brainstorming how I could make that page on the Bootcamp Website even better. I started following the steps to get the repo on my machine.
* **Friday**: No hours logged.
### Week 9: June 28th, 2021

* **Monday**: Started the morning by making small logistical changes to the SymbiFlow pages I'm in charge of for my Broader Impacts Project (setting them up organization-wise so it will be easier to update later). Met with Professor Goeders and Jarom to discuss the current state of our project. Kept learning about Project X-Ray and the other pages.
* **Tuesday**: Worked on the Circuits Module for Chip Camp all morning and afternoon. Started watching a few of the FPGA Track videos I missed while on honeymoon.
* **Wednesday**: Worked from home today. Continued looking over all my Symbiflow modules to brainstorm changes for Broader Impacts Project. I also started reviewing the recent changes in the BFAAST branches.
* **Thursday**: Started the day by inspecting changes in the PUDC branch of BFASST and I learned about what pull requests are currently active with SymbiFlow. I worked at home for the rest of the day catching up on FPGA videos and making a few more changes to my pages.
* **Friday**: Worked from home today. Was finally able to finish my CSV Parser over Zoom with the help of Jessa Locey. Still need to add Sphinx documentation to it but will do that next week. I wrote down my plans for all my SymbiFlow pages and pushed them to the Bootcamp Website to know what I plan to update on them over the next several weeks. Planning on working with Jarom for a PUDC test so the current SymbiFlow pull requests can hopefully go through next week. Will also start preparing Presentation slides next week.

### Week 10: July 5th, 2021

* **Monday**: Holiday. No hours logged.
* **Tuesday**: Worked together with Jarom for a while today on making a PUDC test for Fasm2Bels. Made .xdc and .pcf files for a basic AND2 module. Will have to finish tomorrow so the test can be added to the current PUDC Fix pull request for SymbiFlow.
* **Wednesday**: Met with Jarom and Professor Goeders to touch base on the status of current projects. After our meeting, Jarom and I finished the PUDC test and I pushed it to the Fasm2Bels pudc_fix branch. If approved, it will close Pull Request #63 in the SymbiFlow Fasm2Bels repo. Then, I worked from home the rest of the day making more modifications to the Project X-Ray page. Didn't want to push it until I had it more organized so I will push it tomorrow.
* **Thursday**: Worked from home today and was dealing with the current PUDC pull request on Fasm2Bels. Professor Goeders helped me rebase the repository but the golden files generated are still not passing the CI tests. Worked a little more also on Project X-Ray page. Hoping to push a finalized version by end of day tomorrow.
* **Friday**: Today was incredible! I worked on my final edits for the Project X-Ray page until Jarom arrived, and he helped me figure out why the test.sh still wasn't passing for PUDC. It turned out to be that the carry4 golden Verilog and XDC files were outdated and I had too many newlines at the end of the PUDC golden files. Once those were corrected, I pushed everything and Workflow #69 on the BYU Fasm2Bels repo declared both CI tests passed! Just waiting now for either Tim or Maciej to take a look, approve what I pushed and this pull request and bug will finally be closed. After that, I began working on my Technical Presentation slides and got over a third of them done and continued making updates to the Project X-Ray page. I pushed the first finalized half before I left for home and kept working on the slides from home.

### Week 11: July 12th, 2021

* **Monday**: Worked from home today. All I did was continue working on my presentation slides (my presentation is next week on the 21st). They are 2/3 of the way done now. I read more into FASM since that is the page I will be working on next after I finish the Project X-Ray page tomorrow.
* **Tuesday**: This morning I attended the BYU/SymbiFlow meeting where we met with Tim and others in charge of SymbiFlow, introduced ourselves and gave brief introductions on the projects we are working on and how they involve SymbiFlow. It was a really cool meeting to attend! After that, I went to the lab and finished my final changes to the Project X-Ray page. The next page I will make improvements on for my Broader Impacts is the FASM page. Then, I finished my Technical Presentation slides, worked from home the rest of the day, got feedback from Professor Goeders on my slides, and added and pushed three and2 designs to the BFASST Basic Designs directory. We now have twelve functional, passing and equivalent designs.
* **Wednesday**: Began the day with another meeting with Jarom and Professor Goeders to go over the current state of various pull request and other things BFASST related. I am going to be adding 2 basic BRAM designs and 1 basic ROM design to the basic design folder if I can get them to work. After the meeting, I attended the DEEP DIVE Presentation and the Student Presentations afterwards. Then, I had to reset my previous pull request to BFASST and I deleted the and2 designs that I added yesterday. Finally, I worked on the BRAM designs and found they were both running into Bitstream Reversal Errors. Will work more on finding out why tomorrow.
* **Thursday**: I kept working on the BRAM designs that I started yesterday and started practicing a bit for my presentation next Wednesday. I haven't been able to find out where the error is quite yet so I haven't pushed anything on the new branch I made.
* **Friday**: Debugging continues on the BRAM designs. I also added another branch with a basic ROM design. When I ran it in BFASST, it resulted in the same errors as the BRAM designs. I decided to push them to BFASST for the time being just so the branches could be tracked. I am hoping for them to be in working order come end of day Monday. On the agenda for next week, I plan on editing through the FASM page and pushing a finalized version by end of day Thursday, getting the ROM and BRAM designs to work in BFASST, I give my Technical Presentation on Wednesday and I am leaving for a short weekend trip Thursday evening and will be gone until Monday afternoon. I will work all my hours for the week before leaving Thursday.

### Week 12: July 19th, 2021

* **Monday**: I only worked for a short time from home today to rehearse my presentation for Wednesday with my wife.
* **Tuesday**: Kept working on BRAM and ROM designs. I think the AND2 designs that I removed somehow weren't removed so I need to redo that again. Still unsuccessful in figuring out why they currently aren't equivalent.
* **Wednesday**: Did final preparations for my presentation this morning, attended the final DEEP DIVE Meeting, and attended Student Presentations. I gave my presentation about BFASST second, was really nervous, and my slides accidentally got misformatted when they went up on the projector. I slightly panicked but still managed to get through it. Afterwards, I went home and worked remotely for the rest of the day learning more about Conformal and Yosys flows and if they were causing the BRAM and ROM designs to be not equivalent. They weren't. More digging to come.
* **Thursday**: Worked from home today to do more digging on BRAM/ROM designs. The pull requests to add them (though currently broken) into BFASST were merged. Professor Goeders recommended that I look through the conformal logs to figure out what was wrong and to compare all the primitives in the regular and reversed netlists. I looked and they all appear to be the same, but the reversed on has more. I hope to get to the bottom of this issue soon. Wasn't able to work on the FASM page as I had hoped for this week because I was stressing about my Technical Presentation. I am glad that's done. Since I didn't do the FASM page, I will do the FASM and bits2fasm pages both next week to make up for lost time. FASM 2 BELs and symbiflow-examples will be done in the coming weeks but before the Summer is over. Taking a quick weekend trip to go see family and wife's family, so I will not be working any hours tomorrow. I will be back on Monday afternoon and should be able to work a few hours that day. Will be back in the lab on Tuesday.
* **Friday**: No hours logged.

### Week 13: July 26th, 2021

* **Monday**: Just answered a few quick work messages while on the road.
* **Tuesday**: Attended the BYU/SymbiFlow meeting this morning where we gave updates on all our SymbiFlow related projects to some of the SymbiFlow owners. Jarom and I told them about the adding of more designs and about a new equivalence checking pull request he is working on. After that, I worked a little more on deciphering what's wrong with the BRAM/ROM designs and then had a meeting with Jarom and Professor Goeders on Zoom to discuss how our projects are coming along. We both shared our screens and we found out there is a black box module inside the Vivado generated netlist for the BRAM Single Port design (the one I'm tackling first of the bunch). I spent the rest of the day looking through the whole file to find out what's causing these errors.
* **Wednesday**: Did more investigating into the Conformal logs for the BRAM Single Port design. Because we didn't have a DEEP Dive Meeting today, I completely spaced Student Presentations. I also don't know if we met for Broader Impacts or not, but I feel awful for missing it if we did meet. With what I did work on, I kept looking into the Conformal logs with the help of Jarom to figure out what could be causing them to be not equivalent. I found that there are 3 unmapped key points in one of the netlists. I wonder if that is what's causing the issue. I spent the rest of the day working from home on finalizing the FASM Bootcamp page. I got all the text edited for clarity and began doing experiments with the Follow Up activity. I am likely going to keep it the same, but I need to test it as is right now to make sure it still works. More work on FASM page and BRAM tomorrow, maybe will even start the bit2fasm page.
* **Thursday**: I worked from home very briefly today learning more about bit2fasm. Looking up links and maybe a video that could be added to the webpage since it has a lot (and I mean a LOT) of just text.    
* **Friday**: I worked from home again today working on the FASM Follow Up Activity. As the current instructions are written, I'm not sure how to take the bitstream I generated and turn it into a readable FASM file. Still investigating where I'm going wrong. Didn't work as much as I wanted to this week but I will get the full 40 hours next week, will finish the FASM and bit2fasm pages and will do my best to finish the BRAM/ROM designs and have those committed. Much more to come next week.

### Week 14: August 2nd, 2021

* **Monday**: Jarom and I were planning on having a meeting with Professor Goeders through Zoom today to discuss current developments, but our assignments didn't move forward much so it was cancelled. Professor Goeders suggested that I run the Conformal GUI so I could better easily visualize where exactly the blackbox is that's giving me issues. I began researching that today. I also looked at the SymbiFlow and fasm2bels pages again and realized that they are all culminating together, each module building on its predecessor. I may need to rethink my approach when doing these final pages so that they all flow together more smoothly.
* **Tuesday**: Worked only a few hours from home today trying to get the Conformal GUI to work and learning about .do files.
* **Wednesday**: Went to the last of the Student Presentations for our track. There was no Broader Impacts meeting today. I am still working on the FASM page follow-up activity and trying to get the Conformal GUI to work so I can find where the blackbox is in the BRAM design that's currently "not equivalent." Since the FASM and bit2fasm pages are so closely tied together, I may turn my attention to fasm2bels and SymbiFlow examples and work on those next and save FASM/bit2fasm for last. I also went to the Digital Lab to find out if they had the Cadence Conformal GUI set up on their machines and I was unsuccessful. After returning home, I decided to start from scratch and make the bitstream again but with 2020 Vivado. After messing around with it a little more and running the FASM command, it worked! Eureka, it worked! I spent the remainder of the night organizing the FASM Follow Up Activities section. I plan to push the finalized version of the page tomorrow.
* **Thursday**: Worked from home today. I finished all my final updates to the FASM page and pushed everything up. I also added some links to the FASM2BELs page and did a few minor updates to the Project X-Ray page. Just waiting for Professor Goeders to merge that pull request. Then, I did some more digging into FASM2BELs to familiarize myself with some ideas for the FASM2BELs page. I spent the remainder of the day researching more about Cadence Conformal. My goal will be to try and get the GUI working by end of day tomorrow.
* **Friday**: Finally cloned the FASM2BELs repo to my own machine and went through the entire installation process while at home. When I came to the lab, I researched a bit more on how to get the GUI working, found a website and followed its instructions and it worked! I finally got the GUI working on my computer in the lab!! I went through the different aspects of the GUI as I searched for the black box module, and I found that it was actually the main BRAM instantiation that was the black box all along. My goal for next week will be to find out how to eliminate or patch it up so the BRAM and ROM designs can be finalized into BFASST by the end of the week next week. I spent the rest of my day working from home and familiarizing myself with some of Jarom's recent work while he's gone the next two weeks. I may finish the pull request for him if I can wrap my head around everything. Goals for next week is to get the black box taken care of, get the BRAM and ROM designs finalized into BFASST and finish most of if not all the remaining SymbiFlow pages. I have bit2fasm, fasm2bels and SymbiFlow examples remaining. A few more busy days are ahead before the summer wraps up!

### Week 15: August 9th, 2021

* **Saturday**: Answered a few quick messages about the upcoming week and read through more of the bit2fasm page.
* **Monday**: No hours logged.
* **Tuesday**: No hours logged.
* **Wednesday**: I found another (simpler) BRAM design that is checking out as equivalent through the BFASST tools, so I may see if I can find another ROM one too. There were no meetings today (those are done for the summer). I worked the rest of the day from home on trying to set up the GUI on my home PC, reading more about black boxes and running BFASST tests.
* **Thursday**: I spent a majority of my time today working from home and helping one of Dr. Nelson's students, Jason Prescott, with installing Project X-Ray and getting it's databases and parts to work. I also talked with him about Fasm2Bels and did some experiments for what the Fasm2Bels activity can become. 
* **Friday**: Worked from home again today on the Fasm2Bels follow up activity. I won't push any changes on the activity to the page until I get my version completely working. For next week, there are a few things I need to get done: I need to finish the bit2fasm, fasm2bels, and symbiflow-examples Bootcamp pages and I have to get my 2-page summary of my summer work done by Wednesday. I won't write that until I get get the SymbiFlow pages done. Those will be my first priority, then I will continue to get those BRAM/ROM designs working.

### Week 16: August 16th, 2021

* **Monday**: I met with Professor Goeders this morning to talk about the BRAM/ROM designs, the Cadence Conformal GUI and the remaining SymbiFlow pages. Jarom is still gone for another week so I am also gonna look into what he was working on (getting Yosys from Conda). Professor Goeders helped me look into the GUI a little more with the RAMB18E1 black box. I need to determine why that one is the black box. I spent the rest of the day working from home trying to get fasm2bels to work. Turns out there are more issues with trying to run its test-py script than we orginally thought. Will crack on it more tomorrow.
* **Tuesday**: Kept working from home today on getting fasm2bels to work first before doing any more work on the follow-up activities any further. Not a whole lot of success. I may not finish the fasm2bels page in time. I'll at least get symbiflow-examples and bit2fasm finalized and sent out before I submit my Summer Work Summary tomorrow. 
* **Wednesday**: Worked from home today writing up my Summer Work Summary and finishing the symbiflow-examples and bit2fasm pages. I couldn't finish fasm2bels like I had wanted today because there are still problems initializing the repository because either capnproto_java or RapidWright aren't connecting together properly or whatever else. I am still working on getting that squared off with Professor Goeders help. After getting some link problems settled, I submitted the finalized pages, finished my Summer Work Summary and uploaded it to Learning Suite. Jobs on deck for the next few days is investigating the Yosys inside conda, fixing the hopefully-not-so-broken fasm2bels, and maybe finishing its page as well. 
* **Thursday**: No hours logged.    
* **Friday**: No hours logged.

### Week 17: August 23rd, 2021

* **Monday**: Met with Professor Goeders and Jarom for our last meeting of the summer to discuss plans for the Fall, the current state of what we're working on, and making a few adjustments. I need to get fasm2bels working (and possibly send updates to SymbiFlow for their README.md file). I blew up what I was currently working on and tried using SymbiFlow's version since the BYU fork is many many commits behind. Spend the rest of the day working from home trying to get fasm2bels to work. Will try more tomorrow.
* **Tuesday**: I worked from home today but came forth with great success! I finally discovered the FASM2BELs problem: the paths were correct in the github workflow, but because I hadn't sourced the test.sh file it wasn't working. FASM2BELs finally ran test-py!! WOOHOO!!! I spent the rest of my day updating the official FASM2BELs README.md file with installation instructions (these will be used when I finish the fasm2bels module page) and made a pull request with those changes. It passed all the CI tests! I then went to the ECEn Ambassador meeting (which was offered to IMMERSE students and I'm so glad I got in!). A very good day, need to finish fasm2bels page by end of the week as my last part of my summer work.
* **Wednesday**: Today I spent some time filming with students for the IMMERSE promo videos. It was a really exciting feat! I cannot wait for the video to go public. Then, they came with me to the lab to get some B-Roll footage of me working on the BFASST project. I really think this will help students get more comfortable with projects like ours, including all other projects students are working on. I spent the rest of the day reviewing the comments of Tim and another SymbiFlow member and planning out how I am going to finish the fasm2bels page by Friday.
* **Thursday**: Kept working on fasm2bels issues, put the more in-depth install instructions on the fasm2bels Bootcamp page. I will see if I can bring the BYU/fasm2bels up to speed with SymbiFlow/fasm2bels tomorrow. 
* **Friday**: I synced up BYU/fasm2bels with SymbiFlow/fasm2bels as best I could, but I think I may have broken it since there may be a header missing. I got the first half of the final fasm2bels page pushed because I am not confident yet in the follow up activity I was planning. I can get fasm2bels to run, but I don't know if there should be more outputting in the terminal or not. I am a bit rushed for time today because I am helping the ECEn Ambassadors with NSO this afternoon and then have plans for the evening. I will do my very best to get everything related to fasm2bels fixed by tomorrow or Monday and have the bootcamp page finalized/merged by Monday. I'm sorry I didn't get it done like I thought I could by this afternoon.


## FALL 2021 SEMESTER BEGINS

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

## END OF 2021

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

* **Friday**:

### Week 10: March 11th, 2022

* **Friday**:

### Week 11: March 18th, 2022

* **Friday**:

### Week 12: March 25th, 2022

* **Friday**:

### Week 13: April 1st, 2022

* **Friday**:

### Week 14: April 8th, 2022

* **Friday**:

### Week 15: April 15th, 2022

* **Friday**:

### Week 16: April 22nd, 2022

* **Friday**:

## WINTER SEMESTER ENDS AND IMMERSE SUMMER 2022 BEGINS