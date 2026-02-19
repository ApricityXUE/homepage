这是我的主页的简陋草稿。

以下是一些未套 card 的数据备份：

<iframe src="https://www.newyorkfed.org/markets/desk-operations/repo" style="width:100%;height:600px;border:0"></iframe>

<iframe src="https://fred.stlouisfed.org/graph/graph-landing.php?g=1S3Wd&width=670&height=475" scrolling="no" frameborder="0" style="overflow:hidden; width:670px; height:525px;" allowTransparency="true" loading="lazy"></iframe>

以下是自适应尺寸图片的模版：

<div class="fred-wrapper" id="fredWrap">
  <div class="fred-stage" id="fredStage">
    <iframe
      src="https://fred.stlouisfed.org/graph/graph-landing.php?g=1S3Wd&width=670&height=475"
      scrolling="no"
      frameborder="0"
      loading="lazy"></iframe>
  </div>
  <script>
    (() => {
      const BASE_W = 670;
      const BASE_H = 525;

      const wrap  = document.getElementById('fredWrap');
      const stage = document.getElementById('fredStage');

      function apply() {
        const w = wrap.getBoundingClientRect().width; // 容器真实宽度（比 clientWidth 稳）
        const s = Math.min(1, w / BASE_W);            // 不放大，只缩小

        stage.style.transform = `scale(${s})`;
        wrap.style.height = `${BASE_H * s}px`;
      }

      apply();
      requestAnimationFrame(apply);                   // 移动端经常需要下一帧再算一次
      new ResizeObserver(apply).observe(wrap);        // 容器宽度变化就重算
      window.addEventListener('orientationchange', () => setTimeout(apply, 50), { passive: true });
    })();
  </script>
</div>
