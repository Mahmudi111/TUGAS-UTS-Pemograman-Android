# TUGAS-UTS-Pemograman-Android
TUGAS UTS Pemograman Android
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <ImageView
        android:background="@color/colorPrimaryDark"
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:contentDescription="TODO" />
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="0dp"/>
   <LinearLayout
       android:orientation="vertical"
       android:layout_width="match_parent"
       android:layout_height="match_parent">

       <LinearLayout
           android:background="@drawable/la"
           android:orientation="vertical"
           android:layout_weight="1"
           android:gravity="center"
           android:layout_width="match_parent"
           android:layout_height="0dp">

           <ImageView
               android:layout_width="140dp"
               android:layout_height="140dp"
               android:background="@color/colorPrimary"
               android:src="@drawable/masjid" />

           <TextView
               android:text="MARHABAN YA RAMADHAN"
               android:layout_marginTop="20dp"
               android:textColor="@android:color/black"
               android:textStyle="bold"
               android:textSize="20dp"
               android:layout_width="wrap_content"
               android:layout_height="wrap_content"/>
           <TextView
               android:text="1441 H"
               android:layout_marginTop="5dp"
               android:textColor="@android:color/black"
               android:textSize="20dp"
               android:textStyle="bold"
               android:layout_width="wrap_content"
               android:layout_height="wrap_content" />

       </LinearLayout>


            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="2"
                android:background="#3c5e5e"
                android:orientation="horizontal">

                    <LinearLayout
                        android:layout_width="0dp"
                        android:layout_height="match_parent"
                        android:layout_weight="1"
                        android:gravity="center_horizontal"
                        android:orientation="vertical">

                        <ImageButton
                            android:layout_width="180dp"
                            android:layout_height="160dp"
                            android:background="@android:color/darker_gray"
                            android:src="@drawable/buku" />
                        <TextView
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="Kajian islam"
                            android:textColor="@android:color/white"
                            android:textSize="20dp" />

                        <ImageButton
                            android:layout_width="180dp"
                            android:layout_height="160dp"
                            android:layout_marginTop="30dp"
                            android:background="@android:color/darker_gray"
                            android:src="@drawable/aaa" />

                        <TextView
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="Doa-Doa"
                            android:textColor="@android:color/white"
                            android:textSize="20dp" />

           </LinearLayout>

           <LinearLayout
               android:layout_width="0dp"
               android:layout_height="match_parent"
               android:layout_gravity="center_horizontal"
               android:layout_weight="1"
               android:orientation="vertical">

               <ImageButton
                   android:layout_width="180dp"
                   android:layout_height="160dp"
                   android:background="@android:color/darker_gray"
                   android:src="@drawable/quran" />

               <TextView
                   android:layout_width="153dp"
                   android:layout_height="wrap_content"
                   android:text="Tafsir Al Quran"
                   android:textColor="@android:color/white"
                   android:textSize="20dp" />

               <ImageButton
                   android:layout_width="180dp"
                   android:layout_height="160dp"
                   android:layout_marginTop="30dp"
                   android:background="@android:color/darker_gray"
                   android:src="@drawable/jamdin"/>
               <TextView
                   android:layout_width="wrap_content"
                   android:layout_height="wrap_content"
                   android:text="Jadwal Sholat"
                   android:textColor="@android:color/white"
                   android:textSize="20dp"/>

           </LinearLayout>

       </LinearLayout>

   </LinearLayout>
</LinearLayout>
