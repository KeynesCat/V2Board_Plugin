## V2Ray Plugin For V2Board

### 安装

1. 下载

   ```bash
   git clone https://github.com/thank243/V2Board_Plugin.git
   ```

2. 安装依赖

   ```bash
   pip3 install grpcio google-api-python-client
   ```


### 使用

1. 增加执行权限

   ```bash
   chmod +x main.py v2ray -R
   ```
   
2. 修改cfg.json中的内容
    ```bash
   vi cfg.json
    ```

3. 运行程序
   ```bash
   ./main.py
   ```
