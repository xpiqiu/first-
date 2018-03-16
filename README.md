This is an introduction
=
Part1:Adding the new icon to the application
-

Part2:Adding the blue background
-
*revise shape.xml:
```java
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="oval">
    <solid android:color="#31a7dc" />
    <size
        android:width="15dp"
        android:height="15dp" />
</shape>
```
*some layout change:
```java
<TextView
    android:id="@+id/textView"
    android:layout_width="63dp"
    android:layout_height="60dp"
    android:background="@drawable/b
    android:gravity="center"
    android:text="mon"
    android:textAllCaps="true"
    android:textColor="#909090" />
```

Part3:Adding the small circle
-
some layout change:
```java
<ImageView
    android:id="@+id/refresh"
    android:layout_width="48dp"
    android:layout_height="48dp"
    android:layout_alignBottom="@+id/linearLayout"
    android:layout_gravity="center"
    android:layout_marginBottom="16dp"
    android:layout_marginEnd="74dp"
    android:layout_marginRight="74dp"
    android:layout_toLeftOf="@+id/tv_temperature"
    android:layout_toStartOf="@+id/tv_temperature"
    android:onClick="btnClick"
    app:srcCompat="@drawable/available_updates"/>
 ```
 
               
