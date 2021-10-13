## Maestro

![logo](https://user-images.githubusercontent.com/68790040/137109259-977afe7d-6b31-4c82-8cd7-82e6c5311b47.png)

Maestro is a music learning app design to help people to learn there favorite instrument.
The app is written in Java using android studio and uses Firebase to handle messaging, online storage
and database.

## Functionality

The client has the option to choose from all courses. Every course has different subjects that have their
lessons that the client can pick from.
Every lesson is provided in video format and has a chat for asking question and guidance.
In addition the client can interact with other users and the teachers to ask personal question and make friends.

## Conclusions

The project uses firebase to authenticate users, handle messages, for storage and database as defined in
the targets of the project. The project uses material design, recycle views, card views, fragments and
view pagers in the development of the UI.
Uses background components such as services, broadcast receivers and notifications.
The project uses the gps sensor to get the location of the user and uses internal storage to save the user
information.
The project meets all the desired goals and all the defined targets that were set.

## Discussion

In further development we will add more courses and lessons to the app, develop a better server side
and maybe integrate the app to ios devices as well.

## App screens

#### Main Fragment
![main](https://user-images.githubusercontent.com/68790040/137109283-dfc9ca5d-04be-44c3-94f3-461f8ee04532.JPG)

- The app offers the user a variety of courses to learn music.
- Dragging the side screen offers the user to log in or sign up for the app. If the user is logged in, he can log out or switch to chats, in addition, his name and profile picture are displayed.
- Clicking on a particular course will take the user to the course screen. If the user is not registered for the course or is in guest mode, we will move to a screen that shows the details of the course.

#### Details of the course
![about](https://user-images.githubusercontent.com/68790040/137109296-b6ed7dfe-ea75-4772-bcfb-271bedf6279f.JPG)

- A screen that displays the picture of the course together with its name, the name of the lecturer and an explanation of the course.
- If the user is connected to the application, he is offered to register for the course. if he is in guest mode, he is offered to register or connect to the application.

#### Course screen
![course](https://user-images.githubusercontent.com/68790040/137109307-b69164ed-0156-4bf8-8c54-4291b92c7115.JPG)

- This screen shows the chapter headings of the course.
- Clicking on a chapter head shows the sub-chapters.
- Clicking on a sub-chapter moves to the lesson screen.

#### Lesson screen
![lesson](https://user-images.githubusercontent.com/68790040/137109319-b4b63721-9ac8-4850-b3c1-b4f583499557.JPG)

- This screen shows a video through which the user learns to play.
- Below the video is a group chat where anyone who registers for the course can ask questions and share their experiences.

#### Contacts
![contacts](https://user-images.githubusercontent.com/68790040/137109349-f8d9f0ce-f671-421b-a990-289d0f3bf9c3.JPG)

- A screen that shows all the contacts in the app.
- Clicking on a contact switches to a private chat screen with the contact.

#### Chats
![chats](https://user-images.githubusercontent.com/68790040/137109354-f52a5241-320d-4f5c-b87a-f285257d1c51.JPG)

- A screen that displays all the user's private chats.
- When a user receives a notification for receiving a message, by clicking on the notification he comes to this screen.
- When the user has a message that he did not read, a blue indicator appears next to the message.
