## zeisha_updata

sudo systemctl stop ziesha

cd $HOME/bazuka

git pull origin master

cargo update

cargo install --path .

#rm -rf /root/.bazuka #удаляйте базу данных только если нужно!

sudo systemctl restart ziesha

sudo journalctl -f -u ziesha
