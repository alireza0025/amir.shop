# amir.shop
my shop
<!DOCTYPE html>
<html lang="fa"> 
	<head>

		<link rel="stylesheet" type="text/css" href="style.css">
		<meta name="viewport" content="width:device-width, initial-scale=1.0">
		<TITLE>لوازم ساختمانی بهداشتی امیر</TITLE>
	</head>
	<body style="text-align:center;background-image:url('back.jpg')">
		<h1 class='x1' > لوازم ساختمانی بهداشتی امیر </h1>
		<button type="button" onclick="alert('سمنان بلوار ورزش')"> ! برای مشاهده آدرس اینجا  کلیک کن</button><br>
		<nav>
			<ul style="list-style-type:none;">
				<li><a href=#t2> شیرآلات</a></li>
				<li><a href=#t1> کولر </a></li>
				<li><a href=#t3> ارتباط با ما </a></li>
				<li><a href=#php> انتقادات و پیشنهادات</a></li>
			</ul>
			<br>
		</nav>
		<picture>
			<img src="hik.jpg" style= "max-width:100%;height:auto;">
		</picture>
		<hr>
		<div style="text-align:center"><br>
		<button onclick="playpause()"> play/stop </button><br>
		<video width="320" height="240" controls><br>
		<source src="patrick.mp4" type="video/mp4"><br>
		</video>
		</div><br>
		<h3 color="red"> بیخودی اهنگ گزاشتم</h3>
		<audio controls>
		<source src="lma.mp3">
		</audio>
			<h2 style="border: 2px solid tomato;" id="t2">شیر آلات </h2>
			<table style="width:100%;background-color:yellow;" >
				<colgroup>
					<col span="2" style=background-color:#20B2AA>
					<col span="2" style=background-color:#E6E6FA>
						<caption>لیست نام و قیمت شیر آلات </caption>
						<tr>
							<th> نام محصول</th>
							<th>قیمت</th>
							<th>نام محصول</th>
							<th>قیمت</th>
						</tr>
						<tr>
							<td>شیر ظرفشویی</td>
							<td>385000</td>
							<td>شیر روشویی</td>
							<td>385000</td>
						</tr>
						<tr>
							<td>شیر دستشویی</td>
							<td>385000</td>
							<td>شیر حمام</td>
							<td>410000</td>
						</tr>
			</table>
			<form>
			     <fieldset>
			                <legend> ثبت سفارش</legend>
			             <input list="shir">
			         <datalist id="shir">
			<option value="شیر روشویی">
			<option value="شیر ظرفشویی">
			<option value="شیر دستشویی">
			<option value=" شیر حمام">
			<br>
			</fieldset>
			<label for="fname"> نوع سفارش</label>
			 <input type="text" id="fname" name="fname" value="شیرآلات" disabled><br>
			 <label for="quantity">تعداد سفارش (بین 1 تا 5  ):</label>
                 <input type="range" id="quantity" name="quantity" min="1" max="5"><br>
				 <label for="phone" >: شماره تلفن خود را وارد کنید  </label><br> 
				 <input type="tel" id="phone" pattern="[0-9]{11}" required><br>
			<input type="submit" value="submit" >
			
			
			</form>
			<hr>
				<h2 style="border: 2px solid blue;" id="t1">لیست قیمت ابزار کولر </h2>
				<br>
					<iframe src="https://www.digikala.com/search/category-iranian-cooler/" name="digi" height="500" width="700"></iframe>
				<br>
					<p><a href="https://www.digikala.com/product/dkp-585870/%D9%BE%D9%85%D9%BE-%DA%A9%D9%88%D9%84%D8%B1-%D8%A2%D8%A8%DB%8C-%D9%85%D9%88%D8%AA%D9%88%DA%98%D9%86-%D9%85%D8%AF%D9%84-p" target="digi"> قیمت پمپ کولر</a></p>
				<br>
				<figure>
					<img src="pic.jpg"  style="max-width:100%;height:auto;"> 
					<figcaption> نمای داخلی کولر آبی</figcaption>
				</figure>
				<h2 id="php"> انتقادات و پیشنهادات</h2>
				<form target="_blank"  method="get" autocomplete="on" >
				<fieldset>
				<legend>نظرات</legend>
				          <label for="nba">اینجا بنویسید</label>
				          <textarea name="message" rows="10" cols="30" style="background-color:yellow;">از نظر من ....</textarea>
						  <input type="submit" value="submit" >
						  <input type="reset">
				</form>
				<br>
				<p>نظر شما درباره عملکرد ما</p>
				<form>
				<input type="radio" id="cp">
				<label for="cp"> خوب</label>
				<input type="radio" id="co">
				<label for="co"> عالی</label>
				<input type="radio" id="ci">
				<label for="ci"> بی نقص </label>
				<input type="submit" value="submit" >
				</fieldset>
				</form>
				
					<address style="background-color:rgb(100,200,150); font-size:150%" id="t3">
						ارتباط با ما :
						<br>
						<a href="https://goo.gl/maps/TneUTN11RFYjSUdM8" target="-parent"> 
							<img src="fa.jpg" alt="مکان ما روی نقشه" style= "max-width:100%;height:auto;">
						</a>
						<br>
							tell:02333454324
						<br>
						<a href="tabrizianalireza@example.com"> پست الکترونیک</a>
					</address>
					<footer>
					<p> طراحی شده توسط علیرضا تبریزیان <br>
					ارتباط با ما: tabrizianalireza@gmail.com</p><br>
					<a href="https://wa/me/989922826151">
					<svg>
                            <ellipse cx="100" cy="70" rx="200" ry="55" fill="#008B8B"/>
						    <text fill="#ffffff" font-size="45" font-family="Verdana" x="50" y="86">watsapp</text>
						  </svg> 
						  </a>
					</footer>
	</body>
</html>
