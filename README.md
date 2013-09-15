dotfiles.git
============
Configuration files for emacs, bash and screen.

Running this independently is not necessary if using the [setup](https://github.com/akshayrao/setup)


The setup basically performs the following:

```sh
cd $HOME
git clone https://github.com/akshayrao/dotfiles.git
ln -sb dotfiles/.screenrc .
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.bashrc_custom .
mv .emacs.d .emacs.d~
ln -s dotfiles/.emacs.d .
```

This repo is based off of the [startup class](http://github.com/startup-class) 

Specific link to the lecture:
[Startup Engineering Video Lectures 4a/4b](https://class.coursera.org/startup-001/lecture/index)