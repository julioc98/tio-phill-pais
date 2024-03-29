# Projeto Tio Phill 
Sistema de roterização para vans escolares com objetivo de informar de forma segura e em tempo real os pais utilizando os recursos do celular do motorista.

## Hackathon - Uber Hack - 01 a 02/06/2019

# Equipe - 6
Melanie Miranda
JC
Jessica Rampim
Renato Tadeu Rodrigues
Thiele Nunes de Souza

## Instruções para o uso do Firebase:

Follow these steps to setup and run the quickstart:

 1. Create a Firebase project in the [Firebase Console](https://console.firebase.google.com).
 1. In the Firebase console, enable Anonymous authentication on your project by doing: **Authentication > SIGN-IN METHOD > Anonymous > Enable > SAVE**
 1. In the Firebase console, enable Cloud Firestore on your project by doing: **Database > Create Database**
 1. Select testing mode for the security rules
 1. Copy/Download this repo and open this folder in a Terminal.
 1. Install the Firebase CLI if you do not have it installed on your machine:
    ```bash
    npm -g i firebase-tools
    ```
 1. Set the CLI to use the project you created on step 1:
    ```bash
    firebase use --add
    ```
 1. Deploy the Firestore security rules and indexes:
    ```bash
    firebase deploy --only firestore
    ```
 1. Run a local server:
    ```bash
    firebase serve
    ```
 1. As indicated, open [http://localhost:5000](http://localhost:5000) in your browser and try out the app.

