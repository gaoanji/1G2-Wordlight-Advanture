# 词光奇境大冒险

《词光奇境大冒险》是一款为中一 G2 学生设计的华文词语复习闯关游戏。学生将与熊猫小侠和水獭灵灵一起探索词光奇境，完成不同类型的词语挑战、收集徽章与星星，并最终唤醒词光宝珠。

## 游戏特色

- 词语学习卡、拼音、词义、语境与综合挑战
- 关卡解锁、地图探索和角色移动动画
- 徽章、星星和最终词光宝珠奖励
- 学生排行榜与个人最佳成绩记录
- Google Spreadsheet 学习数据同步
- 电脑与手机浏览器均可使用

## 文件说明

- `index.html`：游戏主页及主要功能
- `assets/`：图片、音乐、音效、徽章和角色素材
- `adventure.css`、`scenes.css` 等：页面样式
- `sentences.js`：不同关卡使用的题目句子
- `scenes.js`：游戏场景、徽章与地图功能
- `user-ui.js`：用户资料与设置功能
- `music.js`：背景音乐控制
- `effects.js`：按钮及徽章音效
- `leaderboard.js`：排行榜及数据同步
- `apps-script/Code.gs`：Google Spreadsheet 后台代码备份
- `.nojekyll`：确保 GitHub Pages 正确读取网站文件

## GitHub Pages 发布

1. 把本项目中的所有文件和文件夹上传到 GitHub 仓库的 `main` branch。
2. 确保 `index.html` 与 `assets` 文件夹并列放在仓库最外层。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. 选择 `main` branch 和 `/ (root)`，然后保存。

不要在仓库最外层额外套一层总文件夹，否则网页可能无法找到图片、音乐和其他素材。

## 数据连接

游戏通过 Google Apps Script 连接 Google Spreadsheet，记录学生的姓名、班级、完成关卡、准确率、用时、成绩、徽章和星星。

如需更换数据表，请更新 `leaderboard.js` 中的 Google Apps Script Web App 地址，并重新部署相应的 `Code.gs`。

## 最终宝物素材

以下文件应放在 `assets/` 文件夹中：

- `wordlight-orb.png`：词光宝珠
- `panda-celebrate.png`：庆祝的熊猫小侠
- `otter-celebrate.png`：庆祝的水獭灵灵

## Copyright and Use

Game design and educational content © 2026 **Miss Gao Anji, Bedok Green Secondary School**.

This resource was created for educational use. Please seek permission from the creator before copying, modifying, republishing or redistributing the game or its educational content.

Third-party fonts, music, software libraries and AI-assisted assets remain subject to their respective terms of use.

## 制作信息

- 设计与教学内容：**Miss Gao Anji**
- 学校：**Bedok Green Secondary School**
- 用途：华文教学与课堂学习

