Este es mi curso de linux clonado

git config --global user.email "xyz@gmail.com"
git config --global user.name
git config --global user.email

# Set git to use the credential memory cache 
git config --global credential.helper cache

# Set the cache to timeout after 1 hour (setting is in seconds)
git config --global credential.helper 'cache --timeout=3600'

git fetch origin master
git pull origin master

git commit -a
git commit -m "mensaje"

