# Outplay Gamehub 桌游教学网站

## 文件
- `index.html`：网站页面，含搜索、分类筛选、中英文切换、教学链接弹窗
- `games.js`：从最新上传的桌游清单整理的 43 款桌游名称和中英文教学链接
- `images/`：每款游戏的自制插画式缩略图（不是官方盒面照片）

## 发布到 GitHub Pages
将 `index.html`、`games.js` 和整个 `images` 文件夹上传到 GitHub repository 根目录，覆盖同名旧文件。然后到 Settings → Pages 确认 `main` 和 `/(root)`。等待部署后打开网站。

## 图片说明
目前每款游戏都有配色一致的插画式图片，不再只显示 emoji。这些是为网站制作的插画式缩略图，并非官方游戏盒面照片。若之后想用真实盒面照片，可逐款替换 `images/` 里的图片，并在 `games.js` 保持相同图片路径。
