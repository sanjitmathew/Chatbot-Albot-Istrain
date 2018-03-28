# Chatbot-Albot-Istrain
Python module for creating a chatbot

This python 2.7 module provides functions to store, question and chat. It uses its own language processing algorithms.
This packages have shown its efficiency and results better than existing chatbots, which you can check and download a desktop version made from these packages. check https://sites.google.com/view/samara-researchlab/labs/uncommon-sense/chatbots/albot-istrain

## how to use
<ul>
  <li>copy the file albot.py in your project</li>
  <li>Please don't use the global variables I have used those are nwd,err,exc,whos,neg,tail,howwords,whywords,whatwords,wherewords,whenwords,rubbish,jar.</li>
  <li>In your source code import everything from albot(its a must)
    <ul> <li>from albot import *</li>  </ul>
   </li>
   <li>To store information
       <ul> 
          <li>store('Malayalam is a palindrome')
            <ul> 
              <li>stores it as a point ie line by line in a file called Knowledge_Base.txt</li>  
            </ul>
    </li> 
    <li>To  ask questions
       <ul> 
          <li>print questions('is malayalam a palindrome')
            <ul> 
              <li>returns the answer</li>  
              <li>no need to add question marks</li> 
              <li>ask one questions at a time</li>  
              <li>if contradictory points are found it is categorized as for and against</li>  
            </ul>
    </li> 
    <li>To  chat
       <ul> 
          <li>print chat('is malayalam a palindrome?')
            <ul> 
              <li>returns the response</li>  
              <li>need to add question mark for questions</li> 
              <li>any sentence without question marks are stored in Knowledge_Base.txt</li>  
              <li>gives reponses like 'got it','point noted', 'no idea'</li>  
            </ul>
    </li>  
            
    
  </li>
</ul>

##disclaimer

This chatbot is not perfect. I have not tested it thoroughly. It does wild guesses. can sometimes be wrong. 
