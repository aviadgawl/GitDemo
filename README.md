delete the latest:  git reset --hard HEAD{1}
                    git push -f
                    git reset --hard HEAD{1}

set username: git config user.name "aviadgawl"
get username: git config user.name

set email: git config user.email "aviadgawl@gmail.com"
get email: git config user.email

clone reposetory: git clone https://github.com/aviadgawl/gitdemo

add gitingnore file: touch .gitignore

add remote origin: git remote add origin https://github.com/aviadgawl/gitdemo

upload files:   git add *
                git commit -m "first commit"
                git push origin master