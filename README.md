
![image](https://img.shields.io/badge/Socket.io-010101?&style=for-the-badge&logo=Socket.io&logoColor=white)
![image](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![image](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)


# Heal

In this COVID time, it was difficult for people to go to doctors every time. What if, if people can check themselves by using an app at their home? So they won't have to visit a doctor every time they have minor symptoms and we tried to solve this problem by creating an app named HEAL.

## What Heal does?
Heal is a symptom checker app. If you are not feeling well you can come here and ask Heal about the possible cause of your illness. It will require only a few minutes to find the cause and the best part about heal is, you do not need to write all the things by yourself, we integrate a voice assistant in the app powered by Dasha AI so you just need to answer a few questions and you are good to go.
Inspiration 👩🏻‍⚕️
As in this COVID time, it was difficult for people to go to doctors every time. At such a time, wouldn't it be great if people can themselves check out their symptoms using just an app at home? So that they won't have to visit a doctor every time they have light symptoms. Therefore, we took inspiration from this problem and presented an idea where people can check out their symptoms and see if they need any doctor or not.

## What it does 👨🏻‍💻
Heal is a symptom checker app. If you are not feeling well you can come here ask Heal about the possible cause of your illness. It will require only a few minutes to find the cause and the best part about heal is, you do not need to write all the things by yourself, we integrate a voice assistant in the app powered by Dasha AI so you just need to answer a few questions and you are good to go.

## How we built it 🧑🏻‍💻
The app consists of frontend and backend. we used React.js to build the frontend of the app and we used node.js as the backend.

We also used some important packages to handle the different scenarios like

Socket.io to show the live chat between the user and Dasha on the frontend
infermedica API to check the possible cause on the bases of the symptoms given by the user.
Dash AI as a voice assistant which gives us voice capabilities and
Sawo labs for authentication which is very reliable and simple to integrate with the app.
## Challenges we ran into
The primary challenge was to build the project in such a small period of time which is quite difficult. We had planned a lot on the project but were not able to implement everything in such a short span of time. Other challenges were to make yourself comfortable with the other teammates as we didn't work before together. We also faced a challenge in training the Dasha AI, no doubt the Dasha AI is simple t integrate but it takes time to train a model so that we can cover all the loopholes. Overall, the major challenges we faced were to maintain the same functionality of the app as we thought in the beginning. We managed to solve many of these challenges because of our consistency and teamwork and we build a working model.

## Accomplishments that we're proud of 🥳
We got so much exposure to contributing to open source and working with a third-party tool (Dasha AI and Sawo and Infermedica API ). We also had frequent discussions where we found solutions to many of the challenges we faced. We gained communication and time management skills throughout the project that we believe is very essential for a developer. Not only this, we gained some new connections and we manage to understand each other in a very short amount of time.

## What we learned
We learned how to work with git and GitHub and also how to script the commands in Dasha Studio and learned how to implement the features from the documentation, we learn how to use socket.io. We also learn some best practices to work with the team and manage the large project and how to handle the frontend and backend parts in a very efficient way.

## What's next for Heal
There will definitely be higher versions of the application, with more and more features in the future. We can not able to implement all the features as of now but we try to make it more efficient to give the best user experience in the medical field.

## Run Locally

Clone the project

```bash
  git clone https://github.com/mayank2021/Heal-symptom-checker.git
```

Go to the project directory

```bash
  cd Heal-symptom-checker
```

Go to frontend 

```bash
  cd client
```

Install the dependencies

```bash
  npm install
```

start the frontend server

```bash
  npm start
```

Go to backend 

```bash
  cd api
```

Install the dependencies

```bash
  npm install
```

start the backend server

```bash
  node index.js
```
You're good to go now.
