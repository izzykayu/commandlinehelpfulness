#Example of git new repo in command line

`echo "# commandlinehelpfulness" >> README.md`
`git init`
`git add README.md`
`git commit -m "first commit"`
`git remote add origin https://github.com/izzykayu/commandlinehelpfulness.git`
`git push -u origin master`

#Example of generating ssh keys on macOS
`cd ~/.ssh`
`ls id_*` 
Above command is go check what ids are currently present
Then you can copy these keys to backup dir
`mkdir key_backup`
`cp id_rsa* key_backup`
`ssh-keygen -t rsa -C "please_put_email_address@example.com"`
