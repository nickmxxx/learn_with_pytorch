# 这是一个学习pytorch的小程序，通过该项目进行pytorch的学习，开发的环境
## 开发环境：python3.7.3 + cuda10.2 + vscode
首先进行pytorch的安装
>pip install torch===1.6.0 torchvision===0.7.0 -f https://download.pytorch.org/whl/torch_stable.html -i https://pypi.tuna.tsinghua.edu.cn/simple some-package

采用国内的清华镜像源进行实践，实现提速
## 为git设置代理 使用v2ray socks5端口为10808 http端口为10809
git config --global http.proxy socks5://127.0.0.1:10808
git config --global https.proxy socks5://127.0.0.1:10808
## 查看代理
git config --global --get http.proxy
git config --global --get https.proxy