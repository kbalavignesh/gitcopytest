# gitcopytest


#git clone https://github.com/user/source.git
#cd source

--Change to right branch

#git remote rm origin

.git/config
[remote "origin"]
        url = https://github.com/kbalavignesh/openweathermap_react.git
        fetch = +refs/heads/*:refs/remotes/origin/*

git mv -k * openweather/

git commit

#dont push this. you can delete this local repos
---------------------------------------------------------------------------------
cd dest
git remote add modified-source ../openweather
git pull modified-source master --allow-unrelated-histories

git log --follow App.js
