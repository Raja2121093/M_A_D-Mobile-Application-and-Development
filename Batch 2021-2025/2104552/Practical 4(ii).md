# Develop a program to implement linear layout to display send message and registration form (vertical and horizontal).
## code
```xml
<?xml version="1.0" encoding="utf-8"?>
<FrameLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingTop="40dp">

    <!-- Title TextView -->
    <TextView
        android:layout_width="420dp"
        android:layout_height="wrap_content"
        android:layout_gravity="top|center_horizontal"
        android:background="#6200EE"
        android:padding="8dp"
        android:text="LinearLayout"
        android:textAlignment="center"
        android:textColor="#FFFFFF"
        android:textSize="30dp"
        android:textStyle="bold" />

    <!-- Separate LinearLayout Content -->
    <LinearLayout
        android:id="@+id/main"
        android:layout_width="match_parent"
        android:layout_height="397dp"
        android:layout_marginTop="30dp"
        android:layout_marginBottom="90sp"
        android:orientation="vertical">

        <!-- "To" Field -->
        <TextView
            android:layout_width="match_parent"
            android:layout_height="55dp"
            android:padding="10dp"
            android:text="To"
            android:textColor="#000000"
            android:textSize="16sp" />

        <View
            android:layout_width="match_parent"
            android:layout_height="1dp"
            android:background="#000000" />

        <TextView
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:padding="10dp"
            android:text="Subject"
            android:textColor="#000000"
            android:textSize="16sp" />

        <View
            android:layout_width="match_parent"
            android:layout_height="1dp"
            android:background="#000000" />
        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:padding="10dp"
            android:text="Message"
            android:textColor="#000000"
            android:textSize="16sp" />
        <View
            android:layout_width="match_parent"
            android:layout_height="1dp"
            android:background="#000000" />

    </LinearLayout>

    <!-- Send Button positioned at the bottom right corner -->
    <Button
        android:layout_width="120dp"
        android:layout_height="50dp"
        android:layout_gravity="bottom|end"
        android:background="#6200EE"
        android:padding="10dp"
        android:text="Send"
        android:textColor="#FFFFFF"
        android:layout_margin="16dp" />

</FrameLayout>
```
## Output
![WhatsApp Image 2024-09-28 at 16 53 34_43f8d68d](https://github.com/user-attachments/assets/ee88d7e2-519f-4395-91bc-28e7215e83e3)
