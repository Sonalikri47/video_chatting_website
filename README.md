# 🎥 Django-Based Video Chatting Website

A real-time **video chatting web application** built using the **Django** framework and integrated with the **Agora Video Web SDK**. This project allows seamless audio and video communication between users, offering a smooth and user-friendly experience.

---

## 🚀 Features

- 🔴 Real-time video and audio chat  
- 🎙️ Microphone toggle  
- 🎥 Camera toggle  
- 🏠 Lobby page for user input before joining calls  
- 🚪 Easy leave button to exit chats  
- 💡 Responsive and intuitive user interface  
- 🔒 Secure and scalable Django backend  

---

## ⚙️ Technologies Used

- 🌐 **Django** — Python web framework for robust backend development  
- 📡 **Agora Video Web SDK** — Real-time audio and video streaming  
- 💅 **HTML5/CSS3** — For structuring and styling web pages  
- ⚡ **JavaScript** — For front-end interactions  
- 🌩️ **Cloud Deployment** — Easily deployable to cloud platforms (e.g., Heroku, AWS)  

---

## 🛠️ Implementation and Setup guide 

Follow these simple steps for setting up and implementing website:

1. **Step 1: Create a Virtual Environment:**
   Create a virtual environment for  the Django project. In your command prompt, navigate to the folder where you want to create the project and run:
   ```bash
   py -m venv djangoproject

2. **Step 2: Set up the Django Project:**
    Check if Django is installed:
      ```bash
      django --version

3. **Step 3: Create a Django project:**
   ```bash
   django-admin startproject mychat2
   cd mychat2

4. **Step 4: Create an app inside the Django project:**
   ```bash
   py manage.py startapp base

5. **Step 5: Install necessary dependencies:**
   Since Django does not provide real-time communication features by default, we will use the *Agora Video Web SDK*.

   - Go to Agora.io
   - Create and account and set up a new project.
   - copy the App ID and App Certificate provided by Agora.

6. **Step 6: Update project files:**
 <br>  Update views.py
 <br>  Replace "YOUR APP ID" and "YOUR APP CERTIFICATE" with the values from Agora:
    ```python
    #views.py
    def getToken(request):
        appID="YOUR APP ID"
        appCertificate="YOUR APP CERTIFICATE"
        #Additional token generation logic here
  <br>  streams.js
 <br>  Set the Agora App ID in the JavaScript file:
   <pre>```javascript 
        //stream.js
        const APP_ID="YOUR APP ID";
        //Additional Agora setup and streaming logic here
     ```</pre> 

7. **Step 7: Run the Django Server:**
   After updating the neccessary files, start the Django development server:
   ```bash
   py manage.py runserver
<br> Now, open you browser and go to :

 <pre> ```bash
   http://127.0.0.1:8000/
 ```</pre>
<br>

## 🙌 **Acknowledgments**

- 💡 [Agora.io](https://www.agora.io/) for providing the **Video Web SDK**  
- 🔥 [Django](https://www.djangoproject.com/) for the **robust framework**  

    
