# Restaurant-CM
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    tools:context="com.facci.restaurantcm.MainActivityCM"
    android:orientation="vertical">


    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textAppearance="?android:attr/textAppearanceLarge"
        android:text="Restaurant CM "
        android:id="@+id/tituloTV"
        android:layout_gravity="center_horizontal" />


    <GridLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:columnCount="23"
        android:rowCount="4">

        <ImageButton
            android:layout_width="wrap_content"
            android:layout_height="100dp"
            android:id="@+id/imagen1CM"
            android:layout_row="0"
            android:layout_column="0"
            android:layout_columnSpan="2"
            android:src="@drawable/uno"
            android:scaleType="centerCrop"
            android:layout_marginTop="30dp"
            android:onClick="click1"/>

    <ImageButton
        android:layout_width="200dp"
        android:layout_height="50dp"
        android:id="@+id/imagen2CM"
        android:layout_row="1"
        android:layout_column="0"
        android:src="@drawable/dos"
        android:scaleType="centerCrop"
        android:layout_marginTop="30dp"
        android:onClick="click2"/>

        <ImageView
            android:layout_width="200dp"
            android:layout_height="60dp"
            android:id="@+id/imagenCM"
            android:layout_row="1"
            android:layout_column="1"
            android:src="@drawable/tres"
            android:scaleType="centerCrop"
            android:layout_marginTop="30dp"
            android:onClick="click3"/>

        <ImageButton
            android:layout_width="200dp"
            android:layout_height="100dp"
            android:id="@+id/imagen4CM"
            android:layout_row="3"
            android:layout_column="1"
            android:src="@drawable/cuatro"
            android:scaleType="centerCrop"
            android:layout_marginTop="30dp"
            android:onClick="click4" />

        <ImageView
            android:layout_width="200dp"
            android:layout_height="100dp"
            android:id="@+id/imaagen5CM"
            android:layout_row="2"
            android:layout_column="1"
            android:src="@drawable/cinco"
            android:scaleType="centerCrop"
            android:layout_marginTop="30dp"
            android:onClick="click5" />

        <ImageButton
            android:layout_width="200dp"
            android:layout_height="100dp"
            android:id="@+id/imagen6CM"
            android:layout_row="2"
            android:layout_column="0"
            android:src="@drawable/seis"
            android:scaleType="centerCrop"
            android:layout_marginTop="30dp"
            android:onClick="click6"/>

        <ImageView
            android:layout_width="200dp"
            android:layout_height="100dp"
            android:id="@+id/imagen7CM"
            android:layout_row="3"
            android:layout_column="0"
            android:src="@drawable/siete"
            android:scaleType="centerCrop"
            android:layout_marginTop="30dp"
            android:onClick="click7"/>


    </GridLayout>
</LinearLayout>

package com.facci.restaurantcm;

//CECILIA LISBETH MOREIRA CEVALLOS
//4 NIVEL "B"
import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.Toast;

public class MainActivityJA extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main_activity_j);
    }
    public void click1(View v){
        Toast.makeText(MainActivityJA.this,"Bocaditos Manabas",Toast.LENGTH_SHORT).show();
    }

    public void click2(View v){
        Toast.makeText(MainActivityJA.this,"Caldo de Gallina",Toast.LENGTH_SHORT).show();
    }

    public void click3(View v){
        Toast.makeText(MainActivityJA.this,"Ceviche de Pescado",Toast.LENGTH_SHORT).show();
    }

    public void click4(View v){
        Toast.makeText(MainActivityJA.this,"Cangrejada",Toast.LENGTH_SHORT).show();
    }

    public void click5(View v){
        Toast.makeText(MainActivityJA.this,"Encebollado",Toast.LENGTH_SHORT).show();
    }

    public void click6(View v){
        Toast.makeText(MainActivityJA.this,"Encocado de Pescado",Toast.LENGTH_SHORT).show();
    }

    public void click7(View v){
        Toast.makeText(MainActivityJA.this,"Apanado",Toast.LENGTH_SHORT).show();
    }
}
