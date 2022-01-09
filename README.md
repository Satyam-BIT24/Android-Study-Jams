# Android-Study-Jams

### AGRICOLA

**Problem Statement :**

India is an agrarian country as almost 70% of the population is engaged in agriculrure related issues. But still there are many problems faced by these farmers. To help farmers connect directly to the government and to help them in farming related issues like in detecting the plant disease to know weather forecast of their area and to modernize them is the main motto.

**Proposed Solution :**

This app **"AGRICOLA"** has the following features (i) Weather Forecasting (ii) Connecting the app to the government website (iii) Detecting Disease in the Plant. For weather forecasting we have used OpenWeather API and we have connected the app to https://farmer.gov.in/ the government site which contains al the information like crop management;soil health card and other informations related to Fertilizers , Pesticide , Seeds etc. Next for detecting disease in the plants we have used ML . The first time when the app is installed it asks you to enter your location and then it forecasts weather of that place thereafter whenever we reopen that app we donot need to enter the location though we can change the location whenever we want. In detecting disease part of the application we can either use camera option to click the photo of the infected leaf to know which disease is the plant infected with and then there is a button to know remedies for the same disease on google or we can also upload image from the gallery for detecting disease.
![merge_from_ofoct](https://user-images.githubusercontent.com/93431006/147937787-b0eb0f01-0273-4573-8a0f-bf62e83d092f.jpg)


**Concepts Used :**
This app is fully made in KOTLIN language. The following concepts have been used in this app:

*Navigation: For navigation within the app we have used Android Jetpack's Navigation component.

*ViewModel: To store and manage UI-related data in a lifecycle conscious way.

*LiveData: To handle data in a lifecycle-aware fashion.

*RoomDB: This is a persistence library which provides an abstraction layer over SQLite to allow for more robust database access while harnessing the full power of SQLite. Basically even when we close the app it remembers the location and so we donot have to re-enter the location again and again.

*Moshi: It is a modern JSON library for Android, Java and Kotlin basically it is helpful to parse JSON into Java and Kotlin.

*Data Binding: For declaratively bind UI components in layouts to data sources.
 **APK :** Download .apk file from https://github.com/Satyam-BIT24/Android-Study-Jams/tree/main/App/build/apk .

**Future Scope :**
In this app we can also add option to contact experts in the agriculture field and then we can add Agronomy/Agribusiness News & Updates and many more features can be added to this app.
