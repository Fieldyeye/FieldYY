
```
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
```
引入外部字体
```
<style>
.red-text {
color: red;
}

p {
font-size: 16px;
font-family: Monospace;
}

.thick-green-border {
border-color: green;
border-width: 10px;
border-style: solid;
border-radius: 50%;

}

.smaller-image {
width: 100px;
}
</style>
```
css 格式

`<h2 class="red-text">CatPhotoApp</h2>`
标题


`<p>Click here for <a href="#">cat photos</a>.</p>`
添加链接


```
<ul>
<li>cat nip</li>
<li>laser pointers</li>
<li>lasagna</li>
</ul>
```
无序列表


```
<ol>
<li>flea treatment</li>
<li>thunder</li>
<li>other cats</li>
</ol>
```
有序列表


```
<form action="/submit-cat-photo">
<label><input type="radio" name="indoor-outdoor"> Indoor</label>
<label><input type="radio" name="indoor-outdoor"> Outdoor</label>
<label><input type="checkbox" name="personality"> Loving</label>
<label><input type="checkbox" name="personality"> Lazy</label>
<label><input type="checkbox" name="personality"> Energetic</label>
<input type="text" placeholder="cat photo URL" required>
<button type="submit">Submit</button>
</form>
```
表单、单选框、复选框、文本输入、按钮

checked 表示默认被选中 
