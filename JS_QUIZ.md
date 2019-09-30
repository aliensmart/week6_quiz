## Javascript Quiz:

### API Lookup

Write a javascript program and HTML file with a text input field, a button, and two count elements that display a 0.

The user can submit a choice, 'yes' or 'no'.

Then use this api `https://yesno.wtf/api` to generate a random yes or no response.

If the user's response matches the output, render an HTML element that displays whether they guessed correctly.

Regardless of the outcome, you should also increment the count element for that response so we can track how many 'yes' responses and how many 'no' responses we've received.

All responses will be of the format `{"answer":"no","forced":false,"image":"https://yesno.wtf/assets/no/26-34b31d1f0777f70c61488f67a36576a9.gif"}`.

For extra credit (or if you finish early), you can try to render the `.gif` on the page.
