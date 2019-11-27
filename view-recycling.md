## View Recycling

### Loop through arraylist and add views to layouts

```
ArrayList<String> words = new ArrayList<String>();

//Add elements to ArrayList
words.add("C");
words.add("C++");
words.add("Java");
words.add("DotNet");
words.add("Perl");

int count = 0;
LinearLayout rootViewLayout = (LinearLayout) findViewById(R.id.rootView);

while (words.size() > count) {
//            Log.d("NumbersActivity", words.get(count));
    TextView textView = new TextView(this);
    textView.setText(words.get(count));
    rootViewLayout.addView(textView);
    count++;
}
```
