# yyl-ys.zsh-theme
yyl-ys为一个[oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)主题，在[主题ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme)基础上修改而成。

主要是做一些个性化的prompt显示。目前支持的功能如下：

- conda虚拟环境
- virtualenv虚拟环境

## 预览

#### conda

![image-20190214201245569](https://img.cayun.me/2019-02-14-121246.png)

#### virtualenv

![image-20190310121046816](https://img.cayun.me/2019-03-10-041047.png)

## 使用方式

#### conda

1. 将yyl-ys.zsh-theme文件拷贝到~/.oh-my-zsh/themes下
2. 修改~/.zshrc中的theme配置为yyl-ys
3. 在~/.condarc中添加`changeps1: False`

#### virtualenv

1. 将yyl-ys.zsh-theme文件拷贝到~/.oh-my-zsh/themes下
2. 修改~/.zshrc中的theme配置为yyl-ys
3. 在~/.zshrc中添加`export VIRTUAL_ENV_DISABLE_PROMPT=true`
