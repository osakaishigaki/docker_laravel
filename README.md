# docker_laravel

# 最初にgitの設定して繋げておく

git config --global user.name "mbp2019"
git config --global user.email osakaihsigaki@gmail.com

echo "# docker_laravel" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:osakaishigaki/docker_laravel.git
git push -u origin main
