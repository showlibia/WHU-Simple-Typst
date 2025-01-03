# WHU-Simple-Typst

本项目用于武汉大学国家网络安全学院的结课论文typst模板。

目前还很简陋，考虑下一步参考[中山大学typst模板](https://github.com/sysu/better-thesis)进行更改。

## Typst使用

- [官方网站](https://typst.app/)
- 本地下载
    - Windows平台可以使用`scoop install typst`
    - Linux/Mac
```
# 安装 Rust 环境并激活，之前安装过则不需要执行下面这两行
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y
source $HOME/.cargo/env

# 安装 Typst CLI
cargo install typst-cli

# 访问缓慢的话，执行以下命令设置清华镜像源，并从镜像站安装
cat << EOF > $HOME/.cargo/config
[source.crates-io]
replace-with = "tuna"

[source.tuna]
registry = "https://mirrors.tuna.tsinghua.edu.cn/git/crates.io-index.git"
EOF
cargo install typst-cli
```

下载完成后可以使用VSCode的`Tinymist Typst`进行编辑和编译

## 教程

- [官方教程](https://typst.app/docs/)
- [非官方中文版](https://typst-doc-cn.github.io/docs/tutorial/)
- [翻译](http://ai-assets.404.net.cn/pdf/typst/typst-zh_CN-20230409.pdf)