# SRI-assessing-platform
SRI（Sexual Repression Index）性压抑指数测试网站，题目来自哈佛心理学系社区。
# 性压抑指数评估平台

🚀 **一键启动，无需复杂配置的心理评估工具**

## 特性如下

- 🎯 **极简部署** - 只需Python，一键启动
- 📱 **响应式设计** - 支持手机和电脑
- 🔒 **结果完全匿名** - 无需注册，保护隐私
- ⚡ **即时结果** - 实时计算，立即查看
- 🧠 **科学评估** - 基于可靠题目来源（虽然经大模型翻译了一手，有的题目看起来不太可靠了）
- 💾 **内存存储** - 无需数据库，重启项目会损毁所有已测试结果

## 🚀 快速开始

#每步运行上方指令即为启动简单版本，下方指令即为启动增强版

### Windows用户
```bash
# 双击运行
start_simple.bat
start_enhanced.bat
```

### Linux/Mac用户
```bash
# 给脚本执行权限
chmod +x start_simple.sh
chmod +x start_enhanced.sh

# 运行启动脚本
bash start_simple.sh
bash start_enhanced.sh
```

### 手动启动
```bash
# 安装依赖
pip install flask
pip3 install flask

# 启动应用
python simple_app.py
python enhanced_app.py
```

### 宝塔部署

# 上传项目文件夹到宝塔面板的wwwroot文件夹
# 网站选择python项目
# 添加项目-选择项目路径（记得选到简化版或增强版文件夹），项目名称会自动填充，或者你爱写啥写啥
# 选择python版本，选你喜欢的即可
# 运行指令填入上方bash脚本的对应版本即可

## 📱 访问方式

启动后访问：
- **本地访问**: http://localhost:6061
- **局域网访问**: http://你的IP:6061

# 参考站：sri.rstqxq.com