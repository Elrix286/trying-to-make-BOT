# trying-to-make-BOT
# trying to create a bot


# to  start the communication with the API
from urllib2 import Request, urlopen

request = Request('https://private-anon-69d48bae69-airdcpp.apiary-mock.com/private_chat/session_id/messages/0')

response_body = urlopen(request).read()
print (response_body)


global n1, n2, my_Tuple=(), final_response =(), tuple= (),c ,d


# code to get a response from the user. here the user should be the bot i am making. code to get the ANSWER
from urllib2 import Request, urlopen
request = Request('https://private-anon-69d48bae69-airdcpp.apiary-mock.com/events/0')

my_Tuple= getORIGNUM()  # calling the function getORIGNUM() for the two numbers returned from the game 

response_body = urlopen(request).read() 
final_response = getsum(my_Tuple)     # to store the final response in the final_respponse as a tuple

print (final_response)

# creating the getsum() function to calculate the sum of the two numbers inside the tuple returned 
def getsum(self, tuple())  #function for  calculating the sum 
       sum =(n1 + n2)
       return sum

# function that will calculate the sum of the two numbers provided by the game script
def getORIG_NUM(self):

 c,d =Numbers.getNUM()   # like a function in the pre-scripted game code that should get the two arguments n1, n2 from the question asked.
        
 return (c,d)    # returning as a tuple
  
    """ trying to explain the logic i thought """
    # if the game script uses random.randrange() function to generate any two numbers between some specified range then we can call the  function that defines the random.randrange() in here as well. 
    like -- 
    if in the game script its coded like
    function getNUM():
      a = random.randrange(0,100)
      b= random.randrange(0,00)
      return (a,b)   # here we can return the values as  a tuple to get multiple return at once
      
      then we can call the getNUM() function from the pre-scripted code to get the two numbers that the question asks for calculating the sum """
      
      
     
                                
    
    
   

