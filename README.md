
<html>
	<head>
		<title> Đây là trang web cùi </title>
	</head>
	<body>
	<div id="header">
		<h1> Tiêu đề web </h1>
		<p>Mô tả web</p>
	</div>
	<div id="content">
		<p> Phần nội dung viết ở đây </p>
	</div>
		<h1 style='background-color: yellow; color: red;'>Test Tiêu đề 1</h1>
		<p style='text-align:center';> Tác giả: Hehe </p>
		<h2 style='background-color: gray; color: green; text-align: center;'>Test Tiêu đề 2</h2>
		
		
		<p> 
			Thẻ p giúp trình duyệt nhận dạng được đoạn văn bản trong HTML
		</p>
		
		<p> 
			Thẻ hr được dùng để tạo đường kẻ ngang 
		</p>
		
		<hr/>
		<pre> 
			Thẻ pre 
			Có công dụng
			xuống dòng
		</pre>
		
		<span>
			Thẻ span được dùng để nhóm các phần tử nội tuyến lại với nhau, tiện cho việc định dạng CSS
		</span>
		
		<br>
		<span>
			Thẻ br được dùng để  <br>
			xuống dòng 
		</span>
		
		<hr/>
		<pre style='text-align:right;color:red;'>
			Code dễ vãi lol
			Sao mà làm khó được tôi
			Mai tôi làm chủ tịch
		</pre>
		<hr/>
		<h2 style='background-color: gray; color: green; text-align: center;'>Danh sách có Thứ tự ol </h2>
		<ol>
			<li> apple 
			<li> chuối
			<li> Táo
		</ol>
		<ol type= "i">
			<li> apple 
			<li> chuối
			<li> Táo
		</ol>
			<ol type= "a">
			<li> apple 
			<li> chuối
			<li> Táo
		</ol>
		</ol>
			<ol type= "a">
			<li type="a"> apple
				<ol>
				<li> loại 1
				<li> Loại 2
				<li> Loại 3
				</ol>
			<li type="A"> chuối
			<li type="I"> Táo
			<li type="i"> Xoài
		</ol>
		<h2 style='background-color: gray; color: green; text-align: center;'>Danh sách khum có Thứ tự ul </h2>
		<ul type="disc">
			<li> apple 
			<li> chuối
			<li> Táo
		</ul>
		
		<ul type="circle">
			<li> apple 
			<li> chuối
			<li> Táo
		</ul>
		
		<ul type="square">
			<li> apple 
			<li> chuối
			<li> Táo
		</ul>
		
	<h1 style='background-color: yellow; color: red;'>Liên kết</h1>
	<h2 style='background-color: gray; color: green; text-align: center;'>Liên kết ngoại </h2>
	<a href="URL"> aaa </a>
	
	<h2 style='background-color: gray; color: green; text-align: center;'>Liên kết nội </h2>
	<a name="Tenvitri"> Vitribatdau </a>
	<a href="#Tenvitri"> Textdaidien </a>
	
	<h2 style='background-color: gray; color: green; text-align: center;'>Liên kết email </h2>
	Gmail: <a href="mailto:hoangphuchvcx02@gmail.com"> hoangphuchvcx02@gmail.com </a>
	
	<h2 style='background-color: gray; color: green; text-align: center;'>Liên kết URL </h2>
	<a href="https://www.facebook.com/" target= 'https://www.facebook.com/' > Mở Facebook </a>
	
	
	<h1 style='background-color: yellow; color: red;'>Tạo bảng</h1>
	<a href="https://drive.google.com/file/d/1XbX0TN8QE2io1fH25d_R9IZU5xQ2CGAv/view" target= 'https://drive.google.com/file/d/1XbX0TN8QE2io1fH25d_R9IZU5xQ2CGAv/view' > Ảnh Bảng </a>
	<img src="https://drive.google.com/file/d/1XbX0TN8QE2io1fH25d_R9IZU5xQ2CGAv/view" alt="Mô tả hình ảnh">

	

	<table border="1">
		<tr>
			<th>Name </th>
			<th>Telephone </th>
			<th>Country </th>
			<th>Center </th>
		</tr>
		<tr>
			<td rowspan="2"> Bill </td>
			<td>50522155  </td>
			<td colspan="2" rowspan="3"> silicon valley -usa </td>
		</tr>
		<tr>
			<td>10055 555 888 </td>
		</tr>
			<td> Job </td>
			<td> 1 888 535 874 </td>
		</tr>
	</table>
	
	<h2 style='background-color: gray; color: green; text-align: center;'> Thuộc tính background </h2>
	<table border="1" style="background-image: url('https://www.searchenginejournal.com/wp-content/uploads/2022/06/image-search-1600-x-840-px-62c6dc4ff1eee-sej-760x400.webp');">
		<tr>
			<th>Name </th>
			<th>Telephone </th>
			<th>Country </th>
			<th>Center </th>
		</tr>
		<tr>
			<td rowspan="2"> Bill </td>
			<td>50522155  </td>
			<td colspan="2" rowspan="3"> silicon valley -usa </td>
		</tr>
		<tr>
			<td>10055 555 888 </td>
		</tr>
			<td> Job </td>
			<td> 1 888 535 874 </td>
		</tr>
	</table>

	<h2 style='background-color: gray; color: green; text-align: center;'> Thuộc tính bgcolor </h2>
	<table border="1" bgcolor="#0099FF">
		<tr bgcolor="FF6699">
			<th>Name </th>
			<th>Telephone </th>
			<th bgcolor="33FF99">Country </th>
			<th>Center </th>
		</tr>
		<tr>
			<td rowspan="2"> Bill </td>
			<td>50522155  </td>
			<td colspan="2" rowspan="3"> silicon valley -usa </td>
		</tr>
		<tr>
			<td>10055 555 888 </td>
		</tr>
			<td> Job </td>
			<td> 1 888 535 874 </td>
		</tr>	
	</table>
	
	<h2 style='background-color: gray; color: green; text-align: center;'> Thuộc tính cellspacing, cellpadding </h2>
	<table border="1" cellspacing="15" cellpadding="15">
		<tr bgcolor="FF6699">
			<th>Name </th>
			<th>Telephone </th>
			<th bgcolor="33FF99">Country </th>
			<th>Center </th>
		</tr>
		<tr>
			<td rowspan="2"> Bill </td>
			<td>50522155  </td>
			<td colspan="2" rowspan="3"> silicon valley -usa </td>
		</tr>
		<tr>
			<td>10055 555 888 </td>
		</tr>
			<td> Job </td>
			<td> 1 888 535 874 </td>
		</tr>	
	</table>
	
	<h1 style='background-color: yellow; color: red;'>Thẻ div</h1>
	<div style="color:#0000FF">
		<p> This is some text to test this code </p>
		<ol>
			<li> apple 
			<li> chuối
			<li> Táo
		</ol>
	</div>
	
	<div id="content">
		<p> Phần nội dung viết ở đây </p>
	</div>
	<div id="sidebar">
		<p> Đây là sidebar  </p>
	</div>
	<div id="footer">
		<p> Copyright 2015 hehe.vn </p>
	</div>
	
	</body>
</html>
	
