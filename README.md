# open_project

a script to open projects in editor with one command.

## installation


- clone the repo
```
git clone git@github.com:michebble/open_project.git
```

- cd into repo, change the script permissions, and create symlink
```
cd open_project
chmod +x ./op
sudo ln -s ./op ~/../../usr/local/bin
```

- set envs for your editor (defaults to vim) and projects directory in your rc or profile
```
echo -e "export OP_EDITOR=code \nexport OP_DIRNAME=Projects \n" >> ~/.zshrc
source ~/.zshrc
```

- open your project from anywhere
```
op my_cool_project
```



