# Futurealize with Tech！
コードにおける共通ルール定めときます。

## 🪛 importの順番

1. ReactHooks
2. styles
3. motion (framer-motion)
4. next (Image, Link etc...)
5. context
6. ライブラリ
7. lib
8. react-icons
9. 画像系

## 👔 CSS styleの順番

1. box-sizing
2. width, height, max, min
3. position (relative以外)
4. display
5. margin
6. padding
7. font系
8. border系 (radiusなど)
9. outline
10. color (font → border → background)
11. 画像系
12. position: relative;
13. cursor

## 🌈 CSSの変数を使おう
`global.scss`の`:root`内で、色などを指定する。(できればRGB値で)
<br/>
<br/>
下記のように、指定する。

    :root {
        --primary-pink: 249, 193, 207;
    }

そうすると下記のように色を指定することができる。

    color: rgb(var(--primary-pink));

RGB値で変数にしたいのは、下記のようにopacityを自由に調整できるから。

    color: rgb(var(--primary-pink), 0.5);

メインの色には`--primary-色`のように命名する。
