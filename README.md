# Alfred: Shorten URLS with YOURLS
An Alfred Workflow for shortening URLs via a self-hosted YOURLS installation. Shorten clipboard content with YOURLS, then copy short URL to clipboard.

## SETUP
Fill out the configuration settings (or edit the "Run Script" utility). You will need to insert the url of your YOURLS installation and your signature token, which you find by going to your Admin Interface and clicking on "Tools".
The workflow itself works via the keyword "short", though you can change that of course, and it looks for the URL in your clipboard. The resulting short URL is then again copied to your clipboard. Optionally you can type something after the keyword, so something like "short newlink" would shorten whatever URL you have copied to "http://your.site/newlink" and copy that to your clipboad.
