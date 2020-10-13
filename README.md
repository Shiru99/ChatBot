# <center>CHATBOT</center> 
***<center>Personal Assistant for anyone</center>***
<center><img src="https://github.com/Shiru99/ChatBot/blob/main/chatbot.png" width="75%" height= "75%" title="FVCproductions" alt="Chatbot Image"></center>

<h2><center>TEAM PHI (φ)</center></h2>

***<center>15th Nov. 2019</center>***
***<center>3rd Sem. SSL project</center>***

<h2>INTRODUCTION</h2>

>

Chat bot will help students to take admission at IIT Dharwad. It will also help existing students to store their personal data and will help them by giving some local information. Not only student will get benefits from this but teachers will also get benefits from this. Teachers can store their time table in it. Time table uploaded by teacher will help students to know the location of teachers at given time.


<h2>BACK END PROCEDURE</h2>

>

1. Filling information in first window will pass that information to client file which will try to match password from actual password to given password.
2. If password matches you have to click sign In option which will call chat bot function in background and will open a chat window on front end.
3. When you will enter question in ask bar and press ask it will call caller update function.
4. Here magic happens. It will try to find the best response from stored data which will give personalized answer to user.
5. Foe ex. For greetings it will select random greeting from response greeting and will pass to user.
6. If its a question then it will pass best response from info.txt or feedbackdone.txt and if it is not able to find direct answer it will give marks to each answer according to previous stored data and user question. And answer with maximum score will be chosen as best suitable answer, but if the answer fails to score greater than threshold which is 51 which may change if admin wants to then it will leave that function.
7. Then it will go to specialized function say library which will contain all information for library. Again it will rank answer and print the most relevant if it is clearing threshold. And so on.
8. If it fails to answer via specialized sections too. It will replay i don't understood and will give google search as result. But question will be added to admin feedback so that when admin will add answers chatbot will become more and more intelligent. 



<h2>RESULTS</h2>

>
The most suitable response will be stored in tuple which will be returned to print function which will print response to interface

    1. Searches for exact match
    2. If not then ranks the answer and most relevant with seared threshold
    3. If not google search and adds question to library.


<h2>LIBRARIES USED</h2>

<center><img src="https://github.com/Shiru99/ChatBot/blob/main/Libs.png" width="75%" height= "75%" title="FVCproductions" alt="Chatbot Image"></center>


<h2>FUNCTIONS OF LIBRARY</h2>

<center><img src="https://github.com/Shiru99/ChatBot/blob/main/FlowChart.png" width="75%" height= "75%" title="FVCproductions" alt="Chatbot Image"></center>


