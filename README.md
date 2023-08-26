# video_chatting_website

Installing necessary library here for real-time communication, Agora video web
sdk services which enables seamless audio and video streaming between users
is incorporated by creating Agora account and apps for accessing services.
Copying the generated App Id and App Certificate used in javascript file
‘stream.js’.
Further necessary Django templates, views, urlpatterns are designed. Later,
focus is on incorporating control features like microphone and camera toggling,
a leaving button, and a lobby page for input variables such as room name and
user name.
During the design and architecture phase, the necessary Django models are
created, taking into account the control functionalities required for video chat.
User authentication and authorization are implemented using Django's built-in
authentication system, Django-admin, ensuring secure access to the website's
controls.
The user interface is developed using HTML, CSS, and JavaScript frameworks,
ensuring an interactive and responsive design that integrates the desired
controls.
In the backend development stage, the logic for managing video calls, chat
rooms, and user interactions is implemented within the streams.js file. This
includes handling control functionalities such as muting, camera toggling, and
leaving the chat as required. Testing the site can be done after downloading the
codes, and accessing the local server at http://127.0.0.1:8000/” .
