# Todo List

## 已完成

- [x] 参考 Open Design 原型完成客户端主界面基础风格。
- [x] 将产品中文名调整为“营销大师”，英文名调整为“Channel Nest”。
- [x] 将项目结构整理为 `frontend` 和 `backend/channel_nest_api`。
- [x] 实现账号密码登录、注册、验证码和登录后使用客户端。
- [x] 实现退出登录后回到登录页。
- [x] 实现个人信息修改和密码修改。
- [x] 通过头像菜单进入个人信息和修改密码页面。
- [x] 将配置改为 JSON 文件方式，减少环境变量依赖。
- [x] 实现渠道管理的多平台入口：小红书、视频号、抖音、B 站、快手。
- [x] 支持每个平台下绑定多个账号。
- [x] 将渠道账号按当前业务用户隔离，避免不同用户共享账号列表。
- [x] 使用 Tauri WebView 承载各平台网页登录和创作中心页面。
- [x] 保存各平台账号的 `login_cookie` 和 `webview_session_id` 到本地 store。
- [x] 小红书改为以创作中心登录作为授权成功标准。
- [x] 抖音改为两段式流程，并支持打开抖音创作者中心。
- [x] B 站和快手改为应用内 WebView 登录。
- [x] 增加账号主页入口，点击后打开对应平台创作中心或主页。
- [x] 增加更新公告页面和自动更新相关入口。
- [x] 配置 GitHub Actions 打包 macOS 和 Windows 桌面端。
- [x] 统一发布产物命名为 `Channel_Nest_<version>_<platform>_<arch>` 风格。
- [x] 修复 Windows 打包时根目录缺少 `build` 脚本的问题。
- [x] 修复 macOS 打包时 Tauri 参数转发导致 `--target` 丢失的问题。
- [x] 修复 Windows 平台账号主页 WebView 左上角关闭按钮无法关闭的问题。
