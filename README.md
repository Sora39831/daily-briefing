# Daily Briefing

多品类日报汇总仓库。每个子目录对应一种日报品类。

## 日报列表

| 品类 | 目录 | 最新 | 链接 |
|------|------|------|------|
| AI 大模型信号评估 | `ai-daily-briefing/` | 2026-05-13 | [查看](https://daily-briefing-5d4.pages.dev) |
| ... | 更多即将上线 | | |

---

### 添加新品类

```
mkdir my-report-category
cp /path/to/report.html my-report-category/index.html
git add -A && git commit -m "add: my-report-category" && git push
```

Cloudflare Pages 自动部署，根目录为仓库根目录（可通过 `root_dir` 配置调整）。
