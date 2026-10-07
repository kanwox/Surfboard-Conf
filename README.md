# 🏄‍♂️ Surfboard 规则配置

专为 Android 平台 [Surfboard](https://getsurfboard.com/) 客户端调优的分流与规则配置文件，开箱即用、低延迟、分流明确。

---

### 🚀 配置一键导入链接 (Direct URL)

在 Surfboard 中选择 **从 URL 导入 (Import from URL)** 并填入下方链接：

```text
https://raw.githubusercontent.com/kanwox/Surfboard-Conf/main/Surfboard.conf
```

> 💡 **提示**：如果网络访问 GitHub Raw 较慢，可使用加速镜像导入（如 `https://ghproxy.net/https://raw.githubusercontent.com/...`）。

---

## ⚡ 核心亮点

- **智能分流**：国内常见站点与直连服务走 `DIRECT`，海外流量走 `PROXY`，兼顾速度与电量。
- **流媒体与常用服务分组**：针对 Netflix、YouTube、Disney+、OpenAI/ChatGPT 等常用平台预设独立策略组。
- **隐私与广告过滤**：内置轻量级去广告及隐私追踪拦截规则，保持页面清爽，不影响正常解析速度。
- **DNS 优化**：预设兼顾低延迟与防污染的 DNS 策略，减少解析异常与劫持。

---

## 📲 快速使用指南

1. **复制直达链接**：点击上方代码框复制配置链接。
2. **导入配置**：
   - 打开 Surfboard 客户端。
   - 点击底部导航栏的 **「配置 (Profile)」**。
   - 点击右上角 **`+`** 按钮，选择 **「从 URL 导入」**。
   - 粘贴直达链接并保存下载。
3. **添加节点**：导入你自己的机场/代理节点或订阅链接，并绑定到对应的策略组中。
4. **启动连接**：在首页点击连接开关，即可享受顺畅的网络分流体验。

---

## 📌 注意事项

- 本配置文件为**规则模板**，本身**不包含任何代理节点**，需自行搭配有效节点/订阅使用。
- 建议在客户端中开启定时更新，以获取最新的分流规则与去广告策略。
