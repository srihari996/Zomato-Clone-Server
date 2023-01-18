# Initial SetUp

https://github.com/srihari996/Zomato-Clone-Server

git clone https://github.com/srihari996/Zomato-Clone-Server
cd zomato-clone 
mkdir server 
cd server 
npm i


<!-- Developer Dependencies -->
npm install express mongoose dotenv


<!-- Developer Dependencies -->
npm i --save-dev nodemon @babel/cli, @babel/core and @babel/preset-env @babel/node

# API Planning

- Food (Food & their details)
- Image (Stroing all the imgs related to the zomato)
- Menu (Menu & their details)
- Order (Order & their details)
- Resturant (Resturant & their details)
- Review (Storing all the list of reviews)
- User (User related details, username, email and password)


jwt => JsonWebToken Session Based Appln 

    >> tokens 
    >> For the 1st time when we visit the application we login or create a acc 
    >> at this pt of time -> a new JWT token will be generated 
    >> and if we revisit the application after 1 day || 10 day ||10 months ... we don't need to pass the credentials instead while making a req the generated JWT token ill be sent to the server 
    >> JWT will be stored in client or endusers browser (Cookise, localstorage)
    >> JWT also has expiration it depends on business perspective (1 day | 10 day || 10 years)  

    hash & salting
    Srihari => hash() => @eabcdhki$6789@12 => salt(6) => abcgtuorh@1609$87yui