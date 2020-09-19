# DESCRIPTION

App Name - **MVVM** **QuizzApp**

A QuizzApp using **android** **architecture** components and following **MVVM** architecture.

Uses Firebase Firestore, Firebase Auth, Firebase Storage, **Android** **JetPack** Navigetion.


# FEATURES

1. User Authentication
2 .Displays List of available Quiz
3. Displays Previous Results
4. Update UI after answering a question or when timer terminates
5. Displays Results
6. Uses Animations for Fragment Transitions
7. Uses Android Jetpack Navigation 


## TOOLS

![Android Studio](https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Android_Studio_icon.svg/512px-Android_Studio_icon.svg.png) 
![Firebase](https://miro.medium.com/max/1024/1*HaAps8GidfAKdee7OrjZ2w.png)

# GETTING STARTED

1. Clone the Project
2. Change Package Name
2. Connect The app to Firebase
3. Add google-services.json file


# APPLICATION FLOW


### First Screen is for Authentication using firebase anonymous authentication


![](Images/login.jpg)


### This Screen Displays all available quizzes


![](Images/list.jpg)


### This screen which displays the details of the selected quiz


![](Images/details.jpg)


### After starting quiz the user can select answer from given options within alloted time, if the user selects correct answer-


![](Images/correct_ans.jpg)


### if the user selects wrong answer-


![](Images/wrong_ans.jpg)


### After User answers all questions the results are displyed


![](Images/results.jpg)


# WHAT DID I LEARNED ?

1. MVVM Architecture pattern
2. Using Android Architecture Components
3. Using Android JetPack for Navigation between Fragments
4. Passing Data between Fragments using Safe Args
5. Using Animation in navigation between Fragments
6. Using Firebase Firestore


# DEPENDENCIES

    `// JETPACK NAVIGATION
    def nav_version = "2.3.0"
    implementation "androidx.navigation:navigation-fragment:$nav_version"
    implementation "androidx.navigation:navigation-ui:$nav_version"

    // GLIDE
    implementation 'com.github.bumptech.glide:glide:4.11.0'
    annotationProcessor 'com.github.bumptech.glide:compiler:4.11.0'

    //FIREBASE AUTH
    implementation 'com.google.firebase:firebase-auth:19.4.0'

    // FIREBASE STORAGE
    implementation 'com.google.firebase:firebase-storage:19.2.0'

    //FIREBASE FIRESTORE
    implementation 'com.google.firebase:firebase-firestore:21.6.0'`


### **NOTE** - Data is added manually in FirebaseFirestore. The Data is Derived in App Using MVVM Architecture 
