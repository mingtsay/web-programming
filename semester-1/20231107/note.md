CSS Positions:
- static: 靜態定位，為預設 document flow 所在位置
- absolute: 絕對定位，離開原本 document flow，並以 page 為基準定位，隨頁面捲動而移動
- fixed: 固定定位，離開原本 document flow，並以 viewport 為基準定位，不隨頁面捲動而移動
- relative: 相對定位，以原本 document flow 位置為基準做位移
- sticky: 黏著定位，在預設 DOM 位置，不過會找最接近可捲動的父層為基準下去定位，捲動時超出 viewport 後效果跟 fixed 類似