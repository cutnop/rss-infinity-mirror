# Goal #

My Goal was to create an infinity mirror with a led matrix that would display various news headlines. and by touching the mirror, you can change the news feed.


# Issues #

  * Not really an issue, but the code allocates 62 chars for each headline. So if a headline is really long, it may be cutoff when trying to read it on the display.

  * When the button is pressed to change the RSS feed, you have to wait till the buffered information from the previous feed is displayed and cleared before you see the new RSS feed.