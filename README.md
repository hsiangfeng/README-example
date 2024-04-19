<!-- 底下標籤來源參考寫法可至：https://github.com/Envoy-VC/awesome-badges#github-stats -->

![](https://img.shields.io/github/stars/hsiangfeng/README-Example-Template.svg)｜![](https://img.shields.io/github/forks/hsiangfeng/README-Example-Template.svg)｜![](https://img.shields.io/github/issues-pr/hsiangfeng/README-Example-Template.svg)｜![](https://img.shields.io/github/issues/hsiangfeng/README-Example-Template.svg)

> EMU200 Automation Instructions



> This is an instruction that direct users to install automation testing software on their devices.。

- [線上觀看連結](https://israynotarray.com/)

## Prerequisites
Node.js 18+

npm 9.6+

Windows 10+, Windows Server 2016+ or Windows Subsystem for Linux (WSL).

MacOS 12 Monterey, MacOS 13 Ventura, or MacOS 14 Sonoma.

Debian 11, Debian 12, Ubuntu 20.04 or Ubuntu 22.04, with x86-64 or arm64 architecture.

Python 2.7 or above. The tutorial of installing Python with Visual Studio Code (https://code.visualstudio.com/docs/python/python-tutorial).





## Installation in Visual Studio Code

> Follow the instructions to install this automation test properly on your device.


### Get the project

```bash
git clone git@github.com
```
### Install Node.js
```bash
Need to install the following packages:
create-playwright@1.17.132
Ok to proceed? (y) y
Getting started with writing end-to-end tests with Playwright:
Initializing project in '.'
√ Do you want to use TypeScript or JavaScript? · JavaScript
√ Where to put your end-to-end tests? · tests
√ Add a GitHub Actions workflow? (y/N) · false
√ Install Playwright browsers (can be done manually via 'npx playwright install')? (Y/n) · true
Initializing NPM project (npm init -y)…
Wrote to C:\Users\a0976\emu\package.json:

{
  "name": "emu",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}

```
Installing Playwright Test (npm install --save-dev @playwright/test)…

### Install Playwright Packages

```bash
npm init playwright@latest
```

### Check the validity 

請在終端機輸入 `cp .env.example .env` 來複製 .env.example 檔案，並依據 `.env` 內容調整相關欄位。

### Run the project approach 1

```bash
npm playw
```

### Test Result

在瀏覽器網址列輸入以下即可看到畫面

```bash
http://localhost:8080/
```

### Environment variables (Dotenv)

```bash
帳號： example@example.com
密碼： example
```

- [x] 登入
- [x] 登出
- [x] 產品列表
...




## 環境變數說明

```env
APIPATH= # API 位置
COUSTOMPATH= # 自訂變數
...
```

## 資料夾說明

- views - 畫面放置處
- controllers - 控制器放置處
- modules - 模組放置處
- assets - 靜態資源放置處
  - scss - scss 檔案放置處
  - images - 圖片放置處
...

## 專案技術

- Node.js v16.15.0
- Vue v3.2.20
- Vite v4.0.4
- Vue Router v4.0.11
- Axios v0.24.0
- Bootstrap v5.1.3
...

## 第三方服務

- Algolia
- Google Analytics
...

## CI/CD 說明

此專案有使用 Github Actions，所以發起 PR 時會自動執行以下動作：

- 建立 Node.js 環境
- 安裝相依套件
- 編譯程式碼
- 執行 ESLint 掃描
- 執行測試
...

當專案 merge 到 main 時會自動執行以下動作：

- 建立 Node.js 環境
- 安裝相依套件
- 編譯程式碼
- 執行 ESLint 掃描
- 執行測試
- 部署到 Github Pages
...

## 聯絡作者

> ps. 這邊絕對不是業配，而是要適當提供一些方式讓觀看者知道你的聯絡方式，讓他們可以更方便的找到你。

你可以透過以下方式與我聯絡

- [部落格](https://israynotarray.com/)
- [Facebook](https://www.facebook.com/israynotarray)
- [Instagram](https://www.instagram.com/isray_notarray/)
...
