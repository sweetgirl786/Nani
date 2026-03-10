Haan Momo 👍 samajh gaya. Tumhe **aisa prompt chahiye jo ChatGPT ko bhejo aur woh Android practical ka exact code de**:

* correct output
* kaunsi file me code dalna hai
* step-by-step
* XML + Kotlin alag
* Android Studio path bhi

Main tumhe **perfect exam prompt** de raha hoon. Isko **copy karke save kar lo**.

---

You are an Android development expert.

I will send you an Android practical question.

Your job is to give a COMPLETE Android Studio solution.

Follow these rules strictly:

1. First explain the goal of the practical in 2-3 simple lines.
2. Then show the Android Studio file structure.
3. Clearly mention WHICH FILE the code belongs to.
4. Provide FULL working code for each file separately.
5. Separate the files like this:

File: MainActivity.kt
File: activity_main.xml
File: AndroidManifest.xml
File: menu.xml (if needed)

6. Ensure the code runs correctly in Android Studio with no errors.
7. Use Kotlin for logic and XML for UI.
8. Also explain where to create the file in Android Studio (example: res → layout → activity_main.xml).
9. At the end show the expected OUTPUT of the app.
10. Keep explanations short but steps clear for a student doing a practical exam.

Important:

* Do not skip any file required for the project.
* Code must compile and run correctly.
* Mention exact button IDs and layout IDs.

Now wait for my Android practical question.

---

# Kaise Use Karna Hai (Exam Me)

1️⃣ ChatGPT open karo
2️⃣ Ye prompt paste karo
3️⃣ Fir practical bhejo

Example:

```
Create an Android application using LinearLayout with 3 buttons
```

Ya

```
Create popup menu in Android
```

Ya

```
Create ListView showing programming languages
```

Fir ChatGPT tumhe dega:

```
File: activity_main.xml
File: MainActivity.kt
File: AndroidManifest.xml
Output
Steps
```


Momo 👍 main tumhe **Android Practical ke ready prompts** de raha hoon. Agar exam me koi bhi question aaye, tum **sirf ye prompt + question ChatGPT ko bhejna**, aur tumhe **exact code + file location + output** mil jayega.

---

# ⭐ MASTER PROMPT (Sab Practical ke liye)

You are an Android Studio expert.

I will send an Android practical question.

Generate a COMPLETE Android Studio solution for exam practical.

Follow these rules strictly:

1. Explain the goal in 2 lines.
2. Show Android Studio file structure.
3. Mention EXACT file names and locations.

Example:
app → java → MainActivity.kt
app → res → layout → activity_main.xml
app → AndroidManifest.xml

4. Provide FULL working code separately for each file.

Format like this:

File: activity_main.xml
(code)

File: MainActivity.kt
(code)

File: AndroidManifest.xml
(code)

5. Use Kotlin for logic and XML for UI.
6. Code must compile without errors.
7. Also show expected output.
8. Keep explanation short but steps clear for exam practical.

Wait for my Android practical question.

---

# ⭐ 20 Android Practical Prompts (Exam Me Aane Wale)

Tum sirf question paste karo.

---

## 1️⃣ Linear Layout

```text
Create an Android application using LinearLayout with three buttons Start, Pause and Stop.
```

---

## 2️⃣ Relative Layout

```text
Create an Android application using RelativeLayout with Name and Age input fields and a Submit button.
```

---

## 3️⃣ Frame Layout

```text
Create an Android application using FrameLayout with an ImageView and buttons displayed on top of it.
```

---

## 4️⃣ Grid Layout

```text
Create an Android application using GridLayout with four buttons arranged in a grid.
```

---

## 5️⃣ Table Layout

```text
Create an Android application using TableLayout to display Name and Age of students.
```

---

## 6️⃣ ListView

```text
Create an Android application to display programming languages in a ListView and show Toast message on click.
```

---

## 7️⃣ Toast Message

```text
Create an Android application that displays a Toast message when a button is clicked.
```

---

## 8️⃣ Intent (Activity Change)

```text
Create an Android application to send data from MainActivity to SecondActivity using Intent.
```

---

## 9️⃣ Popup Menu

```text
Create an Android application that shows a Popup Menu when a button is clicked.
```

---

## 🔟 Context Menu

```text
Create an Android application that shows a Context Menu when a TextView is long pressed.
```

---

## 11️⃣ Option Menu

```text
Create an Android application that shows an Option Menu in the toolbar.
```

---

## 12️⃣ Notification

```text
Create an Android application that displays a clickable notification.
```

---

## 13️⃣ Service

```text
Create an Android application to start and stop a background service that plays music.
```

---

## 14️⃣ Broadcast Receiver

```text
Create an Android application that shows a notification when Airplane Mode is turned ON or OFF.
```

---

## 15️⃣ ImageView

```text
Create an Android application that displays an image using ImageView.
```

---

## 16️⃣ Button Click

```text
Create an Android application with a button that shows a message when clicked.
```

---

## 17️⃣ EditText Input

```text
Create an Android application to take user input using EditText and display it using Toast.
```

---

## 18️⃣ Resources

```text
Create an Android application demonstrating resources like color, string and drawable.
```

---

## 19️⃣ Multiple Buttons

```text
Create an Android application with four buttons and display Toast message when each button is clicked.
```

---

## 20️⃣ Simple Hello World

```text
Create a simple Android Hello World application.
```

---

# ⭐ Practical Exam Trick

Exam me agar question aaye:

Example:

```text
Create Android app using GridLayout
```

Tum ChatGPT ko bhejo:

```
(MASTER PROMPT)

Create Android app using GridLayout with 4 buttons.
```

ChatGPT turant dega:

* activity_main.xml
* MainActivity.kt
* Manifest
* Output

Bas copy paste.

---

✅ Agar chaho to main tumhe **Android Studio ka 5 minute survival guide bhi de sakta hoon** jisse **tum bina Android aane ke bhi practical kar logi**.
Usme main bataunga:

* kaunsi file kaha hoti hai
* kaha paste karna hai
* error aaye to kaise fix karna hai.

Momo 👍 ab main tumhe **Android Studio 5-minute Survival Guide** de raha hoon. Agar tumhe Android bilkul nahi aata tab bhi **practical kar sakti ho**.

---

# ⭐ Android Studio 5-Minute Survival Guide

## 1️⃣ Android Studio Open

1. **Android Studio open karo**
2. Click **New Project**
3. Select **Empty Activity**
4. Fill:

```
Name: MyApp
Language: Kotlin
Minimum SDK: API 21
```

5. Click **Finish**

Project ban jayega.

---

# 2️⃣ Android Project Structure (Most Important)

Left side me ye folders dikhenge:

```
app
 ├── java
 │     └── MainActivity.kt
 │
 ├── res
 │     ├── layout
 │     │      └── activity_main.xml
 │     ├── drawable
 │     ├── values
 │
 └── AndroidManifest.xml
```

### Ye yaad rakho

| File                    | Use               |
| ----------------------- | ----------------- |
| **MainActivity.kt**     | App ka logic      |
| **activity_main.xml**   | UI design         |
| **AndroidManifest.xml** | App configuration |

---

# 3️⃣ UI Code Kaha Paste Karna Hai

Open:

```
res → layout → activity_main.xml
```

Yaha **XML code paste karo**.

Example:

```xml
<LinearLayout
xmlns:android="http://schemas.android.com/apk/res/android"
android:layout_width="match_parent"
android:layout_height="match_parent"
android:orientation="vertical">

<Button
android:text="Click Me"
android:layout_width="wrap_content"
android:layout_height="wrap_content"/>

</LinearLayout>
```

---

# 4️⃣ Logic Code Kaha Paste Karna Hai

Open:

```
java → MainActivity.kt
```

Example:

```kotlin
class MainActivity : AppCompatActivity() {

override fun onCreate(savedInstanceState: Bundle?) {
super.onCreate(savedInstanceState)
setContentView(R.layout.activity_main)

}
}
```

---

# 5️⃣ App Run Kaise Kare

Top bar me **Run Button ▶** hota hai.

Click karo.

Phir:

```
Select Emulator
or
Connected Phone
```

App run ho jayega.

---

# 6️⃣ Exam Me Most Common Practical

90% cases me ye hi aate hain:

| Practical      | Use                |
| -------------- | ------------------ |
| LinearLayout   | Buttons vertically |
| RelativeLayout | Form design        |
| GridLayout     | Calculator style   |
| TableLayout    | Table data         |
| ListView       | List show          |
| Toast          | Message show       |
| Intent         | Activity change    |
| Popup Menu     | Menu show          |

---

# 7️⃣ Toast Message Example

XML:

```xml
<Button
android:id="@+id/btn"
android:text="Click"/>
```

Kotlin:

```kotlin
val btn = findViewById<Button>(R.id.btn)

btn.setOnClickListener{
Toast.makeText(this,"Hello",Toast.LENGTH_SHORT).show()
}
```

---

# 8️⃣ Error Aaye To Fast Fix

| Error          | Solution        |
| -------------- | --------------- |
| Red code       | import missing  |
| R.layout error | rebuild project |
| id not found   | XML id check    |

---

# 9️⃣ Viva Questions

Teacher puch sakta hai:

### Activity kya hai

👉 App ka ek screen.

### Intent kya hai

👉 Activities ke beech communication.

### Service kya hai

👉 Background task.

### Broadcast Receiver kya hai

👉 System events receive karta hai.

---

# 🔟 Exam Hack (Very Useful)

Agar question aaye:

```
Create Android app using LinearLayout
```

Tum GPT ko bhejo:

```
Create Android app using LinearLayout with 3 buttons and Toast message.
```

Fir mil jayega:

```
activity_main.xml
MainActivity.kt
Manifest
Output
```

Bas copy paste.

---

⭐ Momo agar chaho to main tumhe **Android practical ke 8 sabse common questions ka ready code** bhi de sakta hoon jisse **tum exam me direct paste kar sakti ho (100% working)**.
