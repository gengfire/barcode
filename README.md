# barcode
+ barcode and qrcode without canvas
+ 在快应用开发过程中，发现低版本不兼容canvas，遂整合了一个不依赖canvas生成barcode的纯js方法
+ qrcode 引自[qrcode-js](https://github.com/CloudService/qrcode-js)

## barcode
barcode.html
```javascript
var text = '031649618452969653';
var imgSrc = barcode(text, {
	barWeight: 2,
	height: 60,
	padding: 6
});
```

## qrcode
barcode.html
```javascript
var text = '031649618452969653';
var imgSrc = qrcode(text, {
	cellSize: 16,
	margin: 2,
	typeNumber: 4,
	level: 'Q'
});
```
