## 项目简介

## 技术栈
React + Mobx

## 项目业绩

1 100%完成产品feature，
2 项目脚手架搭建，背景是这是一个全新的项目，并且当前部门其他项目使用的技术栈也比较过时，所以准备进行升级。首先是reflux已经停止维护，所以在redux和mobx中进行了调研，最终考虑到项目复杂度和时间成本选择了mobx。并且将发起api请求的原生AJAX封装改为了axios。同时router和webpack都升级到了4.x，并且配合react-loadable进行了懒加载。规范上添加了pre-commit进行git提交规范。最终产出是多个小型项目都使用了该脚手架。