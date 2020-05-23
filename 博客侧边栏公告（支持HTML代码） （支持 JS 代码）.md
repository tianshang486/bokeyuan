# 博客侧边栏公告（支持HTML代码） （支持 JS 代码）

<img src="https://pic.cnblogs.com/face/2044915/20200523111218.png" alt="天殇486的头像" class="img_avatar">

<p class="para">关于我：<strong>天殇486</strong></p>
<p class="para">联系我：<a href="mailto:1426094384@qq.com" title="email">1426094384@qq.com</a></p> 



<hr>
<embed allowscriptaccess="never" allownetworking="internal" invokeurls="false" src="https://files.cnblogs.com/files/mmzs/flashDate.swf"
pluginspage="https://files.cnblogs.com/files/mmzs/flashDate.swf" type="application/x-shockwave-flash" quality="high" autostart="0" wmode="transparent" width="220"
height="65" align="middle">
</div>





<!-- 为博客底部添加音乐组件 -->
<div id="player"  class="aplayer"></div>
<link href="https://files.cnblogs.com/files/shwee/APlayer.min_v1.10.1.css" rel="stylesheet">
<script src="https://files.cnblogs.com/files/shwee/APlayer.min_v1.10.1.js"></script> 

<script type="text/javascript">
var ap = new APlayer({
    element: document.getElementById('player'),
    narrow: false,
    autoplay: true,          <!-- 是否自动播放 -->
    showlrc: false,
    theme: '#F5F5F5',      <!-- 插件背景颜色，建议和你的公告栏背景色一样，这样融为一体的感觉 -->
    music: [{
            title: '音乐1',
            author: 'Faded',
            url: 'https://link.hhtjim.com/163/36990266.mp3',
            pic: 'https://images.cnblogs.com/cnblogs_com/tianshang486/1771584/o_200523061713faded.jpg'
        },
        {
            title: '音乐2',
            author: '青鸟',
            url: 'https://link.hhtjim.com/163/718765.mp3',
            pic: 'https://images.cnblogs.com/cnblogs_com/tianshang486/1771584/o_200523061653%E9%9D%92%E9%B8%9F.jpg'
        },
        {
            title: '音乐3',
            author: '浮夸',
            url: 'https://link.hhtjim.com/163/66282.mp3',
            pic: 'https://images.cnblogs.com/cnblogs_com/tianshang486/1771584/o_200523061637%E9%99%88%E5%A5%95%E8%BF%85.jpg'
        }
    ]
});
ap.init();
</script>