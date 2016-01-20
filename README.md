# Randomizer

Randomizer redirects the user (i.e., the web browser) to a random URL from a custom list of URLs.

Randomizer is built	with the intent of randomization in a controlled experiment.

For now, there is only a HTML file with JavaScript. But more languages are hopefully supported later.

## Example Usage

For example, create three Google Docs forms (or equivalent) and add their URLs to the list in the file. That's it!

The user is then automatically and randomly assigned to one of the URLs when the user visits this file. If the user decides to close and reopen the browser, the user is still redirected to the same URL since a cookie is saved in the web browser.

## Contact
	
Please contact me at <a href="http://twitter.com/peterdalle">@peterdalle</a> or <a href="http://peterdahlgren.com/">peterdahlgren.com</a> if you have any questions.

## How do I edit Randomizer?

1. Download or git clone.
2. Edit the file <code>randomize.html</code> and edit the URLs at these lines:
<pre> 	// List of URLs (two or more) for the experimental treatment and control groups.
		var RedirectURLs = {
			"urls" : [
				{ "url" : "http://www.aftonbladet.se/" },
				{ "url" : "http://www.dn.se/" },
				{ "url" : "http://www.svd.se/" }
			]
		}</pre>
