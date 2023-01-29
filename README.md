# Email Backend
- Implemented using springboot framework. please, make sure you that you change paths found in service classes to the location where you download this project, the project folder was named EmailBackServer. 
- Run Back-End Program on local host https://localhost:8080/ 
- Email Frontend: https://github.com/AliELSharawy/Email-Front-End

## Team Members:
    Ali Hassan ElSharawy
    Basel Ahmed
    Louay Magdy
    
## Design Patterns used:
     Delegation Pattern:
        - Relation between services and controllers
        - Relation between services and models
        - Relation between some services as userFileService and messageService
     Interface Pattern:
        - Relation between MessageCriteria class and MessageService
        - Relation between UserCriteria class and UserService
     Prototype Pattern:
        - Both models objects can be cloned
     Filter Pattern:
        - Applied in searching for messages and contacts
     Maker Interface Pattern
        - in cloning objects , and serialization and deserialization of Json Objects

## Email Web Application provides:

    1- sending emails 
    2- staring emails 
    3- mark an email as important 
    4- making a custom folder where you can put some emails but up to 1 folder 
    5- trashing emails 
    6- make an email as draft 
    7- resend the drafts 
    8- sending attachments with email 
    9- deleting the trashed emails after about 30 days from the trashing process date 
    10- searching for some users 
    11- adding users as friends
    
## Design Decisions made:

    - Sending messages can be from one user to multiple users
    - User can use only one custom folder to drag the needed files inside
    - In searching for messages by "to" attribute if you put multiple users, you will get messages to either of them (inclusively)
