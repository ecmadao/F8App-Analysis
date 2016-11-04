# Analyse the source code of f8-app

> 分析 Facebook f8 App 的架构和实现

## Simple view of file tree in f8-app

```bash
+ index.android.js
+ index.ios.js
- js
    + env.js # environment config
    + setup.js # entry file
    + F8App.js # main component
    + F8Navigator.js # router controller
    + FacebookSDK.js
    # components
    + common
    + filter
    + login
    + rating
    + tabs
    # redux
    + actions
    + reducers
    + store
```

- 入口：`setup.js`，组建 store，渲染 RN

- 最外层组件：`F8App.js`

  - 如果用户已登录，则渲染：`F8Navigator.js`
  - 否则渲染：`login/loginScreen.js`

- 通用组件: `common`

## Menu

### Chapter 1 -- STRUCTOR

- [Main Structor](./Chapter 1/1.main_structor.md)

- [Navigator and Basic Framework](./Chapter 1/2.navigator_and_basic_framework.md)

### Chapter 2 -- COMMON COMPONENTS

- [Common Components](./Chapter 2/1.common_components.md)

- [GeneralScheduleView and ListContainer](./Chapter 2/2.general_schedule_view_and_list_container.md)
