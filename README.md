#### vuex 源码学习
#### Travis CI持续集成构建项目

#指定运行环境
language: node_js
#指定nodejs版本，可以指定多个
node_js:
  - 0.12.5

#运行的脚本命令
script:
  - npm run ci

#指定分支，只有指定的分支提交时才会运行脚本
branches:
  only:
    - master

## Github装逼指南——Travis CI 和 Codecov
https://segmentfault.com/a/1190000004415437