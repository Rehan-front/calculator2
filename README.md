<html>
<html>
<head>
	<title></title>
</head>
<body>
	<style type="text/css">
		@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap');

         /*normal codes*/
        html,body
        {
        	scroll-behavior: smooth;
        }
        *
        {
            margin: 0;
            padding: 0;
            font-family: 'poppins';
            box-sizing: border-box;
        }
        body
        {
        	background: #091921;
        	display: flex;
        	justify-content: center;
        	align-items: center;
        	min-height: 100vh;
        }
        .container
        {
        	position: relative;
        	background: rgba(0,0,0,0.2);
        	display: grid;
        }
        .anss
        {
        	grid-column: 4;
        	height: 80px;
        	font-size: 30px;
        	text-align: right;
        	outline: none;
        }
        input[type="button"]
        {
        	word-spacing: 15px;
        	text-align: center;
        	border: 1px solid transparent;
        	padding: 2px;
        	outline: none;
        	margin-left: 18px;
        }
	</style>
   <div class="container">
   	<form name="forms">
   	<input type="text" name="answer" class="anss"> <br>

   	<input type="button" value=" 1 " onclick="forms.answer.value += '1' ">
   	<input type="button" value=" 2 " onclick="forms.answer.value += '2' ">
   	<input type="button" value=" 3 " onclick="forms.answer.value += '3' ">
    <br>
    <br>
   	<input type="button" value=" 4 " onclick="forms.answer.value += '4' ">
   	<input type="button" value=" 5 " onclick="forms.answer.value += '5' ">
   	<input type="button" value=" 6 " onclick="forms.answer.value += '6' ">
<br>
    <br>
   	<input type="button" value=" 7 " onclick="forms.answer.value += '7' ">
   	<input type="button" value=" 8 " onclick="forms.answer.value += '8' ">
   	<input type="button" value=" 9 " onclick="forms.answer.value += '9' ">
    <br>
    <br>
   	<input type="button" value=" + " onclick="forms.answer.value += '+' ">
   	<input type="button" value=" - " onclick="forms.answer.value += '-' ">
   	<input type="button" value=" * " onclick="forms.answer.value += '*' ">
    <br>
    <br>

   	<input type="button" value=" / " onclick="forms.answer.value += '/' ">
   	<input type="button" value=" 0 " onclick="forms.answer.value += '0' ">
   	<input type="button" value=" = " onclick="forms.answer.value = eval(forms.answer.value)">
   	<br>
    <br>
    <input type="button" value="Clear all" onclick="forms.answer.value = '' " id="c-a">
   	</form>
   </div>
</body>
</html>
