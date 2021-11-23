# FrontDuan

作者：Jaskey Lam
链接：https://www.zhihu.com/question/20543196/answer/57757836
来源：知乎
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。

1.不知道自己高度和父容器高度的情况下, 利用绝对定位只需要以下三行：parentElement{
        position:relative;
    }

 childElement{
        position: absolute;
        top: 50%;
        transform: translateY(-50%);

 }2.若父容器下只有一个元素，且父元素设置了高度，则只需要使用相对定位即可    parentElement{
        height:xxx;
    }

    .childElement {
      position: relative;
      top: 50%;
      transform: translateY(-50%);
    }demo: Edit fiddle - JSFiddleFlex 布局：不考虑兼容老式浏览器的话，用Flex布局简单直观一劳永逸：parentElement{
    display:flex;/*Flex布局*/
    display: -webkit-flex; /* Safari */
    align-items:center;/*指定垂直居中*/
}demo: http://codepen.io/anon/pen/PZK
## https://www.cnblogs.com/wuqilang/p/12792544.html
https://www.jiangruitao.com/webpack/webpack-environment/
python3 -m http.server 4009
https://segmentfault.com/a/1190000012646221
前记
https://www.cnblogs.com/xiaohuochai/p/7522344.html
https://segmentfault.com/a/1190000012996217

https://segmentfault.com/a/1190000039872016https://www.jiangruitao.com/babel/preset-plugin/

https://www.ixiqin.com/2019/02/use-alias-to-simplify-the-reference-path-in-the-vue/
https://juejin.cn/post/6844904126699044872
https://juejin.cn/user/3315782798806430


This dependency was not found:

* core-js/modules/es.array.fill.js in ./node_modules/cache-loader/dist/cjs.js??ref--12-0!./node_modules/babel-loader/lib!./node_modules/cache-loader/dist/cjs.js??ref--0-0!./node_modules/vue-loader/lib??vue-loader-options!./src/view/Upload.vue?vue&type=script&lang=js&

To install it, you can run: npm install --save core-js/modules/es.array.fill.js
babel：
presets: [
    // '@vue/cli-plugin-babel/preset'
    [ "@vue/app", { useBuiltIns: "entry" } ]
  ]
https://segmentfault.com/a/1190000021377600
https://www.virapi.com/
https://juejin.cn/post/6844904082306498573
https://cloud.tencent.com/developer/article/1770288
https://gitee.com/Spinnin/spinnin-jay-music

https://zhuanlan.zhihu.com/p/261695780
https://www.kancloud.cn/wangjiachong/vue_notes/1896011
