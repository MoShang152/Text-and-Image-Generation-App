# 文本和图像生成应用

这是一个使用 OpenAI 的 GPT-4 模型生成文本并处理图像上传的 Web 应用程序。该应用程序使用 Flask 作为后端，并使用 HTML、CSS 和 JavaScript 进行前端开发。

## 功能

- 根据用户输入生成文本
- 上传和预览图像
- 显示用户和机器人消息的对话历史记录

## 安装

1. 克隆仓库：

```
git clone <repository_url>
```

2. 进入项目目录：

```
cd <project_directory>
```

3. 安装所需依赖项：

```
pip install -r requirements.txt
```

4. 运行应用程序：

```
python app.py
```

5. 打开浏览器并访问 `http://localhost:5000` 以查看应用程序的效果。

## 文件结构

- `app.py`：主 Flask 应用文件。
- `templates/index.html`：Web 界面的主要 HTML 文件。
- `static/styles.css`：用于样式化 Web 界面的 CSS 文件。
- `static/script.js`：用于处理前端交互的 JavaScript 文件。

## 使用方法

1. 在文本输入框中输入您的消息。
2. （可选）点击上传按钮上传图像。
3. 点击发送按钮提交您的消息并查看机器人的回复。

## 贡献

如果您想为本项目做出贡献，请随时提交问题和拉取请求。

## 许可证

本项目使用 GNU General Public License v3.0 许可证。
