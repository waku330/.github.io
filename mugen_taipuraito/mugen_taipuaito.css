body {
    font-family: 'Courier New', Courier, monospace, Arial, Helvetica, sans-serif;
    font-weight: Regular;
    margin: 0;
    padding: 0;
    overflow: hidden;
}

#container {
    position: relative;
    width: 100%;
    height: 100vh;
    background-color: #f3f3f3; /* 初期背景色 */
    overflow: hidden;
}

.text {
    position: absolute;
    white-space: nowrap;
    top: 50%;
    transform: translateY(-50%);
    font-family: 'Courier New', Courier, monospace, Arial, Helvetica, sans-serif;
    font-weight: bold;
}

/* ツールボックスのラッパー */
#toolboxWrapper {
    position: fixed;
    top: 0;
    left: 50%;
    transform: translateX(-50%); /* 横中央に配置 */
    display: flex;
    gap: 0; /* ツールボックス間の隙間をなくす */
    z-index: 100;
    max-width: 800px; /* ツールボックスを並べた幅 */
}

/* 元のツールボックス */
#toolbox {
    background-color: rgb(251, 251, 251); /* 半透明な背景 */
    border: 1px solid #000000;
    padding: 10px 40px 20px 40px;
    box-shadow: 5px 5px 5px 1px rgba(0, 0, 0, 0);
    border-radius: 0 0 30px 30px;
    width: 50%; /* それぞれのボックスが横に並ぶように調整 */
    transition: top 0.3s ease;
    position: relative; /* 位置指定を変更せずにアニメーションを実行 */
}

#toolbox h3 {
    margin: 12px 0 18px 0;
    font-size: 12px;
}

#toolbox label {
    margin-right: 10px;
    font-size: 16px;
}

#toolbox input {
    margin-bottom: 10px;
}

/* ランダムツールボックス */
#randomToolbox {
    background-color: rgba(0, 0, 0, 1);
    border: 0.5px solid #ffffff;
    padding: 10px 40px 20px 40px;
    box-shadow: 5px 5px 5px 1px rgba(0, 0, 0, 0);
    border-radius: 0 0 30px 30px;
    width: 50%; /* それぞれのボックスが横に並ぶように調整 */
    transition: top 0.3s ease;
    position: relative; /* 位置指定を変更せずにアニメーションを実行 */
}

#randomToolbox h3 {
    margin: 12px 0 9px 0;
    font-size: 12px;
}

#randomToolbox label {
    margin-right: 10px;
    font-size: 16px;
}

#randomToolbox input {
    margin-bottom: 10px;
}

/* スライダーのスタイル */
#toolbox input[type="range"], #randomToolbox input[type="range"] {
    margin: 10px 0 12px 0;
    width: 100%;
    height: 10px;
    background-color: rgba(255, 255, 255, 0.0);
    border: 1px solid #000000;
    border-radius: 10px;
    -webkit-appearance: none;
    appearance: none;
    outline: none;
}

/* スライダーのつまみ */
#toolbox input[type="range"]::-webkit-slider-thumb, #randomToolbox input[type="range"]::-webkit-slider-thumb {
    -webkit-appearance: none;
    appearance: none;
    width: 1px;
    height: 10px;
    background-color: rgb(0, 0, 0);
    border: none;
}

#toolbox input[type="range"]::-moz-range-thumb, #randomToolbox input[type="range"]::-moz-range-thumb {
    width: 30px;
    height: 10px;
    background-color: white;
    border: none;
}

#toolbox input[type="range"]::-ms-thumb, #randomToolbox input[type="range"]::-ms-thumb {
    width: 30px;
    height: 10px;
    background-color: white;
    border: none;
}

/* カラーピッカーの見た目 */
#toolbox input[type="color"], #randomToolbox input[type="color"] {
    -webkit-appearance: none; /* デフォルトのUIを無効にする */
    appearance: none;
    width: 101%; /* サイズを調整 */
    height: 13px;
    margin: 10px 0 12px 0;
    border-radius: 10px; /* 丸くする */
    border: 0px solid rgba(255, 255, 255, 0.0); /* 外枠のボーダー */
    padding: 0;
    cursor: pointer;
    position: relative;
    overflow: hidden;
}

/* 選択された色をボーダーいっぱいに表示する */
#toolbox input[type="color"]::-webkit-color-swatch-wrapper, 
#randomToolbox input[type="color"]::-webkit-color-swatch-wrapper {
    padding: 0; /* 色選択部分の余白をなくす */
    border-radius: 10px; /* 丸角に合わせる */
}

#toolbox input[type="color"]::-webkit-color-swatch, 
#randomToolbox input[type="color"]::-webkit-color-swatch {
    border-radius: 10px; /* 丸角に合わせる */
    border: none; /* 色選択部分のボーダーを削除 */
}

/* カラーピッカーをクリックしたときの中身の変化を維持 */
#toolbox input[type="color"]:focus, #randomToolbox input[type="color"]:focus {
    border-color: #000; /* フォーカス時にボーダーを強調 */
}


/* ツールボックスを表示するためのホバーアクション */
#toolboxWrapper:hover #toolbox,
#toolboxWrapper:hover #randomToolbox {
    top: 0;  /* マウスが上部に近づいたときにツールボックスを表示 */
}

/*チェックボックスの見た目*/
.checkbox-group {
    display: flex; /* 子要素を横並びに配置 */
    align-items: center; /* 垂直方向に中央揃え */
    /*gap: 10px; /* ラベルとチェックボックスの間にスペースを追加 */
    margin-bottom: 8px; /* グループ間のスペースを追加 */
}

.checkbox-group label {
    margin: 0; /* デフォルトの余白をリセット */
    font-size: 14px; /* フォントサイズを適宜調整 */
}

#randomToolbox input[type="checkbox"] {
    -webkit-appearance: none;
    appearance: none;
    margin-left: auto; /*右揃え*/
    margin-top: 8px;
    width: 20px;
    height: 20px;
    border: 1px solid #fff;
    border-radius: 4px; /*丸カド*/
    background-color: transparent;
    cursor: pointer;
    position: relative;
    flex-shrink: 0; /*形をつぶれなくする*/
}

#randomToolbox input[type="checkbox"]:checked {
    background-color: #fff;
    border-color: #fff;
}

#randomToolbox input[type="checkbox"]:checked::before {
    content: '●';
    color: #000;
    font-size: 14px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

/* チェックボックスがフォーカスされた時の枠線を非表示にしない */
#randomToolbox input[type="checkbox"]:focus {
    outline: none; /* フォーカス時の枠線を削除 */
    border-color: #fff; /* 枠線を透明にしない */
}

/* チェックボックスがクリックされたときの変化を無くす */
#randomToolbox input[type="checkbox"]:checked {
    background-color: #fff;
    border-color: #fff; /* 枠線が変わらないように設定 */
}

#toolbox, #randomToolbox {
    top: -400px;  /* 初期状態では非表示 */
    transition: top 0.3s ease-in-out;  /* アニメーション効果を追加 */
}
