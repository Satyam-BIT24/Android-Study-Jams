# Android-Study-Jams

### AGRICOLA

**Problem Statement :**

India is an agrarian country as almost 70% of the population is engaged in agriculrure related issues. But still there are many problems faced by these farmers. To help farmers connect directly to the government and to help them in farming related issues like in detecting the plant disease to know weather forecast of their area and to modernize them is the main motto.

**Proposed Solution :**

This app **"AGRICOLA"** has the following features (i) Weather Forecasting (ii) Connecting the app to the government website (iii) Detecting Disease in the Plant. For weather forecasting we have used OpenWeather API and we have connected the app to https://farmer.gov.in/ the government site which contains al the information like crop management;soil health card and other informations related to Fertilizers , Pesticide , Seeds etc. Next for detecting disease in the plants we have used ML . The first time when the app is installed it asks you to enter your location and then it forecasts weather of that place thereafter whenever we reopen that app we donot need to enter the location though we can change the location whenever we want. In detecting disease part of the application we can either use camera option to click the photo of the infected leaf to know which disease is the plant infected with and then there is a button to know remedies for the same disease on google or we can also upload image from the gallery for detecting disease.
![WhatsApp Image 2022-01-02 at 14 09 06](https://user-images.githubusercontent.com/93431006/147870747-dd6a1bb1-1151-4d2a-9999-fc0a35e0e55f.jpeg)
![WhatsApp Image 2022-01-02 at 14 09 07](https://user-images.githubusercontent.com/93431006/147870777-02455007-e48b-4a21-b9ef-707d3888036c.jpeg)
![WhatsApp Image 2022-01-02 at 14 09 07 (1)](https://user-images.githubusercontent.com/93431006/147870880-6c2b0408-5e38-4f54-a816-c492b5337797.jpeg)
![WhatsApp Image 2022-01-02 at 14 09 09](https://user-images.githubusercontent.com/93431006/147870904-8d2be1f3-fa79-425d-86c5-800fd068af14.jpeg)
![WhatsApp Image 2022-01-02 at 14 09 10](https://user-images.githubusercontent.com/93431006/147870932-6830e6c2-7b31-47a7-a0ce-aef23cb2de67.jpeg)
![WhatsApp Image 2022-01-02 at 14 09 10 (1)](https://user-images.githubusercontent.com/93431006/147870951-50cc91cc-bc55-462f-8338-f450c0488e88.jpeg)
![WhatsApp Image 2022-01-02 at 14 09 11](https://user-images.githubusercontent.com/93431006/147870965-802d51ae-3a22-4568-af25-addd8fae1ba6.jpeg)
![WhatsApp Image 2022-01-02 at 14 09 11 (1)](https://user-images.githubusercontent.com/93431006/147871000-cde636e1-050e-4f24-9825-31a9726efc9e.jpeg)
![WhatsApp Image 2022-01-02 at 14 09 12](https://user-images.githubusercontent.com/93431006/147871013-2f4d0675-5ee8-4162-81b0-e4e68d05b554.jpeg)


**Concepts Used :**
This app is fully made in KOTLIN language. The following concepts have been used in this app:

*Navigation: For navigation within the app we have used Android Jetpack's Navigation component.

*ViewModel: To store and manage UI-related data in a lifecycle conscious way.

*LiveData: To handle data in a lifecycle-aware fashion.

*RoomDB: This is a persistence library which provides an abstraction layer over SQLite to allow for more robust database access while harnessing the full power of SQLite. Basically even when we close the app it remembers the location and so we donot have to re-enter the location again and again.

*Moshi: It is a modern JSON library for Android, Java and Kotlin basically it is helpful to parse JSON into Java and Kotlin.

*Data Binding: For declaratively bind UI components in layouts to data sources.

**Future Scope :**
In this app we can also add option to contact experts in the agriculture field and then we can add Agronomy/Agribusiness News & Updates and many more features can be added to this app.
