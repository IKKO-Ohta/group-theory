# ド・モルガンの法則

## 主張と証明

### ド・モルガンの法則の証明

1. `X - (A ∨ B) = (X - A) ^ (X - B)`

![image](https://user-images.githubusercontent.com/27924055/107107921-94b1a880-6877-11eb-80df-fc335b6d20ab.jpeg)

![image](https://user-images.githubusercontent.com/27924055/107107927-a2672e00-6877-11eb-8dfa-ee540940080b.jpeg)

2. `X - (A ^ B) = (X - A) ∨ (X - B)`

![image](https://user-images.githubusercontent.com/27924055/107107928-a85d0f00-6877-11eb-812c-3993bd62c96f.jpeg)

![image](https://user-images.githubusercontent.com/27924055/107107934-b27f0d80-6877-11eb-9fa6-1efe0f98d0cb.jpeg)

### ド・モルガンの法則（補集合について）

-  `!(A or B) = !A and!B`
- `!(A and B) = !A or !B`

![image](https://user-images.githubusercontent.com/27924055/107107942-b7dc5800-6877-11eb-8b31-52fe3b2bd72e.jpeg)

![image](https://user-images.githubusercontent.com/27924055/107107916-8bc0d700-6877-11eb-99c1-4a93eeec9106.jpeg)

- 式変形の二行目、否定をつけ忘れていますね。下のようになり、これは定義からBの補集合です
```python
not(x in B) and (x in X)
```

## わからなかったこと

問3.3 対象差の証明、結合法則の証明について
式展開を一緒に追ってくれると助かります！