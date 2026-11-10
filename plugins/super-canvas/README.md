# Super Canvas Plugin

让 Codex / ZCode 可以打开并操作 Super Canvas。

## 安装

### Codex

macOS / Linux：

```bash
git clone https://github.com/superaddmin/Super-canvas.git
cd super-canvas
codex plugin marketplace add "$(pwd)"
codex plugin add super-canvas@super-canvas-local
```

Windows PowerShell：

```powershell
git clone https://github.com/superaddmin/Super-canvas.git
cd super-canvas
codex plugin marketplace add "$PWD"
codex plugin add super-canvas@super-canvas-local
```

Windows CMD 将 `$PWD` 替换为 `%cd%`。

### ZCode

- 打开 **Settings → Plugin Management → Discover**，点击右上角 **`+`** 添加 marketplace。
- 选择 **本仓库目录**（`plugins/super-canvas`）或本仓库根目录，即可发现 `super-canvas` 插件并安装。
- 或在 ZCode 界面直接以本地目录方式加载该插件目录。

安装后新建一个任务，然后输入：

```text
帮我打开并连接到 Super Canvas
```
