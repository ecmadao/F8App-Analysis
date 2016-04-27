## Analyse the source code of f8-app

### simple view of file tree in f8-app

```javascript
- index.android.js
- index.ios.js
- js
// main
-- env.js
-- F8App.js
-- F8Navigator.js
-- FacebookSDK.js
-- Playground.js
-- setup.js
// components
-- common
-- filter
-- login
-- rating
-- tabs
// reducer
-- actions
-- reducers
-- store
```

- Main Entry: `F8App.js`
  - if login: `F8Navigator.js`
  - else: `login/loginScreen.js`
- Extension: `Playground.js`
- Common Components: `common`

### Chapter 1 

  - [Common Component](./Chapter 1/0.Common Component.md)
  - [Navigator and basic framework](./Chapter 1/1.Navigator and basic framework.md)
  - [.GeneralScheduleView and ListContainer](./Chapter 1/2.GeneralScheduleView and ListContainer.md)