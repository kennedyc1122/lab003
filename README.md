# lab_chat.py

def get_peer_node(username):
# get_peer_node is the function name
# username: This will be the username that we will get from the get_username function
# We return n; I want to say we will be returning n because in the body of the fucntion n = Pyre(username) tells me 
that we are fetching a username from Pyre and we return n becvause we want that task or action to be completed and stored in n
  
  
def join_group(node, group):
# join_group is the function name
# node: Based on the lecture and trying to think of my own assumptions, I want to say it's a way
  to connecting based on the body saying node.join(group) so I see it as a connection
# group: this is the group that we are wanting to join
# It is not returning but print that we have joined the group. I want to say we probably don't becuase there isn't
   anything that needs to be be returned back but just shown we've joined?

def chat_task(ctx, pipe, n, group):
# chat_task is the funciton name
# ctx: I'm not too sure what this means but seeing it be called a "ZeroMQ Connection Context" I want to say it looks like
  this is the main connection for the chat 
# pipe: Seeing it being labeled as a "communications pipe polled by ZeroMQ" it tells me this is a way for message to possibly pass thought using ctx?
# n: Being called the "node my chat app is connect to" and how we used n for n = Pyre(username) gives me the idea that this is what we are calling it as
# group: this is the group that we want to join and in this case looks like we want the messages to be sent in this group
# this function does not return anything because by looking at the body of the function, there's nothing that needs to be stored,
but rather certain tasks that we need to execute based off the the while loops and the if/else statements. From what I can gather a piece
we want a certain task to do one thing and if it does not do that one specific task, it will then perform a different task and probably repeat it rather than
stopping it.

def get_channel(node, group):
# get_channel is the funtion name
# node: A way of connecting based on what I've previously stated?
# Group: The desired group that we want to join
