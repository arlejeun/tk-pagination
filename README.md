# \<tk-pagination\>[![Build Status](https://travis-ci.org/cloudgz/tk-pagination.svg?branch=master)](https://travis-ci.org/cloudgz/tk-pagination)[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/cloudgz/tk-pagination)

`tk-pagination` is a simple pagination. It base on four properties:

- total: total number;
- pageSize: the number of pages displayed per page;
- maxLength: how many numbers would change the style of `tk-pagination`;
- currentPage: current page number.

`tk-pagination`是一个简单的分页器，它可以通过设置三个属性来显示不同的样式：

- total: 一共需要显示的条目；
- pageSize: 平均每一页显示的条目；
- maxLength: 样式上，超过多少页出现`...`过渡样式；
- currentPage: 当前页数

Example:

```html
<tk-pagination total="400" page-size="10" max-length="8" current-page="{{currentPage}}"></tk-pagination>
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