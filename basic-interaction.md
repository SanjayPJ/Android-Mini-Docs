
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

#### To show EditText

```
user_name.getText().toString()
```

### To show a toast

```
Toast.makeText(this, "show this", Toast.LENGTH_SHORT).show();
```

