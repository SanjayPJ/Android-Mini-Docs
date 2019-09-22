### Adding custom styles

*inside styles.xml*
```
<?xml version="1.0" encoding="utf-8"?>  
<resources>  
<style  name="GreenText"  parent="TextAppearance.AppCompat">  
	<item name="android:textColor">#00FF00</item>  
</style>  
</resources>
```

*inside each component*

```
style="@style/GreenText"
```

### Themes

*inside styles.xml*
```
<style name="AppTheme" parent="Theme.AppCompat.Light.DarkActionBar">  
  <!-- Customize your theme here. -->  
  <item name="colorPrimary">#3F51B5</item>  
 <item name="colorPrimaryDark">#303F9F</item>  
 <item name="colorAccent">#C5CAE9</item>  
</style>
```
