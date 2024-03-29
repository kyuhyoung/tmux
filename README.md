# tmux
tmux related files

### install

```
$ apt-get install tmux -y
$ git clone https://github.com/kyuhyoung/tmux.git
$ cp -r tmux/.tmux* ~/
$ tmux source-file ~/.tmux.conf
```

### [.tmux/plugins]
The folders such as "tmux-better-mouse-mode" in this folder are still other git repos.  So you have to git-clone them manually.
```
$ sudo chown $(whoami):$(whoami) -R ~/.tmux
$ cd ~/.tmux/plugins
$ git clone https://github.com/tmux-plugins/tpm.git 
$ git clone https://github.com/NHDaly/tmux-better-mouse-mode.git
$ git clone https://github.com/tmux-plugins/tmux-continuum.git
$ git clone https://github.com/tmux-plugins/tmux-resurrect.git
$ git clone https://github.com/tmux-plugins/tmux-sensible.git
$ tmux source-file ~/.tmux.conf
```

### [.tmux.conf]
Tmux cofiguration file.  Edit the file by uncommenting some lines according to your tmux version. This file better be located as "~/.tmux.conf".
Don'forget to apply the configuration file.
```
$ tmux source-file ~/.tmux.conf
```
