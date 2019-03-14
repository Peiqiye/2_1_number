# 2_1_number
LinearLayout,ConstraintLayout,TableLayout
--------------------------------------------------------------
1.利用线性布局实现界面。
主要代码：
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"


    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:orientation="vertical"
   >
    <LinearLayout

        android:layout_width="match_parent"
        android:layout_height="match_parent"
         >

        <Button
            android:id="@+id/btn_1"
            style="?android:attr/buttonBarButtonStyle"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:background="@drawable/buttonstyle"
            android:text="@string/btn_1"
            android:textAllCaps="true" />

        <Button
            android:id="@+id/btn_2"
            style="?android:attr/buttonBarButtonStyle"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="50"
            android:background="@drawable/buttonstyle"
            android:text="@string/btn_2" />

        <Button
            android:id="@+id/btn_3"
            style="?android:attr/buttonBarButtonStyle"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:background="@drawable/buttonstyle"
            android:text="@string/btn_3" />

        <Button
            android:id="@+id/btn_4"
            style="?android:attr/buttonBarButtonStyle"
            android:layout_width="104dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:background="@drawable/buttonstyle"
            android:text="@string/btn_4" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <Button
            android:id="@+id/btn_5"
            style="?android:attr/buttonBarButtonStyle"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:background="@drawable/buttonstyle"
            android:text="@string/btn_5" />

        <Button
            style="?android:attr/buttonBarButtonStyle"
            android:id="@+id/btn_6"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:background="@drawable/buttonstyle"
            android:text="@string/btn_6" />

        <Button
            style="?android:attr/buttonBarButtonStyle"
            android:id="@+id/btn_7"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1.2"
            android:text="@string/btn_7"
            android:background="@drawable/buttonstyle"/>

        <Button
            style="?android:attr/buttonBarButtonStyle"
            android:id="@+id/btn_8"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="@string/btn_8"
            android:background="@drawable/buttonstyle"/>

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        >

        <Button
            style="?android:attr/buttonBarButtonStyle"
            android:id="@+id/btn_9"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="2"
            android:text="@string/btn_9"
            android:background="@drawable/buttonstyle"/>

        <Button
            style="?android:attr/buttonBarButtonStyle"
            android:id="@+id/btn_10"
            android:layout_width="85dp"
            android:layout_height="wrap_content"
            android:layout_weight="0.8"
            android:text="@string/btn_10"
            android:background="@drawable/buttonstyle"/>

        <Button
            style="?android:attr/buttonBarButtonStyle"
            android:id="@+id/btn_11"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="2"
            android:text="@string/btn_11"
            android:background="@drawable/buttonstyle"/>
        <Button
            style="?android:attr/buttonBarButtonStyle"
            android:id="@+id/btn_12"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="0.8"
            android:text="@string/btn_12"
            android:background="@drawable/buttonstyle"/>

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        >

        <Button
            style="?android:attr/buttonBarButtonStyle"
            android:id="@+id/btn_13"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="0.8"
            android:text="@string/btn_13"
            android:background="@drawable/buttonstyle"/>

        <Button
            style="?android:attr/buttonBarButtonStyle"
            android:id="@+id/btn_14"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="0.8"
            android:text="@string/btn_14"
            android:background="@drawable/buttonstyle"/>

        <Button
            style="?android:attr/buttonBarButtonStyle"
            android:id="@+id/btn_15"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1.6"
            android:text="@string/btn_15"
            android:background="@drawable/buttonstyle"/>
        <Button
            style="?android:attr/buttonBarButtonStyle"
            android:id="@+id/btn_16"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1.6"
            android:text="@string/btn_16"
            android:background="@drawable/buttonstyle"/>

    </LinearLayout>

</LinearLayout>
运行结果：

------------------------------------------------------------------------------

2.利用约束布局实现界面。
主要代码：
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".Main2Activity"
    tools:layout_editor_absoluteY="89dp">

    <TextView
        android:id="@+id/t1"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:layout_marginEnd="236dp"
        android:layout_marginBottom="279dp"
        android:background="@color/color1"
        android:gravity="center"
        android:text="@string/t1"
        android:textColor="@color/colorPrimary"
        app:layout_constraintBottom_toTopOf="@+id/t7"
        app:layout_constraintEnd_toStartOf="@+id/t2"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.12" />

    <TextView
        android:id="@+id/t2"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:layout_marginEnd="294dp"
        android:layout_marginBottom="91dp"
        android:background="@color/color2"
        android:gravity="center"
        android:text="@string/t2"
        android:textColor="@color/colorPrimary"
        app:layout_constraintBottom_toTopOf="@+id/t5"
        app:layout_constraintEnd_toStartOf="@+id/t3"
        app:layout_constraintStart_toEndOf="@+id/t1"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />

    <TextView
        android:id="@+id/t3"
        android:layout_width="0dp"
        android:layout_height="97dp"
        android:layout_marginBottom="145dp"
        android:background="@color/color3"
        android:gravity="center"
        android:text="@string/t3"
        android:textColor="@color/colorPrimary"
        app:layout_constraintBottom_toTopOf="@+id/t6"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toEndOf="@+id/t2"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />

    <TextView
        android:id="@+id/t4"
        android:layout_width="0dp"
        android:layout_height="100dp"
        android:layout_marginStart="182dp"
        android:layout_marginTop="187dp"
        android:layout_marginEnd="42dp"
        android:layout_marginBottom="90dp"
        android:background="@color/color4"
        android:gravity="center"
        android:text="@string/t4"
        android:textColor="@color/colorPrimary"
        app:layout_constraintBottom_toTopOf="@+id/t7"
        app:layout_constraintEnd_toStartOf="@+id/t5"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/t5"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:layout_marginEnd="48dp"
        android:layout_marginBottom="176dp"
        android:background="@color/color5"
        android:gravity="center"
        android:text="@string/t5"
        android:textColor="@color/colorPrimary"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@+id/t6"
        app:layout_constraintStart_toEndOf="@+id/t4"
        app:layout_constraintTop_toBottomOf="@+id/t2" />

    <TextView
        android:id="@+id/t6"
        android:layout_width="0dp"
        android:layout_height="103dp"
        android:layout_marginEnd="235dp"
        android:background="@color/color6"
        android:gravity="center"
        android:text="@string/t6"
        android:textColor="@color/colorPrimary"
        app:layout_constraintBaseline_toBaselineOf="@+id/t5"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toEndOf="@+id/t5" />

    <TextView
        android:id="@+id/t7"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:layout_marginBottom="7dp"
        android:background="@color/color7"
        android:gravity="center"
        android:text="@string/t7"
        android:textColor="@color/colorPrimary"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/t4" />


</android.support.constraint.ConstraintLayout>
------------------------------------------------------------------------------
3.利用表格布局实现界面。
主要代码：
<?xml version="1.0" encoding="utf-8"?>
<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:stretchColumns="6"
    tools:context=".Main3Activity">

    <TableRow>

        <TextView
            android:id="@+id/t01"
            android:layout_width="72dp"
            android:layout_height="30dp"
            android:text="@string/t01" />

        <TextView
            android:id="@+id/t07"
            android:layout_width="195dp"
            android:layout_height="match_parent"
            android:gravity="end"
            android:text="@string/t07" />

    </TableRow>

    <TableRow>

        <TextView
            android:id="@+id/t02"
            android:layout_width="45dp"
            android:layout_height="30dp"
            android:text="@string/t02" />

        <TextView
            android:id="@+id/t08"
            android:layout_width="50dp"
            android:layout_height="30dp"
            android:gravity="end"
            android:text="@string/t08" />

    </TableRow>

    <TableRow>

        <TextView
            android:id="@+id/t03"
            android:layout_width="wrap_content"
            android:layout_height="30dp"
            android:background="@drawable/buttonstyle1"
            android:text="@string/t03" />
        <TextView
            android:id="@+id/t09"
            android:layout_width="287dp"
            android:layout_height="30dp"
            android:background="@drawable/buttonstyle1"
            android:gravity="end"
            android:text="@string/t09" />
    </TableRow>

    <TableRow>

        <TextView
            android:id="@+id/t04"
            android:layout_width="match_parent"
            android:layout_height="30dp"
            android:text="@string/t04" />

    </TableRow>

    <TableRow>

        <TextView
            android:id="@+id/t05"
            android:layout_width="match_parent"
            android:layout_height="30dp"
            android:background="@drawable/buttonstyle1"
            android:text="@string/t05" />
        <TextView
            android:id="@+id/t10"
            android:layout_width="287dp"
            android:layout_height="30dp"
            android:background="@drawable/buttonstyle1"
            android:gravity="end"
            android:text="@string/t10" />
    </TableRow>

    <TableRow>

        <TextView
            android:id="@+id/t06"
            android:layout_width="match_parent"
            android:layout_height="30dp"
            android:text="@string/t06" />

    </TableRow>
</TableLayout>


