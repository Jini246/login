<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:background="@drawable/red_button_bg"
    tools:context=".activities.LoginActivity">

    <LinearLayout
        android:padding="10dp"
        android:gravity="center"
        android:orientation="vertical"
        android:layout_width="match_parent"
        android:layout_height="match_parent">
        <LinearLayout
            android:layout_marginTop="20dp"
            android:layout_gravity="center"
            android:orientation="vertical"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content">

            <ImageView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:background="@drawable/circle"
                android:src="@mipmap/blood_bank_icon_round" />
            <LinearLayout
                android:layout_marginTop="10dp"
                android:orientation="horizontal"
                android:layout_width="match_parent"
                android:layout_height="wrap_content">
                <ImageView
                    android:layout_weight="1"
                    android:src="@drawable/facebook_circle"
                    android:layout_width="30dp"
                    android:layout_height="30dp" />

                <ImageView
                    android:layout_width="30dp"
                    android:layout_height="30dp"
                    android:layout_weight="1"
                    android:src="@drawable/twitter_512" />
            </LinearLayout>

        </LinearLayout>

        <EditText
            android:textColor="@android:color/white"
            android:id="@+id/input_username"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:inputType="textEmailAddress"
            android:hint="@string/prompt_email" />

        <EditText
            android:textColor="@android:color/white"
            android:id="@+id/input_password"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:inputType="textPassword"
            android:hint="@string/prompt_password" />

        <Button
            android:textAllCaps="false"
            android:id="@+id/button_login"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="20dp"
            android:textStyle="bold"
            android:background="@drawable/signin_btn"
            android:textColor="@color/primary"
            android:text="@string/action_sign_in_short" />

        <Button
            android:textAllCaps="false"
            android:id="@+id/button_register"
            android:layout_width="wrap_content"
            android:layout_marginTop="20dp"
            android:layout_height="wrap_content"
            android:padding="2dp"
            android:textColor="@android:color/white"
            android:background="@drawable/transparent_black_ten_percent"
            android:text="@string/register" />

        <Button
            android:textAllCaps="false"
            android:id="@+id/button_forgot_password"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:padding="2dp"
            android:textColor="@android:color/white"
            android:background="@drawable/transparent_black_ten_percent"
            android:text="@string/forgotpass" />

    </LinearLayout>

</ScrollView>
© 2020 GitHub, Inc.
