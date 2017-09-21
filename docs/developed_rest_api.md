## 基于RESTful api的开发

### 跨域

- [Ajax本地跨域问题 Cross origin requests are only supported for HTTP](http://www.cnblogs.com/feiqihang/p/4386456.html)

### Session在RESTful api

- [Reddit - Session in api middleware(英文)](https://www.reddit.com/r/laravel/comments/6j74wy/session_in_api_middleware/)

    [推荐阅读]
    My limited understanding of APIs led me to believe that they should be "stateless" which means they don't have sessions associated with them, and tokens are instead used to authorize the user. API keys could also be used to load/persist per user settings, but that's not the same as using a session.

- [Laravel Github - Issue #18187 Store session data per key](https://github.com/laravel/framework/issues/18187)
- [知乎 - 为什么在api.php里面也可以使用session?](https://www.zhihu.com/question/51914191)
- [Segmentfault - api 使用session替代token 的利弊在哪?](https://segmentfault.com/q/1010000008903882?_ea=1774333)

### Laravel 的 RESTful api 开发
- [Segmentfault - 搞一搞laravel里api路由的 auth:api 和 api_token?](https://segmentfault.com/a/1190000009911009)
- [在 Laravel 5 中如何限制 API 的调用频率](https://9iphp.com/web/laravel/laravel-and-api-rate-limiting.html)
