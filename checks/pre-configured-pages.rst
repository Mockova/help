How We Create Pre-configured Checks
===================================

1. The first check we add to the suite is your homepage (this is taken from the
   URL you add as your project).

2. Then, Testomato analyzes your home page and ignores any links that take you
   away from this website (e.g. social links).

3. Next, we sort links by the length of the link text (e.g. About, Contact, Buy,
   etc.). We take the 8 shortest and add them to your dashboard with basic
   configuration.

4. We then add 3 more checks automatically:
   * 404 Not Found Error
   * Favicon
   * robots.txt

5. Finally, we create unconfigured checks for any forms we find on your homepage.
   These checks will appear as gray boxes in your project dashboard.
