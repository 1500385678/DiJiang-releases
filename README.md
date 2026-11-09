# DiJiang-releases

DiJiang 桌面版的**更新分发仓**。

这个仓只放三样东西：

- `DiJiang-Setup-<版本>.exe` —— Windows 安装包
- `DiJiang-Setup-<版本>.exe.blockmap` —— 增量更新的差分包
- `latest.yml` —— 更新清单（版本号、文件名、大小、sha512）

客户端（`electron-updater` 的 github provider）从这里取清单：
`https://github.com/1500385678/DiJiang-releases/releases/latest/download/`

**源码在私有仓** [`1500385678/DiJiang`](https://github.com/1500385678/DiJiang)，这里只有构建产物。

发布由 `G:\_MyGitProject\Forma-Electron` 的 `npm run publish:update` 完成。
