代号：前线 3.0（多人原型）
1. Windows 或 macOS 安装 Node.js 22 LTS 或更高版本：https://nodejs.org/
2. 解压文件，终端进入 frontline3 文件夹，运行 npm install（首次需要联网）。
3. 运行 npm start，浏览器打开 http://localhost:8080 。
4. 同一局域网的朋友打开 http://你的电脑局域网IP:8080 ，必要时允许防火墙的入站连接。
5. 公网联机需要把本项目部署到支持 Node.js 和 WebSocket 的服务器；启动命令 npm start，端口读取 PORT 环境变量。项目没有账号、房间隔离、机器人或正式反作弊，不建议作为无保护的公共服务长期运行。
操作：WASD 移动，空格跳跃，Shift 奔跑，鼠标瞄准，左键射击，R 换弹，1/2/3 切枪，E 拾取，Esc 退出鼠标锁定。医疗包自动恢复生命。安全区持续缩小，死亡可重生。人物为程序化低模3D几何模型。
