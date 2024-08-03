# FFmpeg GUI Converter

不太实用的ffmpeg gui，能实现基本的格式转换
<br><br>
![image](https://github.com/user-attachments/assets/65b4883c-c227-4119-8872-695ea72b7bdb)


## 特点

- 支持大部分FFmpeg功能
- 可以处理整个文件目录
- 支持包括MP4在内的六种常见格式
- 可添加额外参数
- 多余的动画
- 传奇依托白话菜比代码

## 安装与使用

### 安装FFmpeg

如果你还没有安装FFmpeg，可以通过以下两种方式进行安装：

- 使用 `winget` 安装：
  ```shell
  winget install "FFmpeg (Essentials Build)"
  ```

- 或从 [FFmpeg官方网站](https://www.gyan.dev/ffmpeg/builds/#release-builds) 下载 `FFmpeg Essentials Build` 并解压到同目录。

### 方法一：下载预编译的可执行文件

1. 访问 [Releases 页面](https://github.com/zDichX/FFmpeg-GUI-Converter/releases) 
2. 下载最新版本的 `.exe` 程序
3. 运行程序
4. 拖拽文件到窗口或选择文件
5. 选择目标格式
6. 点击 **Execute** 按钮
7. 等待转换完成（程序将在完成后自动退出）

### 方法二：Git Clone

1. 不用教

## p.s.

1. 单个文件会转换后保存至同目录，文件夹会保存至 `converted_files` 文件夹。
2. 我不会写代码，孩子不懂事传着玩的
3. 无论发生什么，请尽可能认为这是正常的

---
---

# FFmpeg GUI Converter

This is a GUI-based conversion tool built on FFmpeg, designed to handle basic format conversions.

## Features

- Supports most FFmpeg features
- Can handle entire directories
- Supports six common formats, including MP4
- Allows the addition of extra parameters
- Animations

## Installation & Usage

### Install FFmpeg

If you don't have FFmpeg installed, you can install it using the following methods:

- Install via `winget`:
  ```shell
  winget install "FFmpeg (Essentials Build)"
  ```

- Or download the `FFmpeg Essentials Build` from [FFmpeg Official Website](https://www.gyan.dev/ffmpeg/builds/#release-builds) and extract it to the same directory as this tool.

### Method 1: Download Precompiled Executable

1. Visit the [Releases page](https://github.com/zDichX/FFmpeg-GUI-Converter/releases)
2. Download the latest version of the `.exe` program
3. Run the program
4. Drag and drop files into the window or select a file manually
5. Choose the target format
6. Click the **Execute** button
7. Wait for the conversion to complete (It will automatically exit upon completion)

### Method 2: Compile from Source

1. `git clone`
2. I bet you know what's the next

## Additional Information

1. Converted files will be saved in the same directory as the original for single files, and in the `converted_files` folder for directories.
2. Please note that this is a simple, fun tool, I'm not a professional developer.
