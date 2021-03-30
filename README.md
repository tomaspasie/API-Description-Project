###### Tomas Pasiecznik
###### Professor Williams
###### IS 421-002
###### 30 March 2020

# Homework: Module 1 - What is an API?

### Assignment: Describe how an API for our school will be used to support the school’s business operations. The scope of the project is to create a minimally viable product (MVP) of an API that supports online course registration for our school. Describe the uses of the API such as supporting mobile and web-based course registration as well as supporting other business applications that the school may develop in the future.

The project we are looking into calls for creating a minimally viable product of an API that supports online course registrtation for the school. The first thing we need to do is to look at the functionality we need to make sure the API has to support the operations that the school needs. Since we know that our focus will be around mobile and web-based course registration, we can assume that a user will need to be able to:  
- See all the courses that are available. (GET Request)
- Register for courses. (POST Request)
- Update meeting times for a course based on available times. (PUT Request)
- Delete courses which one is currently registered in. (DELETE Request)  
Luckily, using an API will make adding these functionalities simple. More specifically, I would use a REST API for this, as opposed to a SOAP API, since I find it to be more efficient and less ridgid for what we will be doing with it. With a REST API, we will be able to add all the functionalities listed above and still be able to easily add other features when we are done. One feature that could be added is a course registration for professors to use (since the one we just created was for students) where a professor would be able to set his course description, meeting times,  as well as any other information needed.
