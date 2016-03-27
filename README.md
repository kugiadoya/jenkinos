# jenkinsos

こちらのサイトを非常に参考にさせていただく

[こちら](http://qiita.com/amasok23/items/2483f5f3e9fe371d1d92)

* jdk 1.7
* Jenkins ver. 1.654

## Usage

以下のものはインストール済想定(バージョンは動作確認したもの)

* Vagrant 1.7.4
* VirtualBox 5.0.2
* git 1.9.5

### Step

以下windows環境想定(コマンドプロンプト) MacOSでもほぼ一緒

1. Vagrantにプラグイン導入 `vagrant plugin install vagrant-omnibus`
1. 任意フォルダ作成 c:\vagrant とします
1. cd c\vagrant
1. git clone https://github.com/kugiadoya/jenkinos.git
1. cd jenkinsos
1. vagrant up

### Specifications

* http://192.168.33.55:8080 でアクセス
