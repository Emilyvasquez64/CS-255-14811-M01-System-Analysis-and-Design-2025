# DriverPass Project Reflection

## What was the DriverPass project about?

The DriverPass project focused on designing a web-based system for a driving education business. The goal was to help students better prepare for their DMV driving test through a combination of online lessons, practice tests, and in-person driving sessions. The system needed to support multiple types of users and allow for lesson scheduling, account management, and tracking of student progress.

The system had to be accessible from any internet-connected device. It also needed to be secure, flexible, and ready to grow as the business expanded.

## Who was the client?

The client was DriverPass, represented by Liam, the owner of the business, and Ian, the IT officer. Liam wanted a complete system to manage student training and scheduling. Ian focused more on security, system roles, and access controls.

## What type of system did they want you to design?

They wanted a web-based system that could be accessed from both computers and mobile devices. The system needed to work for four different user types:

- **Students** who would create accounts, choose a training package, schedule driving lessons, and take practice tests.
- **Drivers** who would view their schedules, log training sessions, and leave notes about students.
- **Secretaries** who would book appointments manually for students that call or visit the office and manage student records.
- **Admin** who would manage user access, reset passwords, block accounts, and monitor system activity.

The system also needed to allow students to reset passwords, securely store sensitive data like student addresses, generate downloadable reports, and support updates from the DMV for test changes.

## What did you do particularly well?

I did a good job organizing the different user roles and making sure each had access only to the features they needed. I clearly mapped out each user type's responsibilities and ensured the system supported their actions. I also focused on technical features like scalability, cloud hosting, and secure data handling. I included offline access to downloadable reports and planned for future updates to training packages, which was important to the client.

## If you could revise one part of your work, what would it be and how would you improve it?

I would revise the activity diagrams. I think they could be more detailed, especially around scheduling and modifying appointments. Adding more conditions and showing how the system responds to each user action would make it easier for developers to follow the logic and avoid confusion during implementation.

## How did you interpret the user's needs and implement them in the system design?

I used the interview transcript to guide every part of the system design. For example, Liam mentioned that customers should be able to schedule driving lessons online or through a call. I included both options in the system features. Ian said the admin needed full access to reset passwords and manage user accounts, so I built role-based access controls.

When Liam said he needed to download reports and open them in Excel, I made sure the system could export data in that format. I also added alerts for DMV updates since they wanted to keep their training material up to date.

Everything in the system was based on what they said during the meeting. I prioritized their goals and focused on making the system simple to use and easy to maintain.

## Why is it important to consider the user's needs when designing?

It is important because the system is built for the users, not the developers. If users cannot do what they need to do, then the system fails, even if it works technically. Listening to the users helps avoid mistakes, reduces frustration, and improves the chances that the system will actually be useful. When each user type has the right tools and access, the system becomes more efficient and supports the business better.

## How do you approach designing software?

I start by collecting detailed requirements and making sure I understand the goals of the system. I break down the users into roles and map out their actions using use case diagrams and activity flows. Then I choose the right technologies that match the project needs, like cloud hosting or a responsive design.

I make sure to include basic features like login security, data storage, and admin tools. I also think ahead about how the system can grow or change later. I work step by step and try to get feedback early to avoid building something the client does not want.

## What techniques or strategies would you use in the future to analyze and design a system?

In the future, I would use strategies like:

- Creating figma wireframes so clients can see the design before development begins
- Building clear documentation for user roles and system behavior
- Meeting regularly with clients to make sure the system stays on track
- Plan for flexibility and updates so the system can improve over time without needing a full rebuild.
