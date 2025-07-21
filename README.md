# 📝 React ToDo App（JavaScript）

![JavaScript](https://img.shields.io/badge/Code-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/Library-React-61DAFB?logo=react&logoColor=black)

## 📌 概要

React と JavaScript を用いて作成したシンプルな ToDo アプリです。  
タスクの追加／完了(チェック)／削除といった基本的な機能を実装しています。

## 💡 学習目的・工夫した点

- React の基本的な構成（関数コンポーネント、Props、Hooks）を理解するために取り組みました。
- 状態管理には useState、フォーム操作には　useRef を使用しています。
- uuid パッケージを使い、タスクごとに一意のIDを付与しています。
- toggleTodo による状態の切り替えなど、再レンダリング の仕組みを意識した設計を心がけました。

## ⚙ 使用技術
![JavaScript](https://img.shields.io/badge/Code-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/Library-React-61DAFB?logo=react&logoColor=black)
- JavaScript
- React

## 📷 機能紹介

- ✅ タスクの追加（空文字は無視）
- ✅ タスクの完了チェック切り替え
- ✅ 完了済みタスクの一括削除
- ✅ 未完了タスクの数を表示

## 🚀 今後、実装予定

- localStorage によるデータ永続化
- コンポーネントのさらなる分離（Form, Filter等）
- CSSでのデザイン強化
- TypeScript化

Todoアプリはこちら→ https://mitsutakaninomiya.github.io/react-tutorial-youtube/



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
