<h1 style="text-align:center">
CSS Split Webpack Plugin
</h1>
<p style="text-align:center">
for css file split
</p>

<h2 style="text-align:center">
  Install
</h2>
<p>
Don't have npm package now,just clone the rep and copy to your project
</p>

<h2 style="text-align:center">
  Usage
</h2>

```javascript
const CSSSplitPlugin=require("please enter your file path")

module.exports = {
  //
  plugins: [
    new CSSSplitPlugin({
      //default:1
      splitCount:2
    }),
  ]
}

```