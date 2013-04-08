Random Quoter
=============

Fork this repo and complete the following:

## Enable the Button

Clicking the button should:

1. Pick a random quote to load.
2. Make an AJAX request to the randomly selected quote HTML file.

## Replace the Quote

After the AJAX request returns successfully:

1. Slide up or fade out (your choice) the `#quote-wrapper` div.
2. Remove the contents of the `#quote-wrapper` div.
3. Add the new quote to `#quote-wrapper`.
4. Using the reverse effect from step #1 (slideDown/fadeIn), display the new quote.

## Finish The Responsiveness

Add media queries for 768px and 1024px. Make sure a noticeable change happens! Something like:

- Increased font size
- Increased `#wrapper` width
- Altered colors

Use transitions if you're feeling snazzy.

## More Fun Times

If you finish the above and are hungry for more, try the following:

1. Make sure you only load each quote once. Do not make another AJAX request if you've already loaded the randomly chosen quote.
2. Load a random quote when the page loads (lose the 'Click the button...' text).