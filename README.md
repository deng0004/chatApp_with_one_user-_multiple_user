# chatApp_with_one_user-_multiple_user

This is an exmaple of real time chat app which is written in React.js, HTML, CSS for Frontend, it acted as a client.
Spring Boot is used for Backend, it acted as a server.


The following tools were used. 

STOMP, which is refer to Simple Text Orientated Messaging Protocol. It will be used for clients to communicate with any message broker to provide message to platforms and brokers. 


                                      
Client           ------Request--->     Server

Client           <----Handshake---      Server

Client           <----Websocket-->      Server 

                            
                            
                            
                                ReactJs(Client)
                                
/Users as client
client 1                 
client 2                 
client 3

                                                                         
                                  STOMP 
connection
                                 
                                
                                

                                Spring(Server)
/Chatroom (public-chat)  
client 1                 
client 2                 
client 3

(private-chat/(user))
/client 1
client 1

/client 2
client 2

/client 3
client 3
