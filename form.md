###### osb-zapros


<html>
	<head>
		<meta charset="utf-8" />
		<title>HTML form, styled</title>
		<style>
			form {
				/* Just to center the form on the page */
				margin: 0 auto;
				width: 335px;
				/* To see the outline of the form */
				padding: 1em;
				border: 1px solid #ccc;
				border-radius: 1em;
			}

			ul {
				list-style: none;
				padding: 0;
				margin: 0;
			}

			form li + li {
				margin-top: 1em;
			}

			label {
				/* To make sure that all labels have the same size and are properly aligned */
				display: inline-block;
				width: 90px;
				text-align: right;
			}

			input,
			textarea {
				/* To make sure that all text fields have the same font settings By default, textareas have a monospace font */
				font: 1em sans-serif;
				/* To give the same size to all text fields */
				width: 300px;
				box-sizing: border-box; /* To harmonize the look & feel of text field border */
				border: 1px solid #999;
			}

			input:focus,
			textarea:focus {
				/* To give a little highlight on active elements */
				border-color: #000;
			}

			textarea {
				/* To properly align multiline text fields with their labels */
				vertical-align: top;
				/* To give enough room to type some text */
				height: 18em;
			}

			.button {
				/* To position the buttons to the same position of the text fields */
				padding-left: 90px;
				/* same size as the label elements */
			}

			button {
				/* This extra margin represent roughly the same space as the space between the labels and their text fields */
				margin-left: 0.5em;
			}
		</style>
	</head> 

<form method="post"   action="https://formspree.io/f/mnqwalae">
    <input type="hidden" name="_next" value="/thanks.html" />
    <input type="hidden" name="_subject" value="ОСБ / Запрос" />
    <input type="text" name="_gotcha" style="display:none" />        
    <p><input type="text" name="ФИО" required placeholder="ФИО (полностью)" /></p>
    <p><input type="email" name="email" required placeholder="Email" /></p>
    <p><textarea name="1) Кто Вас направил? 2) Суть Запроса?" required placeholder="1) Кто Вас направил? 2) Суть Запроса?" rows="16"></textarea></p>
    <input type="submit" value="Отправить" />
</form>



  
