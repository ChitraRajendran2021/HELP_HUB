**HelpHub a Problem-Solving Collaboration Application**
Overview: Create a web-based application that enables users to post problems and allows individuals available for assistance to pick up and help resolve those problems. The application aims to foster collaborative problem-solving by connecting individuals in need of help with those who have the expertise and availability to assist.

**Key Features:**
User Profiles: Users can create and customize profiles, including their skills, areas of expertise, and availability.
Problem Posting: Users can submit problems, detailing the issue, its context, and any relevant information. Problems can be categorized for easy identification.
Problem Discovery: Users can browse through a list of posted problems, filtering them based on Keywords and Skills.
Problem Claiming: Users who are available and capable of helping can claim a posted problem, indicating their intention to provide assistance.
Discussion Platform: Each problem will have a dedicated discussion space where users can communicate, share additional information, and collaborate on solving the problem.
Problem Resolution: Once a problem is resolved, the user who claimed it can mark it as solved. This action can trigger notifications to the original poster and other involved parties.
Rating and Feedback: Users can provide ratings and feedback on the assistance they received, helping to maintain the quality of interactions.
User Notifications: Users will receive notifications about claimed problems, updates, and resolution status changes.
Target Audience: This application is designed for individuals seeking solutions to technical problems, questions, or challenges, as well as those willing to offer their expertise to help others. It can be particularly useful for developers, engineers, IT professionals, and enthusiasts in various domains.
 
**Expected Outcomes:**
Knowledge Sharing: By connecting users seeking help with those willing to provide assistance, the platform encourages the sharing of knowledge and expertise.
Engagement and Learning: Users can improve their problem-solving skills, learn new concepts, and expand their network by actively participating in discussions and assisting others.
Community Building: This unique ecosystem significantly enhances the probability of users securing new assignments by capitalizing on the power of a collaborative and supportive community.


## Run Spring Boot application
```
mvn spring-boot:run
```
The Spring Boot Server will export API at port `8081`.

## Run Angular Client
```
npm install
ng serve --port 8081
```
