---
abbrlink: 3165489602
author: Allen
categories: 工具
hidden: true
indexing: false
published: 2023-06-18 16:01:44
title: alist v3 样式
tags: ['服务器']
---
#自定义头部



```
<!--音乐播放器所用的文件-->
<!-- require APlayer -->
<link rel="stylesheet" href="https://npm.elemecdn.com/aplayer@1.10.1/dist/APlayer.min.css">
<script src="https://npm.elemecdn.com/aplayer@1.10.1/dist/APlayer.min.js"></script>
<!-- require MetingJS -->
<script src="https://cdn.jsdelivr.net/npm/@xizeyoupan/meting@latest/dist/Meting.min.js"></script>

<!-- Waline CSS -->
<link rel="stylesheet" href="https://unpkg.com/@waline/client@v2/dist/waline.css" />


<style>

/* 移除搜索框中的快捷键指引 */
.hope-stack.hope-c-dhzjXW.hope-c-PJLV.hope-c-PJLV-ihYBJPK-css {
    display: none !important;
}


/* 移除整个搜索框 */
.hope-stack.hope-c-dhzjXW.hope-c-PJLV.hope-c-PJLV-ikEIIxw-css {
    display: none !important;
}


/* 搜索框改透明 */
/* 毛玻璃效果 */
/* 白天模式 */
.hope-ui-light .hope-c-PJLV-ikEIIxw-css {
    background: rgba(255, 255, 255, 0.2) !important;
    backdrop-filter: blur(10px) !important;
}

/* 夜间模式 */
.hope-ui-dark .hope-c-PJLV-ikEIIxw-css {
    background: rgb(0 0 0 / 10%) !important;
    backdrop-filter: blur(10px) !important;
}

/* 非毛玻璃效果 */
/* 白天模式 */
.hope-ui-light .hope-c-PJLV-ikEIIxw-css {
    background: rgba(255, 255, 255, 0.2) !important;
}

/* 夜间模式 */
.hope-ui-dark .hope-c-PJLV-ikEIIxw-css {
    background: rgb(0 0 0 / 10%) !important;
}


/* 搜索结果改透明 */
/* 毛玻璃效果 */
/* 白天模式 */
.hope-ui-light .hope-c-PJLV-iiBaxsN-css {
    background: rgba(255, 255, 255, 0.2) !important;
    backdrop-filter: blur(10px) !important;
}

/* 夜间模式 */
.hope-ui-dark .hope-c-PJLV-iiBaxsN-css {
    background: rgb(0 0 0 / 10%) !important;
    backdrop-filter: blur(10px) !important;
}

/* 非毛玻璃效果 */
/* 白天模式 */
.hope-ui-light .hope-c-PJLV-iiBaxsN-css {
    background: rgba(255, 255, 255, 0.2) !important;
}

/* 夜间模式 */
.hope-ui-dark .hope-c-PJLV-iiBaxsN-css {
    background: rgb(0 0 0 / 10%) !important;
}


/* 搜索结果输入框改透明 */
/* 毛玻璃样式 */
/* 白天模式 */
.hope-ui-light .hope-c-kvTTWD-hYRNAb-variant-filled {
    background: rgba(255, 255, 255, 0.2) !important;
    backdrop-filter: blur(10px) !important;
}

/* 夜间模式 */
.hope-ui-dark .hope-c-kvTTWD-hYRNAb-variant-filled {
    background: rgb(0 0 0 / 10%) !important;
    backdrop-filter: blur(10px) !important;
}

/* 非毛玻璃样式 */
/* 白天模式 */
.hope-ui-light .hope-c-kvTTWD-hYRNAb-variant-filled {
    background: rgba(255, 255, 255, 0.2) !important;
}

/* 夜间模式 */
.hope-ui-dark .hope-c-kvTTWD-hYRNAb-variant-filled {
    background: rgb(0 0 0 / 10%) !important;
}


/* 切换视图按钮改透明 */
.hope-c-ivMHWx-hZistB-cv.hope-icon-button {
    background-color: rgba(255, 255, 255, 0.3) !important; /* 可将0.3改成0达到完全没有背景 */
}


/* 去除网站图标与搜索 */
.hope-stack.hope-c-dhzjXW.hope-c-PJLV.hope-c-PJLV-iiOacaA-css {
    display: none !important;
}


/* 顶部新增图片（可设置GIF） */
<img src="图片地址" style="display:block; margin:auto;" />


/* 使用背景图（可设置GIF） */
/*图片API
  樱花：https://www.dmoe.cc
  夏沫：https://cdn.seovx.com
  搏天：https://api.btstu.cn/doc/sjbz.php
  姬长信：https://github.com/insoxin/API
  小歪：https://api.ixiaowai.cn/
  保罗：https://api.paugram.com
  墨天逸：https://api.mtyqx.cn
  岁月小筑：https://img.xjh.me
  东方Project：https://img.paulzzh.com
  */
/* 白天模式 */
.hope-ui-light {
    background-image: url("图片地址") !important;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    background-position-x: center;
}

/* 夜间模式 */
.hope-ui-dark {
    background-image: url("图片地址") !important;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    background-position-x: center;
}


/* 列表改透明 */
/* 白天模式 */
.obj-box.hope-stack.hope-c-dhzjXW.hope-c-PJLV.hope-c-PJLV-igScBhH-css {
    background-color: rgba(255, 255, 255, 0.5) !important;
}

/* 夜间模式 */
.obj-box.hope-stack.hope-c-dhzjXW.hope-c-PJLV.hope-c-PJLV-iigjoxS-css {
    background-color: rgb(0 0 0 / 50%) !important;
}


/* 元信息改透明 */
/* 白天模式 */
.hope-c-PJLV.hope-c-PJLV-ikSuVsl-css {
    background-color: rgba(255, 255, 255, 0.5) !important;
}

/* 夜间模式 */
.hope-c-PJLV.hope-c-PJLV-iiuDLME-css {
    background-color: rgb(0 0 0 / 50%) !important;
}```


/* 文档预览改透明 */
/* 白天模式 */
.hope-ui-light pre {
    background-color: rgba(255, 255, 255, 0.1) !important;
}

/* 夜间模式 */
.hope-ui-dark pre {
    background-color: rgba(255, 255, 255, 0)!important;
}


/* 侧边栏改透明 */
.hope-c-PJLV-ijgzmFG-css {
    background-color: rgba(255, 255, 255, 0.5) !important;
}


/* 去除底部 */
.footer {
    display: none !important;
}


/* 移除本地设置中的 Aria2 */
.hope-stack.hope-c-dhzjXW.hope-c-PJLV.hope-c-PJLV-ikjnSaO-css {
    display: none !important;
}


/* 移除下载选项 */
.hope-select__trigger.hope-c-kvTTWD.hope-c-huZphZ.hope-c-kvTTWD-hYRNAb-variant-filled.hope-c-kvTTWD-gfwxhr-size-md.hope-c-huZphZ-cIGthf-cv.hope-c-PJLV.hope-c-PJLV-ijSQbqe-css {
    display: none !important;
}


/* 去除公告关闭按钮 */
.notify-render .hope-close-button {
    display: none;
}


/* 评论适配大小契合度 */
.newWaline {
    width: min(96%, 940px);
    flex-direction: column;
    row-gap: var(--hope-space-2);
    border-radius: var(--hope-radii-xl);
    padding: var(--hope-space-2);
    box-shadow: var(--hope-shadows-lg);
}
/* 评论区 白天模式透明度 */
.hope-ui-light .newWaline {
    background-color: rgba(255, 255, 255, 0.8)!important;
}
/* 评论区 夜间模式透明度 */
.hope-ui-dark .newWaline {
    background-color:rgb(0 0 0 / 80%)!important;
}


/* 音乐播放器进一步进行隐藏 */
.aplayer.aplayer-fixed.aplayer-narrow .aplayer-body {
    left: -66px!important;
}
.aplayer.aplayer-fixed.aplayer-narrow .aplayer-body:hover {
    left: 0!important;
}


/*渐变背景CSS*/
 #canvas-basic {
    position: fixed;
    display: block;
    width: 100%;
    height: 100%;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: -999;
}

</style>

```
#自定义内容
```
<!--延迟加载-->
<div id="customize" style="display: none;">
    <div>
        <!--音乐播放器-->
        <meting-js
            server="netease"
            id="7519316683"
            type="playlist"
            fixed="true"
            autoplay="true">
        </meting-js>

        <!--评论模块-->
        <center>
            <div class="newWaline" id="waline"></div>
        </center>
        <script type="module">
            import { init } from 'https://unpkg.com/@waline/client@v2/dist/waline.mjs';

            init({
                el: '#waline',
                serverURL: 'https://your-domain.vercel.app',
            });
        </script>

        <br />
        <center>
            <div>
                <span class="nav-item">
                    <a class="nav-link" href="xxxxxx" target="_blank">
                        博客 |
                    </a>
                </span>
                <!--后台入口-->
                <span class="nav-item">
                    <a class="nav-link" href="/@manage" target="_blank">
                        管理
                    </a>
                </span>
            </div>
        </center>
        <br />
        <br />
    </div>
    <!--延迟加载范围到这里结束-->
</div>
<!--延迟加载配套使用JS-->
<script>
    let interval = setInterval(() => {
        if (document.querySelector(".footer")) {
            document.querySelector("#customize").style.display = "";
            clearInterval(interval);
        }
    }, 200);
</script>

<!-- 渐变背景初始化,如果要使用渐变背景把下面一行注释去掉即可 -->
<!-- <canvas id="canvas-basic"></canvas> -->
<script src="https://npm.elemecdn.com/granim@2.0.0/dist/granim.min.js"></script>
<script>
    var granimInstance = new Granim({
        element: '#canvas-basic',
        direction: 'left-right',
        isPausedWhenNotInView: true,
        states: {
            "default-state": {
                gradients: [
                    ['#a18cd1', '#fbc2eb'],
                    ['#fff1eb', '#ace0f9'],
                    ['#d4fc79', '#96e6a1'],
                    ['#a1c4fd', '#c2e9fb'],
                    ['#a8edea', '#fed6e3'],
                    ['#9890e3', '#b1f4cf'],
                    ['#a1c4fd', '#c2e9fb'],
                    ['#fff1eb', '#ace0f9']

                ]
            }
        }
    });
</script>


```