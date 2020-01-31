TypeScript React Use React from CDN Demo
=========================================

如何使用来自cdn的react/react-dom，而不把它们打包。

关键在于webpack中`externals`的定义。

注意：
- 必须使用`ReactDOM`这个名字，大小写也不能变，否则找不到

```
npm install
npm run demo
```

It will open page on browser automatically.
