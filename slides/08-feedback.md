# 0 点達成！！！

<img src="../assets/banzai_business.png" width="360"/>

---

# 振り返り

---

# ファイルサイズ

---

#### 圧縮なし（0 点）

<br/>
<img src="../assets/bundle-big.png" />
<br/>

#### 圧縮 + Code Splitting

<br/>
<img src="../assets/bundle-small.png" />
<br/>

#### Service Worker

<br/>
<img src="../assets/bundle-sw.png" />
<br/>

---

## 142KB → 7782KB（54 倍） へ

---

# スピード

---

#### 圧縮なし（0 点）

<img src="../assets/speed-low.png" />
<br/>

#### 圧縮 + Code Splitting

<img src="../assets/speed-high.png" />
<br/>

#### Service Worker

<img src="../assets/speed-sw.png" />
<br/>

---

## First Contentful Paint が 0.3 → 41.5s （138 倍）へ

---

# まとめ： Performance 0 を目指すために

---

### ファイルサイズを増やす = **読み込むデータ量を増やす**と効果に直結

<br/>

- gzip、コード分割、minify をやめるとファイルサイズ増大
- 高画質画像を元画像のまま活用することも効果が期待できる
- 大は小を兼ねる！

---

### 100 点のときと 0 点の時とでは**表示までに体感できるほどの差**がある

<br/>

- 会社設備の高速な回線だと見過ごしがち
- ユーザーはスマホが大半だったりキャリア回線も多い
  - モバイルユーザーはページ表示に 3 秒待てないと言われている
  - 現代人には余裕が必要
  - 3G ならゆっくりお茶を飲むことも可能！

---

# END
