Setting up check50 and submit50 from CS50 to work on local Vscode \

Step 1: Install the relevant pip packages check50 nd submit50 refer to cs50 read the docs for documentation https://cs50.readthedocs.io/github/ \
Step 2: The issue is if your logged into github in your local vscode when you try to use check50 it will go via the deafult route which is password, which is no longer supported
therefore the solution is to logout of ur vscode github, so that it prompts you for ur github username and password, under the password you will key in the token instead \
Step 3: To set up a personal access token https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token follow hte documentation but essentially
just need to go to settings in github, developer settings, then personal access tokens classic, and configure the time and allow the permisions ans save then this token is then used as the password field. 
