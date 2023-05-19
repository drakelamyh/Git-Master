# Git Commands



## Copy old repo from Github and push edits back into Github

Use Command Prompt (search for CMD)

To navigate to desired folder to copy repo to
`cd Desktop`

Clone repo in Github into a new folder on computer
`git clone https://github.com/drakelamyh/AlphaBravo.git`

CMD command to navigate to repo folder
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

Use this command instead of main branch is named as * master instead.
`git push origin master`



