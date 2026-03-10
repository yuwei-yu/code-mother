<template>
  <a-layout-footer class="footer">
    <div class="footer-content">
      <p class="slogan">fishV-nocode · AI 无代码网站生成平台</p>
      <p class="meta">
        灵感到上线，一站式完成。部分能力由
        <a
          href="https://www.codefather.cn"
          target="_blank"
          rel="noopener noreferrer"
          class="author-link"
        >
          编程导航
        </a>
        提供支持。
      </p>
    </div>
  </a-layout-footer>
</template>

<script setup lang="ts">
// 无需额外的响应式数据
</script>

<style scoped>
.footer {
  background: rgba(255, 255, 255, 0.8);
  backdrop-filter: blur(10px);
  text-align: center;
  padding: 16px 24px 24px;
  margin-top: 24px;
  border-top: 1px solid rgba(226, 232, 240, 0.9);
}

.slogan {
  margin: 0;
  color: #4b5563;
  font-size: 14px;
  font-weight: 500;
}

.meta {
  margin: 4px 0 0;
  color: #9ca3af;
  font-size: 14px;
}

.author-link {
  color: #0ea5e9;
}

.author-link:hover {
  color: #0369a1;
}
</style>
