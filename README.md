# 📘 AdonisJS API boilerplate for Electron
Purpose of this Repository is to run AdonisJS as a Backend Server in Electron

### Initial Setup
- Create an AdonisJS API Project
- Build the Project
- Copy **Build** directory and paste inside this repo and rename to **App**
- Also copy **.env** from project and paste inside **app**
- Run MySQL and create database

### Installing dependencies
- Run `npm i --g @adonisjs/cli`
- Run `npm install` inside Project **Root** Directory and inside **app** directory

## 🔥 Development
- Then in the **Root** directory, run `npm run start`
## 📦 Building
- If Electron starts without an error in Development, then run following command to **publish an App**
  - `npx electron-packager . app2 --platform=darwin` _For MacOS_
  - `npx electron-packager . app2 --platform=win32` _For Windows_
  - `npx electron-packager . app2 --all` _For All Platform_
  - Optionally `--asar` flag can be used

## 📝 Todo's
- [ ] Adding splash screen
- [ ] Use **PM2**
