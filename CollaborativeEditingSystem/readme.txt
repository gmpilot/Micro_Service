________________ Run System ________________

** Go to terminal
1. ls
2. cd user_management
3. mvn spring-boot:Run

________________ Check API Register ________________

** Go to postman for Register
1. url http://localhost:8081/api/users/register
2. Json raw body: 
                {"username":"name",
                "password":"pass",
                "email":"name@lab.com"}
3. Method: POST 
4. Send and check success

________________ Check API Login ________________

** Go to postman for Login
1. url http://localhost:8081/api/users/login
2. Json raw body: 
                {"username":"name",
                "password":"pass",
                "email":"name@lab.com"}
3. Method: POST 
4. Send and check success

________________ Check API Others ________________
1. url http://localhost:8081/api/users/delete
2. url http://localhost:8081/api/users/change-password