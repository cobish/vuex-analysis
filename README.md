# vuex-analysis
vuex 源码解析

## 前言

一直想完整地阅读一个库的源码，但无奈没有坚持下来。摸过 jQuery，尝过 underscore，但都半途而废了，真是郁闷至极。反思了再反思，一方面是自己的基础还不够扎实，另一方面是有点大跃进（一下子拿那么大的库来研究，还真有点坚持不下来）。

说了这么多，只能说自己还是太 simple 了。这次我想试着研究 vuex 的源码，它的代码相比来说少很多，而且日常也经常使用到，会比较熟悉，希望自己能够坚持阅读完吧。

这一次我不打算逐行研究代码，而是打算从一个大体的方向去了解整个库，所以只会有核心代码的解析。虽然这样可能会有点浅尝辄止，但我相信只要了解了整体结构，接下来具体的代码实现在以后想了解时再仔细查阅与学习也不迟。

开始吧......

## 计划

这一次主要是对 vuex 的 state、getter、mutation、action 和 module 做一个深入的了解，对插件与热重载暂时忽略。

- [ ] vuex 是如何安装。
- [ ] State 的实现原理。
- [ ] mapState 的实现原理。
- [ ] Getter 的实现原理。
- [ ] mapGetter 的实现原理。
- [ ] Mutation 的实现原理。
- [ ] mapMutation 的实现原理。
- [ ] Action 的实现原理。
- [ ] mapAction 的实现原理。
- [ ] Module 的实现原理。

## License

MIT

