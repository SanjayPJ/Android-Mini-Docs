
## Basic Interaction

### Functions

```
public void function_name(View view){
	// do something here
}
```

*inside MainActivity.java*

### To get content of a text area

```
EditText password = (EditText) findViewById(R.id.password);
```

### Set Text on a TextView

```
password.setText(message);
```

#### To show EditText

```
user_name.getText().toString()
```

### To show a toast

```
Toast.makeText(this, "show this", Toast.LENGTH_SHORT).show();
```

### To show debug log

```
Log.d("myTag", "This is a message");
```

### Hide Topbar

```
getSupportActionBar().hide();
```

*inside onCreate*

### Iterate Through Layouts

```
for(int i=0; i<myGridView.getChildCount(); i++) {
    TextView child = (TextView)mGridView.getChildAt(i);
    // do stuff with child view
}
```

### Getting values from checkbox

```
CheckBox chocolateCheckBox = (CheckBox) findViewById(R.id.chocolate_checkbox);
boolean hasChocolate = chocolateCheckBox.isChecked();
```
