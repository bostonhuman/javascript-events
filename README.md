# javascript-events
In this example, when the mouse moves over a list item, the content of its id attribute is written into the list item. The same happens if the user clicks on a list item because mouseover does not work on touchscreen devices. The mouseout event also removes this extra information from the page to prevent the added content building up.

# Components that make the app run

* The selector finds all list items on the page. The resulting jQuery on the page. The resulting jQuery object is used more than once, so it is stored in a variable called $listItems.
* The .on() method creates an event listener, which waits for when the user moves a mouse over a list item or clicks on it. It triggers an anonymous function.
* Note how the two events are specified in the same set of quote marks, with a space between them. The .mouseout() method triggers the removal of any child span elements to prevent build-up of added values.

## How to run the app
* In your terminal:
```
git clone https://github.com/bostonhuman/javascript-events
```
* Open `events.html` to run the app.
