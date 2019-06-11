## 4. ComponentのLazy loadでのCode splittingをoffにする

<br/>

---

```ts
- const Hoge = React.lazy(() => import(/* webpackChunkName: "Hoge" */ './Hoge'))

+ import Hoge from './Hoge'
```

---

<img src="../assets/score-4.png" width="640" />

---

# ！