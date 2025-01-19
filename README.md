<html>
 <head>
     <title>Bài 17: Các mức ưu tiên của bộ</title>
 </head>
  <body>
  <h1>Luyện tập 1: Giải thích sự khác nhau giữa hai định dạng sau:</h1>
    <img src="![ca714c339f8e23d07a9f](https://github.com/user-attachments/assets/b5c7e8b3-b3c3-46e8-9991-9292dec0bcc8)
" width="1062" height="395" alt="Luyện tập 1">
  <p>• #p123 + p {color: red;} : áp dụng cho phần tử p với điều kiện phần tử p nằm ngay sau phần tử bất kì có mã định danh #p123

•h2#p123 + p {color: red;}: áp dụng cho phần tử p với điều kiện phần tử p nằm ngay sau phần tử h2 có mã định danh #p123</p>
  <h1>Luyện tập 2:Trong phần Thực hành, các tên riêng (tên người, tên tổ chức) cần được bổ sung định dạng đóng khung và in nghiêng. Em sẽ thực hiện các yêu cầu này như thế nào?</h1>
  <p>• Đưa các tên riêng vào thẻ <em> </em>

• Tạo mẫu định dạng CSS cho phần tử <em>: em {font-style: italic; border: 1px solid blue;}</p>
 <h1> Vận dụng 1: Tìm hiểu thêm các dạng pseudo-class khác, nêu ý nghĩa và tìm ví dụ ứng dụ thực tế cho các kiểu bộ chọn này</h1>
   <p>Các trạng thái của phần tử input:

checked: được chọn (type=checkbox)

focus: được chọn (type=text)

enabled: sẵn sàng nhập dữ liệu

disabled: vô hiệu hóa phần tử input

valid: có hiệu lực

invalid: không có hiệu lực</p>
 <img src="![124](https://github.com/user-attachments/assets/984f14a6-9af9-47bb-81b5-430a704e2265)

" width="831" height="227" alt="Ảnh minh họa">

input:checked {height: 50px; width: 50px;}

input: valid {background-color: yellow;}

input: invalid {background-color: magenta;}

input[type=text]: enabled {background: cyan;}

input[type=text]: disabled {background: silver;}

</style></p>
<h2>Giải</h2>
<img src="![125 html](https://github.com/user-attachments/assets/a26a30a3-52a1-4e55-ac2a-c8cb0a00c18c)

" width="713" height="425" alt="Ảnh minh họa">
<p><html>

<head>

<style>

input:checked (height: 50px; width: 50px;}

input: valid {background-color: yellow;}

input: invalid (background-color: magenta;}

input[type=text]: enabled {background: cyan;}

input[type=text]: disabled {background: silver;}

</style>

</head>

<body>

<form action="">

First name: <input type="text" name="firstname"><br><br>

Last name: <input type="text" name="lastname"><br><br>

Email: <input type="email"><br><br>

Country: <input type="text" disabled="disabled" value="Viet Nam"><br><br>

<input type="checkbox" value="Bike"> I have a bike<br>

<input type="checkbox" value="Car"> I have a car<br>

</form>

</body>

</html></p>

 <h1> Vận dụng 2: Tìm hiểu thêm các dạng pseuso-element khác, nêu ý nghĩa và tìm ví dụ ứng dụng thực tế cho các kiểu bộ chọn này.</h1>
 <p>Các phần tử giả:

before: thành phần phía trước

after: thành phần phía sau

marker: thành phần đánh dấu</p>
 <p><style>

h1::before {content: url(smiley.gif);}

h1::after {content: url(smiley.gif);}

::marke {color: red; font-size: 23px;}

</style></p>
<h2>Giải</h2>
<p><html>

<head>

<style>

h1::before {content: url(smiley.gif);}

h1::after {content: url(smiley.gif);}

::marker {color: red; font-size: 23px;}

</style>

</head>

<body>

<h1>This is a heading</h1>

<ul>

<li>Coffee</li>

<li>Tea</li>

<li>Milk</li>

</ul>

<ol>

<li>First</li>

<li>Second</li>

<li>Third</li>

</ol>

</body>

</html></p>





 
</body>
</html>
