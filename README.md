# 基本設定

gitとansibleがインストールし、以下を叩いて終わり。

```
$ git clone git@github.com:wing-tail/basic_setting.git $HOME/basic_setting
$ cd $HOME/basic_setting
$ ansible-playbook -i inventory set_up.yml --ask-become-pass
`````
