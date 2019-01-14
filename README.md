# Configuration file for building osx with ansible
brew, cask, mas, dotfile, awscli, xcode, vsc, golang...

## install

```shell
ansible-playbook -vv site.yml -i locahost --ask-pass --ask-sudo-pass
```


## reference
- [AnsibleでMacの開発環境を構築する](https://techte.co/2018/01/22/ansible-mac/)
- [Ansibleでパスワードをスマートに
](https://qiita.com/fukushi_yoshikazu/items/5e327103066ac80629f3)