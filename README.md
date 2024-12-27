# love-web
基于HTML+CSS+JavaScript实现的静态网页，模仿《点燃我温暖你》电视剧中出现的爱心代码  
### 文件构成
`index.html` 主文件  
`css/style.css` 样式文件  
`js/heartAnimation.js`和`heartParticles.js` 网页动效文件 

### 修改说明
如需修改网页中的文字，请修改`js/heartAnimation.js`文件中的第64行
```
63 ctx.fillText(
64    "FRY", // 画面中显示的文字
65    this.x - this.width * 0.5,
66    this.y - this.height * 0.5,
67    this.width,
68    this.height
69  );
```
