# relativelayout
relativelayout
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:layout_margin="6dp"
    tools:context=".MainActivity"
    >

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="250dp"
        android:src="@drawable/a_1"
        android:scaleType="centerCrop"

        />


    <Button
      android:layout_width="150dp"
      android:layout_height="wrap_content"
      android:layout_centerVertical="true"
        android:text="salim"

        />

    <TextView
        android:layout_width="150dp"
        android:layout_height="45dp"
        android:layout_centerVertical="true"
        android:layout_alignParentEnd="true"
        android:background="#48CCCD	"
        android:gravity="center"
        android:text="@string/_1000"
        android:textSize="18sp"
        android:textStyle="bold" />

    <ImageView
        android:id="@+id/a"
        android:layout_width="114dp"
        android:layout_height="249dp"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="12dp"
        android:layout_marginLeft="7dp"
        android:layout_marginEnd="12dp"
        android:layout_marginRight="6dp"
        android:scaleType="centerCrop"
        android:src="@drawable/az_2"
        android:contentDescription="TODO" />

    <ImageView
        android:layout_width="125dp"
        android:layout_height="250dp"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_toStartOf="@id/a"
        android:scaleType="centerCrop"
        android:src="@drawable/ag_3" />

    <ImageView
        android:layout_width="125dp"
        android:layout_height="250dp"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_toEndOf="@id/a"
        android:scaleType="centerCrop"
        android:src="@drawable/mag_4"
         />

</RelativeLayout>
