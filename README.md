# wxSVG-findDifference
 微信图文找不同交互

作品展示：[过年前，吉珠变得不一样了？]（https://mp.weixin.qq.com/s/9ogsqIZ_2WOtfQvUYp9G1A）

原理：透明度动画。点击区域与显示区域写在同一个组中，点击后在另一处出现“反馈”。

动画代码： 

    //点击后在0.5s时间内，透明度由0到1；
    <animate
        attributeName="opacity"
        begin="click"
        dur=".5s"
        values="0;1"
        fill="freeze"
        restart="never"
    ></animate>

仓库中存放了基本的demo，可以clone分析代码结构理解设计逻辑。