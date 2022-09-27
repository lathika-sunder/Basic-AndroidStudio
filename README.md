# Basic-AndroidStudio
~~~
Developed: G venkata Pavan Kumar
Registered Number: 212221240013
~~~
## MainActivity.java
~~~
package com.sanath.lifecycle;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);




        Toast toast = Toast.makeText(getApplicationContext(), "OnCreate Executed", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStart(){
        super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStart Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onResume(){
        super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),"OnResume Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onPause(){
        super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"OnPause Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStop(){
        super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStop Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onRestart(){
        super.onRestart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onDestroy(){
        super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Executed",Toast.LENGTH_LONG);
        toast.show();
    }
}
~~~
## activity_main.xml
~~~
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="HelloWorld!"
        android:layout_centerVertical="true"
        android:layout_centerHorizontal="true"
        android:textSize="20sp"
        android:textColor="@color/black"

        />
</RelativeLayout>
~~~
### Output
![java1](https://user-images.githubusercontent.com/94827772/192425369-77fb107d-a4ea-41c5-a473-842cf5765216.jpg)
![java2](https://user-images.githubusercontent.com/94827772/192425377-dd2c78bf-f5cb-47f0-bcf4-3f24b49d8d62.jpg)
![java3](https://user-images.githubusercontent.com/94827772/192425381-e81f0b46-185f-4e08-b27e-7b051140d3f6.jpg)
![java4](https://user-images.githubusercontent.com/94827772/192425384-79c945f5-bc16-4ec2-acb5-0538e7432169.jpg)
![java5](https://user-images.githubusercontent.com/94827772/192425387-e2185a78-e184-4e36-9f59-0860d76d556d.jpg)
![java6](https://user-images.githubusercontent.com/94827772/192425389-364071b5-1c59-44d4-82cc-5746a6ee01b0.jpg)
![java7](https://user-images.githubusercontent.com/94827772/192425390-7d34f9ee-24ff-4d34-b85b-831bbae4be83.jpg)


### Result:
Therefore a program is return to develop a program to detect the various life cycles of an activity. The program is successfully executed.

