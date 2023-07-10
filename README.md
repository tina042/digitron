<div align="center" > 
   <h2>Digitron: Tech Interview Simulator<h2>
   <h2 align="center">Description </h2>
   <h3>Digitron provides you a platform where you can select your tech stack and give one on one interviews with our AI. Our platform also provides you a Q and A       section where you can ask any general queries to our AI and also a Study material section where you can read about different tech stacks.
   </h3>
</div>  
    
   <h2 align="center">Deployed Link</h2>
   <h3 align="center">Backend: https://hackathon-o2kz.onrender.com </h3>

<br>
    
<h2 align="center">Tech Stack</h2>
<h3 align="center">Frontend</h3>
<p align="center">React | Redux </p> 
       
<h3 align="center">Backend</h3>
<p align="center">Node.js | Express.js | Openai</p> 
       
<h3 align="center"> Database </h3>
<p align="center">MongoDB Atlas </p>

<h3 align="center">CSS Libraries</h3>
<p align="center">Tailwind CSS</p> 


# Schema : 

- user 
   - Name
   - Phone_No
   - email
   - password
   - course

- OTP verify 
    
   - Useremail
   - otp
   - createdAt
   - expireAt

## 
    # API Endpoints 
----

  ## `users`
<br>   
  
        GET    -   /user
        POST   -   /user/register
        POST   -   /user/login
        POST    -   /user/verifyotp
        POST    -  /user/forgot-password
        GET    -  /user/reset/:userid/:token
        PATCH  -  /user/reset/:userid/:token
        POST   -  /user/logout

<br>
  
## `Chat`
<br>   

- General Chatbot
                
        POST    -   /chat/genetalChat 
     
- Interview Chatbot

        POST   -   /chat/interviewChat
      

<br>
          
