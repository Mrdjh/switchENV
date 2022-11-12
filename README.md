# switch ENV

开发过程中，可能需要电脑共存n个版本的软件  如`php`,`composer`,`node`,`java`等

使用本软件，可以灵活切换当前环境的软件变量（无需重启cmd）

## 使用教程

1. 你需要灵活切换版本的软件`不要`加入环境变量，纯用本软件管理（使用本软件前先删掉）
2. 本软件安装目录需要添加俩个环境变量，假设本软件安装在`D:\switchENV\`，则需要添加以下环境变量
- D:\switchENV\
- D:\switchENV\bat
3. 启动本软件: cmd 输入`./switchENV.exe` 或者运行 `swtichENV.bat`
4. 页面可视化配置和切换


## 开发

- 下载代码
- `go run main.go`
- 前端代码说明看`kernel/public/README.md`

### 规划

- [ ] github CICD 自动打包exe