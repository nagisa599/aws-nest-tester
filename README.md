手順
```bash
# g++コンパイラのインストール
sudo yum -y install gcc-c++
# gitのインストール
sudo yum -y install git
# nvmのインストール
git clone https://github.com/creationix/nvm.git ~/.nvm
# vimでファイル作成
vi .bash_profile
# 以下の内容を記述
# nvm
if [[ -s ~/.nvm/nvm.sh ]] ; then
        source ~/.nvm/nvm.sh ;
fi
# 更新
source .bash_profile
# v16をinstall (Amazon Linux 2 はv20対応していなかったため)
nvm install v16.20.0
```
