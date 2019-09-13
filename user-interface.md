## User Interface

### Views

#### TextView

```
<TextView  
  android:id="@+id/textView2"  
  android:layout_width="wrap_content"  
  android:layout_height="wrap_content"  
  android:text="TextView"  
  app:layout_constraintEnd_toEndOf="parent"  
  app:layout_constraintStart_toStartOf="parent"  
  app:layout_constraintTop_toTopOf="parent" />
```

#### ImageView

```
<ImageView  
  android:id="@+id/imageView"  
  android:layout_width="wrap_content"  
  android:layout_height="wrap_content"  
  android:layout_marginTop="52dp"  
  app:layout_constraintEnd_toEndOf="parent"  
  app:layout_constraintStart_toStartOf="parent"  
  app:layout_constraintTop_toBottomOf="@+id/textView2"  
  app:srcCompat="@mipmap/ic_launcher" />
```

#### Button

```
<Button  
  android:id="@+id/button"  
  android:layout_width="wrap_content"  
  android:layout_height="wrap_content"  
  android:text="Button"  
  app:layout_constraintEnd_toEndOf="parent"  
  app:layout_constraintStart_toStartOf="parent"  
  app:layout_constraintTop_toTopOf="parent" />
```

### ViewGroups

#### Linear Layout

```
<LinearLayout  
  android:layout_width="match_parent"  
  android:layout_height="340dp"  
  android:orientation="horizontal"  
  app:layout_constraintEnd_toEndOf="parent"  
  app:layout_constraintStart_toStartOf="parent"  
  app:layout_constraintTop_toTopOf="parent">  
  
 <Button  android:id="@+id/button2"  
  android:layout_width="wrap_content"  
  android:layout_height="wrap_content"  
  android:layout_weight="1"  
  android:text="Button" />  
  
 <Button  android:id="@+id/button4"  
  android:layout_width="wrap_content"  
  android:layout_height="wrap_content"  
  android:layout_weight="1"  
  android:text="Button" />  
  
 <Button  android:id="@+id/button3"  
  android:layout_width="wrap_content"  
  android:layout_height="wrap_content"  
  android:layout_weight="1"  
  android:text="Button" />  
</LinearLayout>
```
