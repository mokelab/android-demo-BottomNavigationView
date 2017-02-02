# android-demo-BottomNavigationView
BottomNavigationView demo - how to change check state

```
Menu menu = bottomNavigationView.getMenu();
MenuItem menuItem = menu.getItem(position);

// Just change checked state
menuItem.setChecked(true);


// change and perform event
// bottomNavigationView.findViewById(menuItem.getItemId()).performClick();
```
