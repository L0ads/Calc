<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="sans-serif-condensed"
        android:text="Привет"
        android:textSize="30sp"
        android:textStyle="bold"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintHorizontal_bias="0.398"
        app:layout_constraintLeft_toLeftOf="parent"

        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.39" />

    <Button
        android:id="@+id/button"
        android:layout_width="100dp"
        android:layout_height="57dp"
        android:layout_marginEnd="4dp"
        android:text="Нажми сюда"
        android:textColor="#F60B0B"
        app:layout_constraintEnd_toStartOf="@+id/switch1"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteY="412dp" />

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="191dp"
        android:layout_height="179dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.254"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.106"
        tools:srcCompat="?attr/homeAsUpIndicator" />

    <Switch
        android:id="@+id/switch1"
        android:layout_width="114dp"
        android:layout_height="78dp"
        android:text="Сменить тему"
        tools:layout_editor_absoluteX="296dp"
        tools:layout_editor_absoluteY="101dp" />


</androidx.constraintlayout.widget.ConstraintLayout>
