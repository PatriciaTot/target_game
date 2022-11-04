## Study of the HTML code of the document

In the HTML code, there are some elements such as "button", "span" and "div". Some of them are identified by their "id" to better differentiate them and target them with the javascript code that will be created.

## Adding a target element

To do this, I first create a function which creates a target thanks to the "target" button and which starts the chronometer after a click on this button. Next, I create the "add_target" function which adds a new target randomly each time in the "field" id element. Next, I create the "remove" function which deletes a target when this element is clicked on. Finally, I create the "remove_target" function which deletes the target and adds a hit class to it before deleting it. But it also removes it from the DOM tree by displaying the effect of the click on this element and its disappearance after 1 second.

## Timer management

A "start_chrono" function is created to start the stopwatch. By clicking on the "Start" button, the stopwatch is started and after each click it is reset to zero. In addition, the old targets are deleted.

## How the game is played

I first create a function that displays the number of targets left to destroy. Then a function that updates the number of targets remaining to be destroyed by subtracting this number each time a target is deleted. Finally, a function that resets the table to empty after clicking on the "Start" button.

## Conclusion

This project was very instructive for me personally. It allowed me to use in a practical way all the knowledge I had acquired in the course and in lectures. In particular, there were some difficulties in creating certain functions, which were remedied later.
