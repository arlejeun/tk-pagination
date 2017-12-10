# \<tk-pagination\>[![Build Status](https://travis-ci.org/cloudgz/tk-pagination.svg?branch=master)](https://travis-ci.org/cloudgz/tk-pagination)[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/cloudgz/tk-pagination)

# Install

```sh
bower install cloudgz/tk-pagination --save
```

`tk-pagination` is a simple pagination. It base on the following these properties:

- total: total number;
- pageSize: the number of pages displayed per page;
- maxLength: how many numbers would change the style of `tk-pagination`;
- currentPage: current page number.
- noJumpDevice: hide the jump device.
- noPageCount: hide the page count.
- totalText: total text.
- pageQuantifier: page quantifier.
- itemQuantifier: item quantifier.
- jumpButtonText: jump device button text. 

`tk-pagination`是一个简单的分页器，它可以通过设置以下这些属性来显示不同的样式：

- total: 一共需要显示的条目；
- pageSize: 平均每一页显示的条目；
- maxLength: 样式上，超过多少页出现`...`过渡样式；
- currentPage: 当前页数；
- noJumpDevice: 隐藏跳转输入框以及按钮；
- noPageCount: 隐藏页面统计器；
- totalText: 统计标签文本；
- pageQuantifier: 页数统计量词，默认为`页`；
- itemQuantifier: 条目统计量词，默认为`条`；
- jumpButtonText: 跳转器按钮文本，默认为`跳转`；

Example:

```html
<tk-pagination
  no-page-count
  no-jump-device
  total="400"
  page-size="10"
  max-length="8"
  current-page="{{currentPage}}"></tk-pagination>
```

# Develop

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Run the test

```
polymer test
```

## Lint

```
npm run lint
```