# lab

面对一些前端问题的思考

## 中断请求（cancle request）

1. 连续请求，为了保证相同 API 的返回数据的时序性，中断 response time 过长的请求
2. 前端 SPA，切换路由，减少性能损耗，需要对于上一个 page 的请求进行中断
