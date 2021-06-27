# kj
Kubernetes公式ドキュメント内リンクを/ja/docs/に置き換える

## Install

```
git clone https://github.com/oke-py/kj.git
cd kj
make install
```

## Create an issue body

```
git clone https://github.com/kubernetes/website.git
cd website
git switch -c dev-1.19-ja.2
kji /docs/concepts/containers/container-environment/
```

## Replace links

```
git clone https://github.com/kubernetes/website.git
cd website
git switch -c dev
kjr /docs/concepts/containers/container-environment/
```

