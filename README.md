## Inspiration
Our group found that one of the reasons online-learning was difficult was due to the difficulty of meeting classmates, which led to lower levels of motivation to study. Our group was inspired to solve this problem, and we decided that a website dedicated to creating study partners was the best solution.
## What it does
ZotLink is an online forum website that makes it easier for students to find other fellow students that are taking the same classes and study with them. Students can make public posts on ZotLink, which show the school (ex. ICS), class number (ex. 31), and a message (ex. Working on Lab 1 - Langson at 2!) specifying the location and time of a student's study session. Students can react to posts, which gives them access to a group chat with everyone who has also reacted to the post. Posts on ZotLink can be filtered by school and class, which allows students to easily find their desired study buddies.
## How we built it
The backend was built with Python using the websockets library. This created the server that clients could connect to and get information about the other clients, and we used ngrok to move from locally hosted to internet hosted. The frontend was built with ReactJS using the MUI library. Although we had little experience using ReactJS, with a lot of help from mentors, we managed to create a working UI that properly displayed and filtered posts.
## Challenges we ran into
We ran into many technical issues while developing ZotLink. Installing modules was particularly problematic in back end, and front end struggled with syntax errors due to unfamiliarity with ReactJS. We also had trouble connecting the front end to the servers in back end, partly due to miscommunication about how the data would be sent.
## Accomplishments that we're proud of
This was the first/second hackathon for everyone in our group, so we are proud that we created something functional as beginner hackers. We were also all new to ReactJS, and we surprised ourselves with how much we learned throughout the course of HackUCI. Despite the lack of certain features and a somewhat lackluster look, we are proud that everything we coded meshed well together.
## What we learned
We were exposed to many concepts that were very different from the content in the beginner ICS courses. Despite our lack of experience, we learned that enough time and effort (and help from mentors) is enough to create a functional project. Being new to web dev, we learned a lot about front end and ReactJS, in addition to how servers work. We also learned that we learned a lot when asking for help and communicating with our teammates.
## What's next for ZotLink
We were unable to implement certain features due to time constraints and technical complexity. If we had more time, we would firstly implement the chat room feature, where students who interact with a post would be given a chat room where they could talk and get to know one another. We would also add more tags to the posts such as major and include every school and class at UCI, as currently there are only a couple of recognized courses.
