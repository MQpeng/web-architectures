## 性能优化准则

> We should forget about small efficiencies, say about 97% of the time: premature optimization is the root of all evil. Yet we should not pass up our opportunities in that critical 3%.

1. web项目初期应该为3%关键的性能优化奠定基础
2. 3%关键性的性能优化点
    1. 框架选型：优秀的web框架很好的平衡了性能和效率，因此一个好的框架同样是性能优化的开始
    2. 资源加载：资源的加载在code初期就提供了稳定有效的支撑服务，将大大优化性能和效率，以及减少产品会议的次数
        - 异步加载
        - 按需加载
        - 懒加载
        - 图片加载优化
        - 缓存优化
    3. 首屏优化：首屏快速显示是提升web项目用户好感的最直接的方式！这么重要的优化，应该在web项目架构初期就应该有稳定的方案落地解决，并规范开发
3. 性能监控平台的搭建越早越好