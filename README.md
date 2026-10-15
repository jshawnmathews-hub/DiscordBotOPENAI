The bot should have one command, !ask, with the system prompt we've seen in Lesson 9 notebook. This command now will use OpenAI Responses API, passing along a list of 3 tools, movie\_search, movie\_rate, and recommend.



Handle any required function calls coming in the response of the client.responses.create(), and give the final output back to the Discord user.



Feel free to add any other functionalities you would like to your bot to make it stand out 😎



Lesson 8 Homework

!ask question

Create a new discord bot command that receives a question, forwards it to OpenAI using the Responses API, and sends back the answer to the discord channel.

This needs to be stateful, meaning, you should keep track of previous messages exchanged with that user. Extra points if you can maintain a separate chat history for each user! The command must append the word "bark bark" in a random place in the answer before sending it back.





Lesson 8 Homework

!ask question

Create a new discord bot command that receives a question, forwards it to OpenAI using the Responses API, and sends back the answer to the discord channel.

This needs to be stateful, meaning, you should keep track of previous messages exchanged with that user. Extra points if you can maintain a separate chat history for each user! The command must append the word "bark bark" in a random place in the answer before sending it back.



This topic is closed for comments.

This topic is closed for comments.

