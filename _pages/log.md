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
* **Thursday**: 
* **Friday**:

### Week 17: August 23rd, 2021

* **Monday**: 
* **Tuesday**: 
* **Wednesday**: 
* **Thursday**: 
* **Friday**:
