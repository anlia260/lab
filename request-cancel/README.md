# 中断请求（cancle request）

1. 连续请求，为了保证相同 API 的返回数据的时序性，中断 response time 过长的请求
2. 前端 SPA，切换路由，减少性能损耗，需要对于上一个 page 的请求进行中断

## 案例 1 经常会出现的相关场景

1. 实时搜索，如何保证最后一次搜索是最新的数据
2. 滚动加载的时候，如何保证列表的顺序是一致的，这个时候是不能`cancle request`

参考网址
[如何解决异步请求的竞态问题](https://zhuanlan.zhihu.com/p/113970301)
[单页面应用批量取消请求的最佳实](https://github.com/chunpu/blog/issues/98)
[JavaScript 异步时序问题](https://segmentfault.com/a/1190000019473988)
