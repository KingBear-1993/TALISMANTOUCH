# Guardian Eye V1 Final Master

这是当前确认后的 V1 主版本封版说明。

## 主运行文件
- `guardian_eye_v1_final_master.html`

## 主内容文件
- `guardian_eye_v1_final_content.json`：64 张核心卡主内容库（当前主句精修版）
- `guardian_eye_v1_final_high_hit_pool.json`：高命中 16 张优先池
- `guardian_eye_v1_final_priority_copy_pool.json`：首页 / 过渡页 / 导出页优先调用池

## 当前封版结构
- 首页：4 个一级按钮
  - Money Pressure
  - Burnout
  - Feeling Alone
  - Need Clarity
- 结果页与导出页：主句一致
- 导出页：仅排版更适合分享，不再切换另一套主句
- 首页短句：走 priority copy pool
- 过渡页文案：走 priority copy pool
- 导出页：不额外塞随机长句，避免排版冲突
- 出卡逻辑：用户输入很短或为空时，优先使用 high-hit 16-card pool

## 后续改动规则
1. 后续不要再直接覆盖旧分叉文件。
2. 所有后续调整都从 `guardian_eye_v1_final_master.html` 复制新版本再改。
3. 若只改文案，优先改对应 JSON，不先动交互层。
4. 若只改视觉，尽量不动首页按钮、输入框、翻牌链路。

## 当前封版目标
- 可运行
- 手机端整屏基本稳定
- 首页按钮可用
- 结果页 / 导出页视觉已统一
- 文案层已完成多轮人工精修
