# CISC4900_Log
Nafisa Anzum and Sabina Ismailova

Week#	| Week Starting	| Progress
------|---------------|---------
1	| 8/20/23	| - Attend orientation meeting and form group. 
2	| 8/27/23	| - Start with a project idea for the course and set up github repos and trello table to keep track of tasks. 
3	| 9/3/23	| - Fill out the forms about project ideas and submit them.
4	| 9/10/23	| - Get offer from Allan to set up an internship with Wikitongues to complete the course and agreed.
5	| 9/17/23	| - Waiting on email back from Wikitongues about the onboarding and starting date. Onboarding meeting set to 09/27/2023.
6	| 9/24/23	| - Meet up with Daniel for onboarding and discuss what the workload is going to be like and what the next steps are. Got an email with the next steps and what to do while waiting to be fully onboarded. 
7	| 10/1/23	| - Assigned to set up MAMP and Wordpress on our computers and play round with the system to get an idea of the basic structure and how it works. 
8	| 10/8/23	| - Set up MAMP and Wordpress and getting an idea of how it works while waiting for the Zip file with the website wordpress files to be shared.
9	| 10/15/23	| - Wikitongoues zip file with wordpress website sent out and instructed to set that up and upstream it to the Wikitongues repo. Worked on setting up the Wikitongues wordpress files and successfully set it up, but faced an issue with upstreaming to the Wikitongues repo. Contacted Daniel for help with the upstreaming issue and provided with resources. 
10	| 10/22/23	| - Working on fixing the issue with upstreaming. Followed resources and faced most likely an access error when attempting to updtream. Getting ready to write up slides about the tasks assigned and working on a plan on how to go about it. (10/24) Got the upstreaming issue fixed by getting access rights to the wikitongues repo. Started working on the carousel scroll issue on the website main page. (10/27) <br>- We had a meeting with Daniel and spoke about the next steps. Nafisa had rewritten the entire custom.js even though she couldn't see the how everyhting changed. The scroll function stopped working as a result. Sabina had gotten the scrollbar to work and be dynamically changed. <br>- Daniel had given another assignment which is more on data cleaning and set up a meeting for Nafisa to meet Shahani, if Nafisa says no, Sabina will be connected to see if she wanted to do the work.
11	| 10/29/23 | 	- Nafisa had a meeting with Shahani regarding the data mining project and how would it go. She is thinking about how she would approach it before she agrees to the project. We had the Demo 2 meeting with AJ. He discussed on next steps for the internship itself as it is nearing the end of the semester. Sabina made a pull-request completing the jQuery to vanilla js conversion and the fix to make the carouselScroll() function dynamic. She had the carouselScroll() function fixed and was waiting for Nafisa to fix unrelated history issues with the repository and be able to push her changes before she proceeded. <br>- Sabina updated Daniel about the task being done and to look over the pull-request and confirm for merge. Daniel replied saying he had to travel and would get back to it. The Friday weekly check-in was pushed back to next week Tuesday because Daniel was traveling. Sabina was told to research and familiarize herself with PHP syntax and in-line PHP in preperation for the next project. The next project hasn't been discussed yet. Nafisa is researching about data mining to see if she can take up the new task she was introduced to by Shahani. 
12	| 11/5/23	| - Nafisa and Sabina met with Daniel on Tuesday. Nafisa updated with that she had contacted Shahani and her agreement with the data project. She has asked Daniel for further way to contact Shahani. Daniel moved on with Sabina and has discussed her next task. He had gone over the backend and how wordpress works, including where the necessary files are and how Sabina will be moving forward with her work. <br>- Sabina's new task is to make the homepage banner to be more dynamic in the fact that the image can change to another image instead of being static. Sabina is waiting on the team to test the PR for approval and was assigned a new task to make the homepage banner dynamic/variable(Tuesday, 11/7). <br>- This would make the banner change for every instance that the website is opened, picking an image from the array of images provided by the admin on the WordPress CMS. Worked with Daniel to get a user setup to access the WordPress site CMS(Wednesday, 11/8).Did research on the different data options provided by the ACF WordPress extension that the website uses to make custom pages(Thursday, 11/9). <br>- Adjusted the CMS to let admin select multiple images for the banenr instead of just one image. Made changes to the banner--main.php file to accomodate the array passed in by the gallery from the CMS(11/10). Faced some issues with testing the code as there were issues saving the added images in the CMS. Contacted Daniel to troubleshoot this. (11/10) We went ahead and started recording Demo 2 as well as editing and then submitting it.
13	| 11/12/23	| - Sabina got introduced to the new task on Wednesday 11/15. The task was to fix some issues with the hover effect of the nevbar on the Wikitongues website and deciding on whether it would be ebst to stick with pure CSS for the hover effects or implement them through Javascript. Looking over the code and working with the CSS, Sabina decided that it would be better to redo the implementation of the hover effects using Javascript. Sabina looked over the task and came up with a plan on how to go about fixing the hover effects. She went over the plan with Daniel on the weekly check-in on Friday 11/17 and asked clarifying questions. She started working on the implementation. <br> - Nafisa had tried reinstalling and following the docs for layout parser. Raul(the previous intern for Shahani's project) had contacted on (11/14) and discussed what he had completed so far and gave Nafisa more info on what she is actually completing   
14	| 11/19/23	| - Sabina was having issues combing through the files to figure out what lines of CSS were overriding her Javascript hover effect implementations and got a handle of that by 11/20. There was an issue while trying to replicate the effect that was desired because of the layout and spacing in the navbar. The navbar hover effects were mostly done except that she had to make some slight but noticible changes to the styling of the nav links and the dropdowns for the navlinks. She asked Daniel to meet and go over the hover effect that she implemented and to get feedback on her changes and if there is anything that she should change or do differently on Wednesday 11/22. <br>- Due to it being Thanksgiving week there was a slight delay and we ended up getting feedback during the weekly check-in on Friday 11/24. Sabina got some more pointers on what to change/add and got approval on the style changes she made in the processes of fixing and reimplementing the navbar hover effects. They agreed to meet again and go over the changes once she was done implementing the newly suggested changes and additions. <br>- Nafisa spoke with Daniel during Friday's meeting as well and discussed an alternate route in completing Shahani's task as some of the ideas presented by the previous intern does not work as there are deprecated dependencies. She has done an alternate code with other libraries that somewhat work but as Nepalbhasa is not recognized, it's hard to predict if it actually works. Daniel and Nafisa decided to try to see if they can parse through the pdf itslef and later run a code that divides the work.
15	| 11/26/23	| - Nafisa had downloaded Nepalbhasa onto her computer and is trying to work around as to why it is not working. <br>- Sabina got feedback from Daniel on the navbar hover effects task she was working with on Wednesday 11/29. She made final changes to make the navbar fade-in animation quicker, as suggested, and pushed the code into the codebase. Her PR is waiting on approval. During the meeting on Wednesday, Daniel also discussed Sabina's next project. The new project was to use PHP sessions to track when was the last time the user visited the website. If the user had not visited the website through a certain time interval, a banner with notifications would show up on the header. Her task for now was to see if the PHP sessions work and check back for more details on the banner element template once the PHP sessions work as expected.  
16	| 12/3/23	| - Sabina got the template for how the banner alert should look on Monday evening 12/04. She also got further instructions on where to set up the front-end and the backend for the banner alert. She started working on the front-end portion of the banner alert using dummy data and had a basic draft ready by Friday, 12/08 to show and go over details during the weekly check-in. The only part of the banner alert left now was the backend portion which she had to set up in WordPress and use PHP to navigate through the data. While finishing off the banner alert, she had a question to clarify what Daniel would like to be done once the user clicks the X-button on the alert. She is waiting to discuss the issue with Daniel. During the Friday check-in, it was also mentioned that Sabina would be getting a smaller task to complete by the end of the internship if she would be able to complete the banner alert task by the start of next week. 
17	| 12/10/23	| 
18	| 12/17/23	| 
