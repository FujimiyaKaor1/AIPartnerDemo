# AI 智能伴侣 ❤️

一个基于 Streamlit 和 DeepSeek API 构建的 AI 智能伴侣聊天应用。

## 功能特性

- 🤖 **AI 伴侣对话** - 基于大语言模型的智能伴侣角色扮演
- 💬 **流式输出** - 实时显示 AI 回复，提升交互体验
- 📝 **会话管理** - 支持创建、保存、加载和删除聊天会话
- ⚙️ **自定义伴侣** - 可自定义伴侣昵称和性格特征
- 🎨 **友好界面** - 基于 Streamlit 的现代化 Web 界面

## 技术栈

- **前端框架**: Streamlit
- **AI 模型**: DeepSeek API
- **语言**: Python 3.x

## 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/FujimiyaKaor1/AIPartnerDemo.git
cd AIPartnerDemo
```

### 2. 安装依赖

```bash
pip install streamlit openai
```

### 3. 配置 API Key

设置环境变量：

**Windows (PowerShell):**
```powershell
$env:DEEPSEEK_API_KEY = "your-api-key-here"
```

**Linux/macOS:**
```bash
export DEEPSEEK_API_KEY="your-api-key-here"
```

### 4. 运行应用

```bash
cd lesson1
streamlit run AiPartner.py
```

## 使用说明

### 伴侣设置

在左侧边栏可以自定义：
- **昵称**: AI 伴侣的称呼
- **性格**: 描述伴侣的性格特征（如：活泼开朗的东北姑娘）

### 会话管理

- 点击 **新建会话** 创建新的聊天
- 点击会话列表中的会话名可加载历史记录
- 点击 ❌ 按钮可删除对应会话

## 项目结构

```
lesson1/
├── AiPartner.py        # 主程序文件
├── resources/
│   └── logo.png        # 应用 Logo
└── sessions/           # 会话数据存储目录（自动创建）
```

## 注意事项

- 请确保已获取 DeepSeek API Key
- 会话数据保存在本地 `sessions/` 目录
- 请勿将 API Key 提交到代码仓库

## License

MIT License
