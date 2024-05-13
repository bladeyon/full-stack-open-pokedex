# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full stack open course

Fork the repository to complete course exercises

## Commands

Start by running `npm install` inside the project folder

`npm start` to run the webpack dev server
`npm test` to run tests
`npm run eslint` to run eslint
`npm run build` to make a production build
`npm run start-prod` to run your production build

## update fork git

要更新 fork 的 Git 仓库，可以按照以下步骤操作：

1. 添加远程仓库：`git remote add upstream <original-repo-url>`
2. 获取最新的更改：`git fetch upstream`
3. 合并更改：`git merge upstream/master` (假设你想要合并 master 分支)
4. 推送更改：`git push origin master`
   注意：

- `<original-repo-url>` 是原始仓库的 URL。
- `upstream` 是远程仓库的名称，你可以随意命名。
- `origin` 是你的 fork 仓库的名称。
  如果你想要保持你的 fork 仓库与原始仓库同步，可以使用以下命令：
  `git pull --rebase upstream master`
  `git push origin master`
  这将获取最新的更改，并将其应用到你的 fork 仓库中。
