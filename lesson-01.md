# Git 学习笔记 · 第 2 课：init 与第一次 commit

## 本课路线
git init → 剖析 .git → 配置身份 → 第一次完整 commit

## 关键概念
- `git init`：把普通文件夹升级为仓库，创建 .git 目录（装好时光机 ≠ 拍了照）
- `.git` 目录：仓库的心脏，objects/ 存历史，refs/ 存分支指针，HEAD 记录当前位置
- 身份配置三层级：system < global < local，就近覆盖；global 配一次全机通用
- 三区模型：工作区（草稿纸）--git add--> 暂存区（取景框）--git commit--> 仓库（相册）

## 本机环境
- git 2.54.0.windows.1
- 仓库创建于 GIt learning 文件夹，初始分支 main

## 追加陷阱实验区
这行是【第一次】写入的内容。
这行是【第二次】写入的内容——发生在 add 之后！

## 分支心得
main 是定稿线，dev 是实验线——两边可以各自推进。
