<どうやってインストールするの？>

    ホームディレクトリにクローンする。
    （シンボリックリンクを貼るので実はどこでもいい)
    # cd ~
    # git clone https://github.com/kapuusagi/dotfiles dotfiles

    各ドットファイルをシンボリックリンクにする。
    # ln -s ~/dotfiles/my_vimrc ~/.vimrc
    # ln -s ~/dotfiles/my_gvimrc ~/.gvimrc

<その他>
    参考にしたURL
    そろしっかりvimを使う。dotfileのgithub管理とvundleの導入
	http://holypp.hatenablog.com/entry/20110515/1305443997
    Vundle/NeoBundleでプラグインを自動管理
	https://qiita.com/jnchito/items/5141b3b01bced9f7f48f
