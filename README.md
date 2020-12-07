# limechat_rasa_assignment

A couple of things I would have wanted to get right - 

1. Use of retrieval intent for faqs
2. Rules to implement active loop for bringing the conversation back to flow while booking a room

Both these require rules to be activated and given the restricted time, I couldn't figure out a way to make rules work without messing up the entire training data story flow. Everytime I configured even a super simple rule, the stories were being bypassed for some reason. 

Except for the back-to-conversation-flow feature, the uploaded model should work otherwise for all other listed intents.
Also would have loved to add decorators like fallback response, conversation ending response etc.
