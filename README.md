# Analysis_Whatsapp_Group
This will contain Python code of the tasks I had performed over my class WhatsApp group data extracted from .txt file backup. 



# What were the Ideas?
## 1. How the frequency of messages vary over the day?

**motivation**

motivation was the check what was the valuable time, if someone wants to send post a news to the whatsapp group such that it can reach maximum number of people in shortest amount of time.

![image](https://user-images.githubusercontent.com/64163517/140058907-191c1848-1918-48ae-a032-dc7ee0dfa081.png)

This can be used by someone if he/she wants to promote something in a group, then he can go on the busiest hour to get the most attention of the viewers. 

### 1.1 Who posted between 4 AM and 5 AM.
since 4 and 5 AM is the most silent time in my whatsapp group, still I wanted to see who were the masters of this time as well.![image](https://user-images.githubusercontent.com/64163517/141661418-bf93463e-e978-4314-a431-6407285d00a4.png)

## 2. Who sends the most number of messages in the group?
**motivation**

when classses commenced, I was curious to know who would be my go-to-guy incase I want to know about any class gossip.

![image](https://user-images.githubusercontent.com/64163517/140166440-be3dc43a-3a51-4bf0-94a4-41e6faf9b0a8.png)

## 3. Calculating the total time it took for the conversation?
**motivation**

Actually, it was just some personal thing, here I calculated the total amount of time with our usual typing speed it would have taken to do the chats. 

Here I have used whatsapp chat file backup and telegram chat backup file. 
P



# How to locally run the project?
**Requirements**
1. You will need [python](https://www.python.org/downloads/) installed in your system. 
2. An editor of your choice, like [VS Code](https://code.visualstudio.com/download) or [Anaconda](https://www.anaconda.com/products/individual) distrbution. 
3. you will also need to install following libaries, to install a library either open anaconda prompt for Anaconda or open a terminal in VS Code

`pip install matplotlib`

`pip install json`

**Setup**
1. Fork the repository to your account.
2. Open git bash in the folder where you want to open the project.

    `git clone www.github.com/<yourusername>/Analysis_Chat_Data`
3. Open the folder in VS Code or Jupyter Notebook, and you are good to go. 


# More ideas to implement
- [ ] who is the most emoji person in the group.  
    - [ ] calculate the number of emoji for each user of the group
    - [ ] then compare for who has highest score among them 
    - [ ] then declare the winner among them. 
- [ ] Evaluate the average mood of the group with the help of smillies used
    - [ ] give a sentiment value of zero to one to every emoji
    - [ ] evaluate the total sentiment score for the day, then devide it by the total number of emojis used on that day
    - [ ] plot a time varying graph of the same 


- [ ] write code of Socially active chart again, this one is old and not purely in python as well.  
    **Steps**
    - [ ] merge data to form a new updated data set. - 16 November 2021
    - [ ] start working on the data set - 16 November

**major update**
- [ ] make a user profile out of the data of every participant of the group ...and add these features
    - [ ] sleeping time of top 3 partcipants
    - [ ] all the messages
    - [ ] length of messages
    - [ ] average length of the messages
    - [ ] average time between the replies
    - [ ] sentiment
    - [ ] how his/her messages' length varied over time
    - [ ] how much time he/she takes to reply
    - [ ] deleted messages 
 
- [ ] make a general application, or web application if possible



