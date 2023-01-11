# Syllabus {-}

**Course:** ENST/MRNE 222 Environmental Data Science Spring 2023 
**Class time and location:** Mondays and Wednesdays 8:05 - 9:20 Anne Arundel North 111  
**Lab time and location:** Wednesdays 1:10 - 4:20 Anne Arundel West 209  
**Instructor:** Dr. Cassie Gurbisz  
**Email:** cbgurbisz@smcm.edu  
**Office location:** Kent Hall 308  
**Office hours:** Tuesdays 11:00-1:00  
**Website url:** https://enst222.github.io/website/

## Course description {-}
Today's environmental challenges are increasingly complex and involve vast amounts of data. With technological advances that make environmental measurements cheaper and easier and open science tools that make data more accessible, the environmental field could even be described as “drowning in data.” In this course, students will learn how to use tools from statistics and computer science to gain insight from environmental data without "drowning" in it. We will draw practical real-world meaning from complex datasets by interpreting our analyses in the context of previous environmental or marine science coursework. Throughout the course, we will use literate programming and version control tools to ensure that our analyses are reproducible and accessible. We will do all of this using [R](https://cran.r-project.org/), one of the most popular and in-demand statistical programming languages in the environmental and ecological fields.

## Course materials {-}
All of the readings and software in this class are free and publicly available. There are free online versions of all the textbooks, and R, RStudio, and GitHub are also free. Two information sources which we'll use most frequently are:

* [R 4 Data Science](http://r4ds.had.co.nz/)
* [Introduction to Modern Statistics](https://openintro-ims.netlify.app/)

You'll need to bring a laptop to class and lab every day. Make sure to also bring a charger. If you don't have a laptop, please talk with me so we can get you a loaner.

For computing, we'll be using Posit Cloud (formerly RStudio Cloud), which lets you access RStudio and all of the packages we'll need right from your browser. Although R and RStudio are freely available to download onto your computer, working from a central cloud version ensures that we spend our class time learning to code rather than trouble shooting software issues. All of your work should be done in our class Posit Cloud RStudio workspace. You should receive an email invite to join the workspace. You can also request to join using [this link](). 

I do recommend that you [download R and RStudio](https://rstudio-education.github.io/hopr/starting.html) onto your computer at some point during the semester since you won't have access to our cloud workspace after the course ends. You might also want to get your computer connected to GitHub so you can ask for help if you run into any problems. [happywithgitr.com](https://happygitwithr.com/) has very good instructions - be sure to follow them carefully and don't skip any steps.

## Learning outcomes {-}
At the completion of this course, students will be able to gain insight from environmental data **reproducibly** and **collaboratively** using **modern programming tools and techniques**. 

Specific outcomes include being able to:

* visualize environmental data using `ggplot2`
* wrangle and tidy data tables using `dplyr` functions to generate a suitable dataset for analysis
* use functions and iterative programming to automate analysis tasks
* define research questions and hypotheses
* construct statistical models to quantify patterns and make predictions
* interpret data in the context of prior knowledge in the environmental or marine science domains 
* communicate results and document code using RMarkdown documents 
* store data and code using a clean and clear system of organization
* use version control tools (Git and GitHub) to collaborate and share code

## Grading {-}
This is an "ungraded" course. I want you to focus on learning R and developing your quantitative reasoning skills without the stress of losing points over minor mistakes. Mistakes are inevitable in this type of course. In fact, making mistakes and fixing them is the best way to learn! Furthermore, [research has shown](https://www.alfiekohn.org/article/case-grades/) that grading doesn't improve learning and can sometimes even harm learning. Rather than submitting work to me "in exchange" for a letter or number grade, you will self-evaluate most of your assignments by comparing them to the provided solutions documents. In addition, your peers and I will provide qualitative feedback on your projects. This should help you think intentionally about what you're learning, what you're struggling with, and what you need to do to maximize your learning in the course. Hopefully, this will spark your inner motivation to do your best work. Brief learning reflections will be an important component of most assignments. Periodically throughout the semester, you will also submit more substantial learning reflections in which you give yourself a grade based on your progress in the course (since we still need to submit grades to the registrar at the end of the semester). We will meet individually at the end of the semester to discuss your overall progress. As the instructor, I have the final say in your grade. But I rarely find that changing a student's self-assessed grade is necessary - I trust your judgment.

## Assessment {-}

### Application exercises {-}
Occasionally we will work on brief [application exercises](https://enst222.github.io/website/exercises.html) during class to practice new tools and concepts. These will be posted as assignments in our Posit Cloud workspace. When you open an assignment, Posit Cloud will make a copy for you. Your changes will be automatically saved and I'll be able to see your work. If you miss class, I will not check that you have completed the application exercises - they are mostly for demonstration purposes. But it would be a good idea to go through any missed application exercises to see how the tools covered that day work. 

### Labs {-}
[Labs](https://enst222.github.io/website/labs.html) afford us time to practice the concepts covered in class and work collaboratively on group projects. Some exercises will be relatively brief and can be completed during the designated lab time. Others will be more involved and may need to be finished for homework. Either way, lab assignments don't need to be submitted until the following Wednesday before the next lab. That way, you will have time to collaborate further, clean things up, revise, etc. if needed. 

However, please be sure to complete lab assignments by the due date. At the beginning of each lab, I will typically post a solutions document for the previous lab assignment so you can self-evaluate your work and ask questions. If you do need to submit an assignment after the deadline, I ask that you not look at the solutions until you have completed the work. The labs are designed to help you learn, so you won't be doing yourself any favors if you just copy the solutions! 

### Data challenges {-}
Whereas labs typically involve guided exercises to help you learn how to use a particular set of tools, we will have two take-home, open-book [data challenges](https://enst222.github.io/website/challenges.html) to assess your ability to use these tools without as much guidance. Think of the labs as riding a bike with training wheels and the data challenges as a way of demonstrating that you're ready to ride on your own. These should initially be done individually without any help from your peers so that we can assess your individual progress. A few days after each challenge deadline, you will have time in class to compare answers with your peers and work through any lingering problems. Then, as with lab exercises, I'll post a solutions document so that you can evaluate your own work and reflect on your progress.

### Group projects {-}
Finally, the course also includes two open-ended group [projects](https://enst222.github.io/website/projects.html) to demonstrate that you can ask a meaningful research question and apply the tools you have been learning to answer it using real environmental data. Keeping with our biking metaphor, you'll have the freedom to ride wherever you want to go, completely free of training wheels. You'll identify a topic with which you're familiar from previous coursework to ensure that you have the disciplinary grounding needed to interpret your analysis. You must complete the final projects and make substantial code contributions to your group's work in order to pass this course.

### Learning reflections {-}
Because this is an ungraded class, we will emphasize qualitative reflection to self-assess your learning. Most if not all of of your assignments will include a reflection component in which you think about what you learned through the assignment, what challenges you faced, etc. You will also write two more in-depth [reflections](https://enst222.github.io/website/reflections.html) during the semester to more broadly evaluate your progress in the course. It is very important that you put earnest effort into all of the reflections to show that you are thinking carefully about your learning in the absence of quantitative grades. 

## More information {-}

### Attendance and late work {-}
It is very important that you regularly attend class and lab. Everything we do builds on previously covered topics. So if you miss class or lab, you risk falling behind. I also know that life happens! If you need to miss class or lab, first make sure to communicate this with me. Then check the class [schedule](https://enst222.github.io/website/schedule.html) to see what you missed, review relevant slides and readings, and complete missed assignments on your own. If group-based project work took place, be sure to communicate with your team ASAP to come up with a plan for how you will contribute. Since this is an ungraded course, I will not automatically dock your grade due to absences. However, when you write your mid-semester and final learning reflections, you should carefully consider your attendance record - especially repeated absences - may have impacted your learning and, therefore, your grade.

I am similarly flexible about late work. If you need an extra day or two to complete an assignment, just ask - it's usually not a problem. However, you should think about the purpose of a particular due date and how a late submission will affect your learning. In the case of projects, a late submission might mean you will miss the opportunity to get feedback on your work. For assignments and data challenges, you might miss the chance to work collaboratively with your peers to solve stubborn data or coding challenges. You should take these learning opportunities into consideration before requesting an extension.

### Engaged learning {-}
SMCM has recently decreased the amount of time allocated to class meetings. To maintain the rigor of our 4-credit courses, students are expected to spend time outside of normal class meeting times engaging with course material. In this class, students can expect engaged learning to consist of coding exercises and collaborative group work completed during lab sessions.

### Office hours {-}
Office hours are set times dedicated to students. This means that I will be in my office waiting for you to come by talk to me. If you have a straightforward coding question, it's usually easiest to address during lab. Office hours are better if you want to talk privately, or you have a more in-depth coding question.

### Sharing / reusing code and academic honesty {-}
A huge volume of code is available on the web to solve any number of problems. This is one of the fabulous things about R. So unless I explicitly tell you not to use something, the course’s policy is that you can - and should - make use of online resources. In fact, an important part of learning R is learning how to search the internet for coding solutions. With that being said, you should be mindful of the difference between applying an online solution to a coding problem and copying a complete analysis and calling it your own. While the former scenario helps you learn, the latter detracts from your learning and is considered plagiarism. I trust that you can distinguish between the two. Students should be familiar with the official SMCM academic policies as outlined in the Course Catalog. You may also read the Student Handbook [To the Point](http://www.smcm.edu/tothepoint/wp-content/uploads/sites/71/2015/08/student-handbook.pdf) to acquaint yourself with college guidelines and regulations.  

## SMCM resources {-}

**Accommodations and Accessibility**: SMCM is committed to providing access to the learning and living experience to students with disabilities and disabling health conditions. If you have received a letter from the Office of Accessibility Services (OAS), which outlines the academic accommodations to which you are entitled to and you want  those accommodations to apply to this course, you MUST share your letter and meet with me to review that letter. If you suspect that you have a learning or living need related to a disability or disabling health condition that could benefit from  accommodations, you should contact the Office of Accessibility Services, who can help you learn more about how to proceed. Email: adasupport@smcm.edu

**The Wellness Center**: If you find yourself struggling with your mental or physical health this semester, please let me know.  I am one of many people here at SMCM who care about you and your welfare. The Wellness Center (240-895-4289) provides numerous confidential health and counseling services including same day/next day connections to counseling by calling 240-895-4289 or emailing the Director at jljolly@smcm.edu. To learn more about Wellness Center Services please go to their webpage at https://www.smcm.edu/wellness/

**Office of Student Support Services**: The Office of Student Success Services (OS3) provides free tutoring services and academic coaching with professional staff and Peer Academic Success Strategies (PASS) Specialists. You may drop into the PASS office in 230 Glendening for walk-in appointments on Mondays 11:30-1:00 and Tuesdays 4:30 to 6:00. You can also email PASS@smcm.edu. For tutoring for a specific course, please email your request to tutoring@smcm.edu. For any other help call 240-895-4388 or email os3@smcm.edu.

**The Writing and Speaking Center**: Located on the first floor of the main Library, the Writing & Speaking Center offers free peer tutoring in writing and speaking. The peer tutors are students themselves, but they have completed extensive hands-on training to learn how to assist their peers at any step of the process (planning, drafting, or revising) for any writing or speaking assignment. The peer tutors will not make decisions about revision for you and will instead work collaboratively with you to discuss ideas and consider options so that you can choose how best to revise on your own. This collaborative approach is one of the best ways to help students develop their abilities because all writers and speakers need audiences—just ask the peer tutors, who often schedule tutorials with each other. To make an appointment, please visit www.smcm.edu/writingcenter and click the “Schedule an Appointment” button. If you have questions or need assistance, please contact Director Ben Click at baclick@smcm.edu.

**Office of Title IX Compliance and Training**: St. Mary's College of Maryland is committed to helping create a safe and open learning environment for all students. If you (or someone you know) have experienced any form of sexual misconduct, including sexual assault, dating or domestic violence, or stalking, know that help and support are available.
 
The College strongly encourages all community members to take action, seek support, and report incidents of sexual misconduct to the Title IX Office.  Under Title IX of the Education Amendments of 1972, I am required to disclose information about such misconduct to the Title IX Office.
If you would like to talk to a confidential employee who does not have this reporting responsibility, you can contact SMCM Wellness Center or Health Services at (240) 895-4289. 
 
For more information about reporting options and resources at St. Mary's College of Maryland and the community, please visit the Office of Title IX Compliance and Training.
