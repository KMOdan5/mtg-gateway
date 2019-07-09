# サイト解析
### URL

```
https://mtg-jp.com/products/card-gallery/
```

### タグ構成
- div class="box-year"
  - ul
    - li
      - a href= カード一覧URL
        - div class="img"
        - div class="name" セット名


## カード一覧
### URL

```
https://mtg-jp.com/products/card-gallery/0000182/
```

### タグ構成
- main article
  - div id="contents"
    - div id="pankuzu"
    - section
      - div class="inner"
        - div class="box-type" 分類毎
          - header class="type-header"
            - h2
              - span class="jp" 日本語-分類名
              - span class="en" 英語-分類名
          - ul class="card-list"
            - li すべてのカードリスト
              - a href= 詳細ページURL
                - figure
                  - img src= カードイメージ
              - figcaption カード名

### 属性
- 分類名
  - 白,青,黒,赤,緑,多色,アーティファクト,土地


## 詳細ページ
### URL

```
https://mtg-jp.com/products/card-gallery/0000182/466756/
```

### タグ構成
- main article
  - div id="contents"
    - div id="pankuzu"
    - section
      - div class="inner"
        - div class="card-detail"
          - figure class="card-img"
          - div class="card-info"
            - h2 カード名
            - ul class="icon-list" コスト
            - p class="type" カード・タイプ
            - p class="power-toughness" パワー/タフネス
            - p class="text" 日本語-テキスト
            - p class="text" 英語-テキスト

### 属性
