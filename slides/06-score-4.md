## 4. Component の Lazy load での Code splitting を off にする

<br/>

---

```ts
- const Hoge = React.lazy(() => import(/* webpackChunkName: "Hoge" */ './Hoge'))

+ import Hoge from './Hoge'
```

---

![](../assets/score-4.png)

---

### ！

<img src="../assets/pistol_pose_man.png" width="240"/>
