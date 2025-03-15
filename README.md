# Personal Resume Generator

This is a project for generating a personal resume page. It loads and parses Markdown files to display resume information and supports switching between Chinese and English.

## Features

- Load and display resume content in Markdown format
- Support for switching between Chinese and English
- Responsive design that adapts to different screen sizes

## Usage

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/WangZixuan-nus/CV.git
    ```

2. Open the `index.html` file:
    ```bash
    open index.html
    ```

3. By default, the page will load the English version of the resume content. Click the "中文/English" button in the top right corner to switch between Chinese and English versions.

## File Structure

- `index.html`: The main page file that contains the language switch button and the resume content container.
- `academics.md`: Resume content in English.
- `academics_cn.md`: Resume content in Chinese.

## Dependency

This project depends on the `marked.js` library for parsing Markdown files.

```html
<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
```

## Customization

You can modify the content of the `academics.md` and `academics_cn.md` files to generate different resume pages according to your needs.

## Example

You can view an example page generated by this tool [here](https://wangzixuan-nus.github.io/CV/).

## Contributing

Welcome to submit issues and pull requests to improve this project.

## License

This project currently does not specify a specific license.

--- 

# 个人简历生成工具

这是一个用于生成个人简历页面的项目，通过加载和解析 Markdown 文件来展示个人简历信息，并支持中英文切换。

## 功能

- 加载并展示 Markdown 格式的个人简历内容
- 支持中英文语言切换
- 响应式设计，适配不同屏幕尺寸

## 使用方法

1. 克隆此仓库到本地：
    ```bash
    git clone https://github.com/WangZixuan-nus/CV.git
    ```

2. 打开 `index.html` 文件：
    ```bash
    open index.html
    ```

3. 默认情况下，页面会加载英文版本的简历内容。点击右上角的“中文/English”按钮，可以在中英文版本之间切换。

## 文件结构

- `index.html`: 主页面文件，包含语言切换按钮和简历内容展示容器。
- `academics.md`: 英文版简历内容。
- `academics_cn.md`: 中文版简历内容。

## 依赖

该项目依赖 `marked.js` 库用于解析 Markdown 文件。

```html
<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
```

## 自定义

你可以根据自己的需求修改 `academics.md` 和 `academics_cn.md` 文件的内容来生成不同的简历页面。

## 示例

你可以在 [这里](https://wangzixuan-nus.github.io/CV/) 查看这个工具生成的示例页面。

## 贡献

欢迎提交 issues 和 pull requests 来改进这个项目。

## 许可

该项目目前没有指定具体的许可证。
