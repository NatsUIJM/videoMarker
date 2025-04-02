# 工具介绍

这是一个可以选取视频特定帧，进行简单标记（矩形、箭头、数字和文本），并将这一帧保存在本地的工具。

# 使用方法

1. 下载本工具：

    ```bash
    git clone https://github.com/NatsUIJM/videoMarker
    ```

2. 进入目录：
    ```bash
    cd videoMarker
    ```

3. 创建并激活虚拟环境
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

4. 安装依赖
    ```bash
    pip install flask
    ```

5. 运行服务
    ```bash
    python app.py
    ```

运行服务后，打开`http://127.0.0.1:5000`（或其他端口），页面上会显示一个视频播放器，你可以通过拖动进度条来选取视频的帧，然后进行简单标记。