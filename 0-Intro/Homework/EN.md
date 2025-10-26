# Before Starting the Course

You need to design a WhatsApp-like messenger **on your own** (even if you know nothing yet or your design consists of just one server and a single database — that’s perfectly FINE).  
You don’t need to show this design to anyone; it will be for your personal use only. After each lesson, you’ll revisit this design — review what was done incorrectly, and update it based on new knowledge from the lessons. (At the end of the course, I’ll show how **I** would design a similar system.)

## System Requirements

- The system has **no seasonality**.  
- The system will be used **worldwide**.  
- The application must display **unread messages**.  
- The application must support **chats** and **private messages**.  
- Messages can contain **only text and images**.  
- **Maximum image size per message:** 1 MB.  
- **Maximum number of images per message:** 3.  
- **Maximum text size per message:** 2000 characters.  
- Clients include **mobile**, **desktop**, and **web applications**.  
- **200,000,000 unique users** log in daily.  
- Each user sends **10 messages per day** on average.  
- Each user views messages **20 times per day** on average.  
- The system must operate **24/7**, allowing a maximum **downtime of 4 hours and 23 minutes per year**.  
- The application must display **online/offline statuses**, as well as the **last seen time** of a user.  
- A message must be **delivered within 3 seconds** to the recipient (if the recipient is offline, they should receive a **push notification** on their mobile phone).  
- The application must support **cross-device synchronization** (for example, if a user reads a message on their phone, the message should also appear as read on their laptop).  

## Additional Notes

- You **don’t need to design the frontend** (focus only on the backend).  
- You **don’t need to design authentication** (assume this part of the system has already been implemented).  

You may use tools like **Lucidchart** or **Miro** for your design — they have rich functionality and make it easy to update your diagrams later.

## Your Design Should Include

- **Load and memory consumption estimation** for main operations.  
- **Data model** (describe the core entities in your database and their relationships).  
- **API description** (you don’t need to specify REST or GraphQL endpoints — just describe the main operations conceptually).  
- **High-level system architecture** outlining the main components and their interactions with other parts of the system.  

Good luck designing your version of WhatsApp! *(It will be very interesting to review your progress after completing the course.)*
