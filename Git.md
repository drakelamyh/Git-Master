# Git Commands



## Copy old repo from Github and push edits back into Github

Open up Command Prompt (search for CMD).

To navigate to desired folder to clone repo to, use the CMD command:

- `cd Desktop`

Clone repo in Github into a new folder on computer at desired folder location:

`git clone https://github.com/drakelamyh/AlphaBravo.git`

CMD command to navigate to new repo folder cloned:

`cd AlphaBravo`

Indicate the specific file that is amended and needs to be uploaded

`git add Charlie.py`

Alternatively, indicate all amended files to be uploaded

`git add .`

Record intended changes to the online repo with custom comments

`git commit -m "Comment Here"`

Check which Github branch you are in. If you are pushing into the main branch, make sure it shows as * main

`git branch`

Push files into * main branch. Git will authenticate with browser to make sure you have password to the Github account.

`git push origin main`

Use this command instead if top branch is named as * master instead.

`git push origin master`




