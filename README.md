# 锦鲤上岸

这是《锦鲤上岸》的 GitHub Pages 静态发布版本。

## 上传内容

请将本文件夹中的全部内容上传到 GitHub 仓库根目录，包括隐藏文件 `.nojekyll`。

```text
index.html
styles.css
game.js
favicon.ico
game-assets/
.nojekyll
```

不要只上传 `index.html`，游戏依赖 `game-assets` 中的图片和音乐。

## 开启 GitHub Pages

1. 打开仓库的 `Settings`。
2. 进入 `Pages`。
3. 在 `Build and deployment` 中选择 `Deploy from a branch`。
4. Branch 选择 `main`，目录选择 `/ (root)`。
5. 保存并等待 GitHub 生成访问地址。

访问地址通常为：

```text
https://你的用户名.github.io/仓库名/
```

## 隐私提醒

此发布版本仍包含纪念卡图片。第 5、6 张已替换为卡通化图片，但上传到公开仓库后，仓库中的全部图片和音乐仍可被任何访问者下载。请在发布前再次确认其余纪念内容适合公开。

## 本地预览

不能依靠双击 `index.html` 完整模拟 GitHub Pages。可在此目录启动静态服务器：

```powershell
npx serve .
```

然后访问命令行显示的本地地址。
