<div align="center">
  <picture>
    <source srcset="./assets/profile.svg?v=2" type="image/svg+xml">
    <img src="./assets/profile.svg?v=2" width="100%" alt="Anna — 21 · security research · full-stack">
  </picture>
</div>

<!--
  用 <picture> 包住图片，GitHub 就不会再自动套一层 <a href=".../blob/...">，
  点图片没有任何跳转。直接写 <img> 会被强制包链接（无 href 的 <a> 也会被剥掉后重包）。

  改内容：编辑 assets/gen_profile.py 里的常量，重跑 python3 gen_profile.py，
  上传后把上面的 ?v=2 递增（GitHub 图片代理按 URL 缓存）。
-->
