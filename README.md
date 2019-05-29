# 同步滚动PDF和pdf解析出来的相同页数的dom元素列表

pdf 同步滚动 

---

## 一、布局
左边是PDF，右边是Dom元素列表
1. 当左边pdf滚动的时候，右边相对应的dom元素对应滚动当页的比例
2. 当右边dom元素滚动的时候，左边Pdf也相对应滚动当页的比例

## 二、页面嵌入pdf
1. 引入负责API解析文件pdf.js: https://cdnjs.cloudflare.com/ajax/libs/pdf.js/2.2.2/pdf.js
2. 引入负责核心解析文件pdf.worker.js： https://cdnjs.cloudflare.com/ajax/libs/pdf.js/2.2.2/pdf.worker.js
3. 把使用的url放在能访问到的位置

## 三、代码解析
见index.html
