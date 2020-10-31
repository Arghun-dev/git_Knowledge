# git_Knowledge

### git global setup


`git config --global user.name "Arghun Mousanezhad"`
`git config --global user.email "arghun.developer@gmail.com"`


### create a new repository


`git clone https://gitlab.com/Arghun/newdaya.git`
`cd newdaya`
`touch README.md`
`git add README.md`
`git commit -m "add README"`
`git push -u origin master`


### push an existing folder


`cd existing_folder`
`git init`
`git remote add origin https://gitlab.com/Arghun/newdaya.git`
`git add .`
`git commit -m "Initial commit"`
`git push -u origin master`


### push an existing git repository


`cd existing_repo`
`git remote rename origin old-origin`
`git remote add origin https://gitlab.com/Arghun/newdaya.git`
`git push -u origin --all`
`git push -u origin --tags`

