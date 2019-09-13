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

#### Table Layout

```
<TableLayout  
  android:layout_width="340dp"  
  android:layout_height="340dp"  
  app:layout_constraintBottom_toBottomOf="parent"  
  app:layout_constraintEnd_toEndOf="parent"  
  app:layout_constraintStart_toStartOf="parent"  
  app:layout_constraintTop_toTopOf="parent">  
  
 <TableRow  android:layout_width="match_parent"  
  android:layout_height="match_parent"  
  android:layout_weight="1">  
  
 <LinearLayout  android:layout_width="340dp"  
  android:layout_height="match_parent"  
  android:orientation="horizontal">  
  
 <Button  android:id="@+id/button4"  
  android:layout_width="wrap_content"  
  android:layout_height="match_parent"  
  android:layout_weight="1"  
  android:background="@mipmap/ic_launcher" />  
  
 <Button  android:id="@+id/button5"  
  android:layout_width="wrap_content"  
  android:layout_height="match_parent"  
  android:layout_weight="1"  
  android:background="@mipmap/ic_launcher" />  
  
 <Button  android:id="@+id/button6"  
  android:layout_width="wrap_content"  
  android:layout_height="match_parent"  
  android:layout_weight="1"  
  android:background="@mipmap/ic_launcher" />  
  
 </LinearLayout> </TableRow>  
 <TableRow  android:layout_width="match_parent"  
  android:layout_height="match_parent"  
  android:layout_weight="1">  
  
 <LinearLayout  android:layout_width="340dp"  
  android:layout_height="match_parent"  
  android:orientation="horizontal">  
  
 <Button  android:id="@+id/button12"  
  android:layout_width="wrap_content"  
  android:layout_height="match_parent"  
  android:layout_weight="1"  
  android:background="@mipmap/ic_launcher" />  
  
 <Button  android:id="@+id/button11"  
  android:layout_width="wrap_content"  
  android:layout_height="match_parent"  
  android:layout_weight="1"  
  android:background="@mipmap/ic_launcher" />  
  
 <Button  android:id="@+id/button7"  
  android:layout_width="wrap_content"  
  android:layout_height="match_parent"  
  android:layout_weight="1"  
  android:background="@mipmap/ic_launcher" />  
  
 </LinearLayout> </TableRow>  
 <TableRow  android:layout_width="match_parent"  
  android:layout_height="match_parent"  
  android:layout_weight="1">  
  
 <LinearLayout  android:layout_width="340dp"  
  android:layout_height="match_parent"  
  android:orientation="horizontal">  
  
 <Button  android:id="@+id/button8"  
  android:layout_width="wrap_content"  
  android:layout_height="match_parent"  
  android:layout_weight="1"  
  android:background="@mipmap/ic_launcher" />  
  
 <Button  android:id="@+id/button9"  
  android:layout_width="wrap_content"  
  android:layout_height="match_parent"  
  android:layout_weight="1"  
  android:background="@mipmap/ic_launcher" />  
  
 <Button  android:id="@+id/button10"  
  android:layout_width="wrap_content"  
  android:layout_height="match_parent"  
  android:layout_weight="1"  
  android:background="@mipmap/ic_launcher" />  
  
 </LinearLayout> </TableRow></TableLayout>
```
