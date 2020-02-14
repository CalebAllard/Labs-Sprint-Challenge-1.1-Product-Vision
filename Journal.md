### Prompt 1

Describe the conversations you had this sprint with your product owner(s) and team.

- Describe the product and features you plan to deliver.
    Our team is working on the Mission Control system, which will be used by Lambda to manage the Labs projects.
    It will allow a Manager "team lead" to view all projects he/she is leading. Also it will have a Team Member "employee"
    which will have access to only projects they are on. It will allow for notes, and the easy shearing and displaying of 
    project resources. 

- How did these conversations determine the features you will deliver during Labs?
    We decided that after the meeting with stakeholders and potential users, that we will be adding different views for each account type
    (e.x. Manager or Team Member). They will be able to both share and add resources for projects they are affilated with. In the future
    we would like to see, or add a superuser which would be able to other account types which will make the system more dynamic and be able
    to work in more enviroments. 

- How did your discussions change the way you viewed the product?
    At first we thought this product was going to be designed as a system for Lambda to use. However after we found out
    that the stakeholders wanted this producted to be developed in a way where it can be used in any bussiness, and be viable for a 
    product development managment system. After knowing that we knew we would have to change the way we were thinking of adding or changing
    features.


### Prompt 2

Describe the technical or design discussions that shaped the long-term product vision.

    After finding out the stakeholders view was a system that was dynamic and not just for Lambda we shifted our thoughts to a overall
    project managment solution product vision. Our current long-term goals have a view of a fully customizable managment project.
    Which can and would fit into any proudct development enviroment. Giving control of several proejcts to managmanet, and the quick and easy
    details or view for each project and the team. the sytem would be a hub for information and communication for a project and its team.

    We will be redesigning the flow of the system to make it more intuitive and have a natural flow and look to it. Giving an easy learning curve
    to new users. Allowing managment and team memebers to have more focus on there work, instead of how to use our program. 


- **For data scientists and engineers:** Describe the technologies that you will use to build this product. Why do they fit the product vision?
    
    For the project we have a very robust stack. For the frontend we will be using React which will give the web application a more
    descktop application feel. With Context API for state managment, This was decided over Redux due to its flexability with expandability for
    the project as it grows.

    We will be using postgres for data persistince, Prisma and Apollo with GraphQL as are connection between frontend and backend
    GraphQL gives more flexability and dynamicism this with URQL will give the project the ablity to decided the data you want back. Authentication will be 
    handled by third party Okta for OAuth for secuirty. our hosting will be through AWS