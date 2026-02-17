# Welcome to My Homepage
<!-- 
<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=250&section=header&text=HI%20THERE!&fontSize=80&fontAlign=50&fontAlignY=30&animation=twinkling" />
</p> -->

<!-- <p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=1E6788&repeat=false&width=435&lines=console.log(%22Hello%2C+World%22)" alt="Typing SVG" /></a>
</p> -->


<p align="center">
<img src="./assets/logo_1.png" width="300">
</p>

<div>
  <p align="center">
    <!-- Twitter -->
    <a href="https://x.com/r1bjtythrbigbi9" target="_blank">
      <img src="https://img.shields.io/badge/Twitter-推特-blue" />
    </a>&emsp;
    <!-- YouTube -->
    <a href="https://www.youtube.com/@SheeranXue" target="_blank">
      <img src="https://img.shields.io/badge/YouTube-油管-c32136" />
    </a>&emsp;
    <!-- WeChat（点击复制微信号） -->
    <a href="javascript:void(0);"
       onclick="copyWechatId()">
      <img src="https://img.shields.io/badge/WeChat-微信-07c160" />
    </a>&emsp;
    <!-- Bilibili -->
    <a href="https://space.bilibili.com/11490425/" target="_blank">
      <img src="https://img.shields.io/badge/Bilibili-B站-ff69b4" />
    </a>
  </p>
  

  <!-- 提示文字 -->
  <p id="wechat-tip" class="wechat-tip">
    微信号已复制 ✔
  </p>
</div>



<!-- 只针对这个提示的动画样式 -->
<style>
.wechat-tip {
  text-align: center;
  font-size: 14px;
  color: rgba(0,0,0,.6);

  opacity: 0;                 /* 初始透明 */
  transform: translateY(6px); /* 初始轻微下移 */
  transition: all 0.35s ease; /* 渐变动画 */

  margin-top: 6px;
  pointer-events: none;       /* 不影响鼠标事件 */
}

/* 显示状态 */
.wechat-tip.show {
  opacity: 1;                 /* 渐入 */
  transform: translateY(0);   /* 回到正常位置 */
}
</style>


<script>
function copyWechatId() {

  const wechatId = "your_wechat_id";  // ← 改成你的微信号
  const tip = document.getElementById("wechat-tip");

  // 复制到剪贴板
  navigator.clipboard.writeText(wechatId).then(() => {

    // 1️⃣ 添加 show 类 → 触发渐入动画
    tip.classList.add("show");

    // 2️⃣ 2 秒后移除 → 渐出
    setTimeout(() => {
      tip.classList.remove("show");
    }, 2000);

  });

}
</script>
<!-- <script>
function copyWechatId() {
  const wechatId = "great_xuesiyuan";  // my wechat id

  navigator.clipboard.writeText(wechatId).then(() => {
    const tip = document.getElementById("wechat-tip");
    tip.style.display = "block";

    setTimeout(() => {
      tip.style.display = "none";
    }, 2000);
  });
}
</script> -->

<p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Lora&size=17&pause=1000&color=14465D&repeat=false&width=435&lines=%E8%BF%99%E6%98%AF+Sheeran+X+%E7%9A%84%E4%B8%BB%E9%A1%B5%EF%BC%8C%E8%AE%A1%E5%88%92%E7%94%A8%E4%BA%8E%E8%AE%B0%E5%BD%95%E4%B8%80%E4%BA%9B%E5%B9%B3%E6%97%B6%E7%9A%84%E6%80%9D%E8%80%83%E3%80%82" alt="Typing SVG" /></a>
</p>

<!-- 这是我现在的主页毛胚，计划是用于记录一些平时的思考。 -->

### 快速开始

<div class="grid grid-2">
  <div class="card">
    <div class="card-title">推荐入口</div>
    <div class="card-desc">从随笔切入，快速看到我在关注什么。</div>
    <ul class="list">
      <li>
        <a href="./投资随笔/佰维存储/"><b>📌 佰维存储</b></a>
        ：存储周期、预期与交易结构
      </li>
      <li>
        <a href="./投资随笔/江顺科技/"><b>🚀 江顺科技</b></a>
        ：商业航天产业链、制造端弹性
      </li>
      <li>
        <a href="./投资随笔/英特尔与CPU产能/"><b>🧩 英特尔与 CPU 产能</b></a>
        ：供给修复、节奏与外溢影响
      </li>
    </ul>
    <div class="tip">
      本站保持克制表达、高信息密度、持续更新迭代。
    </div>

  </div>

  <div class="card">
    <div class="card-title">栏目导航</div>
    <div class="card-desc">按 mkdocs.yml 导航进入对应板块。</div>
    <div class="grid">
      <a class="card card-link" href="./投资随笔/佰维存储/">
        <div class="card-title">投资随笔</div>
        <div class="card-desc">围绕个股、产业链与预期差的记录与复盘。</div>
      </a>
      <a class="card card-link" href="./金融理论知识/价值与价格/">
        <div class="card-title">金融理论知识</div>
        <div class="card-desc">金融理论：概念、框架与经济学常识。</div>
      </a>
      <a class="card card-link" href="./投资学理论知识/货币的时间价值/">
        <div class="card-title">投资学理论知识</div>
        <div class="card-desc">投资理论：风险、预期管理与直觉。</div>
      </a>
    </div>
  </div>
</div>

---

<div align="center">
  <a href="https://www.buymeacoffee.com/sheeranxue" target="_blank">
    <img
      src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png"
      alt="Buy Me A Coffee"
      height="60"
      width="217"
    />
  </a>
</div>

<div class="footer">
  <div class="footer-left">
    <div class="footer-title">Keep it simple.</div>
    <div class="footer-desc">共同进步。</div>
  </div>

  <div class="footer-right">
    <a class="link" href="./about/"><b>About</b></a>
  </div>
</div>

<!-- <p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=250&&section=footer&text=BYE!&fontSize=80&fontAlign=50&fontAlignY=70&animation=twinkling" />
</p> -->
