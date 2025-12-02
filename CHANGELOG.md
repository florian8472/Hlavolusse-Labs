Steps I did initially: removed the UW link from hlab.science and linked Netlify
In Netlify, I opted to deploy my homepage from GitHub
I don't remember how I did these first two steps, but GPT-5 helped and I can ask it again
Used two websites and one editor
Netlify and Github are the two websites
Editor = Visual Studio Code (VSD; program on my desktop)
Also downloaded Git to my desktop, which allows me to push code from Github to Netlify
Important: first download VSD. Use default installation settings. 
Then download Git. During installation, select VSD as the default Git editor! Other than that, use default installation settings. 
Created a folder in the folder 'Website' on my computer (or rather S Laptop Florian 2021)
This folder is named Hlavolusse-Labs and contains all the relevant files for the homepage 
The index.html file is the file that defines the structure of the homepage
Other files, such as 'publications' are for the different sections of the homepage
Under 'assets', there are files such as the styles file in the css folder 
For making changes to the homepage, I need to first change the code of the respective file
For example, I open styles.css via VSD and type the changes, or copy in a replacement code, and then save the new file
Then I have to push this file change to Git
I do this by opening the Terminal in VS (Ctrl `), and then type:
git add .
git commit -m "Update About section and color scheme"
git push
Then Netlify will auto-build and deploy
HTML is the skeleton of a website (defines structure and content) - WHAT you see
CSS defines the style and appearance of the HTML elements - HOW IT LOOKS
HTML and CSS are two different languages that work together to build websites, but they serve very different purposes
HTML says: “Here’s a button.”
CSS says: “Make that button gold with white text and rounded corners.”
For a photo: place it as JPG file into the assets/img folder
hlab.science has IP address: 13.52.188.95
On December 1st 2025, I copied the folders and files containing the coding my our homepage into "J:\Website\Hlavolusse-Labs"
This is now the local repo from where changes are pushed to the Remote repo on Github
Local repo: On your computer (like J:\Website\Hlavolusse-Labs)
Remote repo: On a server (like GitHub)
Netlify builds your site from the remote Github repo whenever you push changes
When I changed the server hosting my homepage files, I had to designate them again as a Git repository
On the computer terminal, I added: 
cd /path/to/homepage
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/florian8472/Hlavolusse-Labs.git
git push -u origin main