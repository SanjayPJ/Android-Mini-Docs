## Creating Intents

#### Create a geolocation intent
```
Intent intent = new Intent(Intent.ACTION_VIEW);  
intent.setData(Uri.parse("geo:0,0?q=37.423156,-122.084917"));  
if (intent.resolveActivity(getPackageManager()) != null) {  
    startActivity(intent);  
}
```

#### Create a email intent
```
public void composeEmail(String[] addresses, String subject, String order_summary) {  
    Intent intent = new Intent(Intent.ACTION_SEND);  
  intent.setType("text/plain");  
  intent.putExtra(Intent.EXTRA_EMAIL, addresses);  
  intent.putExtra(Intent.EXTRA_SUBJECT, subject);  
  intent.putExtra(Intent.EXTRA_TEXT, order_summary);  
 if (intent.resolveActivity(getPackageManager()) != null) {  
        startActivity(intent);  
  }  
}

// call this function like this

String main_addresses[] = { "sanjaypj@gmail.com" };  
composeEmail(main_addresses, "order", order_summary);
```

### Creating Activities

- *right click on app folder*
- *select new*
- *select activity*
- *select empty activity*
- *enter activity name*

#### Start new activity

```
Intent intent = new Intent(this, NumbersActivity.class);  
startActivity(intent);
```

