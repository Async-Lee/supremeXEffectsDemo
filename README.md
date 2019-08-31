# supremeXEffectsDemo
##三角形蜘蛛网 X supreme联名特效

// script引入
<script src="supremeXEffects.js"></script>

// 适应于webpack项目的引用方式
import supremeXEffects from '@assets/js/supremeXEffects.js'

// 简单易用 明眼人一看就懂。总之秦牛正威🐂🍺
let supremeXEffects = new SupremeXEffects(),<br>
params = {<br>
    el: document.body,<br>
    // direction: 'left',<br>
    width: 500,<br>
    count: 40,<br>
    color: ['red', 'white', 'gray']<br>
}<br>
supremeXEffects.init(params)<br>