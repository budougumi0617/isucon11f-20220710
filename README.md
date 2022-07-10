# isucon11f-20220710

合同練習

- AMI: `ami-0d5fa5dc3ea5b2b66`
- ベンチマーカー
    - インスタンスタイプ: c5.xlarge
    - EBS: gp3 30GB
- 競技用サーバー 3台
    - インスタンスタイプ: c5.large
    - EBS: gp3 30GB

# ベンチマークの回し方

ベンチサーバーにubuntuユーザーでSSH接続する

/etc/hosts に以下を記載

```jsx
# もしかしたらhotsを書かなくてもいいかも（試してない）
# 1つのサーバーだけ入れてね
<ベンチを向けたいserverのIP> sub.mishima.tokyo
```


# 参考
https://github.com/budougumi0617/isucon-cheatsheet/