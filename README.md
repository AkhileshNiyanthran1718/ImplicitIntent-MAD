# Ex.No:3a Develop program to create a text field and a button “Navigate”. When you enter “www.gmail.com” and press navigate button it should open google page using Implicit Intents.


## AIM:

To create a navigate button using Implicit Intent to display the gmail page using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

### MainActivity.java

package com.example.exp_1;

import android.os.Bundle;

import androidx.appcompat.app.AppCompatActivity;

import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast = Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStart() {
        super.onStart();
        Toast toast = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
        toast.show();
    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Toast toast = Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onPause() {
        super.onPause();
        Toast toast = Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onResume() {
        super.onResume();
        Toast toast = Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStop() {
        super.onStop();
        Toast toast = Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onDestroy() {
        super.onDestroy();
        Toast toast = Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG);
        toast.show();
    }
}


### activity_main.xml


<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#DB0505"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="serif"
        android:text="hello world"
        android:textColor="#B60FC8"
        android:textSize="24sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>




## PROGRAM:
```
/*
Program to print the text “Implicitintent”.
Developed by: Akhilesh Niyanthran
Registeration Number : 212225220006
*/
```

## OUTPUT
<img width="959" height="560" alt="Screenshot 2026-11-01 220104" src="https://github.com/user-attachments/assets/ad9ab74d-db28-4809-9a29-13daf2078594" />

<img width="1641" height="958" alt="Android Studio Preview with onPause Toast" src="https://github.com/user-attachments/assets/038f94d4-fcc9-4e2a-a866-1ee90f2acf34" />

<img width="1641" height="958" alt="Android Studio Lifecycle Toast Demo" src="https://github.com/user-attachments/assets/b303e379-5883-4b14-9e35-1b26da1bdf7f" />

<img width="959" height="562" alt="Screenshot 2026-11-01 214808" src="https://github.com/user-attachments/assets/63a3ea3d-91f5-49f5-a3d1-5a1c367087d1" />

<img width="959" height="557" alt="Screenshot 2026-11-01 214910" src="https://github.com/user-attachments/assets/4d3192f3-dabc-4eb5-8711-1ec0bdc6ddd1" />

<img width="957" height="554" alt="image" src="https://github.com/user-attachments/assets/8a5e6060-6128-46db-a03b-7d5c328befc5" />


## RESULT
Thus a Simple Android Application create a navigate button using Implicit Intent to display the gmail page using Android Studio is developed and executed successfully.


