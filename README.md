# README
## Setup

Wolfram言語の実行環境は主にMathematicaとJupyterの2つがありますが, 
無料で実行環境構築ができるJupyterベースでSteupを行うことをここでは想定しています.

詳しくは, see this [docs](https://ryonakagami.github.io/2023/03/09/wolfram-engine-setup/)


## How to Use it

基本的には`.ipynb`形式ファイル & VS Code経由でWoflfram Kernelを呼び, そこで演算を行うことを想定しています.

### Jupyter Kernelの設定

1. `.ipynb`ファイルをVS Codeで開く
2. `select Jupyter Kernel`をクリック
3. Woflfram Kernelを選択

## Troubleshooting
### kernel errorが出る

```zsh
% ps aux | grep "Wolfram" | awk {'print $2'} |xargs kill -9 
```



## References

> Ryo's Tech Blog

- [Wolfram Engineをローカルで使用できるようにするまで](https://ryonakagami.github.io/2023/03/09/wolfram-engine-setup/)