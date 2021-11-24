<html>
	<head>
		<meta charset="utf-8" />
		<title>Your first HTML form, styled</title>
		<style>
			form {
				/* Just to center the form on the page */
				margin: 0 auto;
				width: 380px;
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
				height: 5em;
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

	<body>
		<form action="https://mductor.weebly.com/ajax/apps/formSubmitAjax.php" method="post" id="form-326867494739260084" accept-charset="UTF-8" target="form-326867494739260084-target-1637753094238">
			<ul>
				<li>
					<label for="name">Name:</label>
					<input type="text" id="name" name="user_name" />
				</li>
				<li>
					<label for="mail">E-mail:</label>
					<input type="email" id="mail" name="user_mail" />
				</li>
				<li>
					<label for="msg">Message:</label>
					<textarea id="msg" name="user_message"></textarea>
				</li>
				<li class="button">
					<button type="submit">Send your message</button>
				</li>
			</ul>
		</form>
	</body>
</html> 

<form enctype="multipart/form-data" action="https://mductor.weebly.com/ajax/apps/formSubmitAjax.php" method="POST" id="form-326867494739260084" accept-charset="UTF-8" target="form-326867494739260084-target-1637753094238">
    <div id="326867494739260084-form-parent" class="wsite-form-container" style="margin-top:10px;">
      <ul class="formlist" id="326867494739260084-form-list">
        <label class="wsite-form-label wsite-form-fields-required-label"><span class="form-required"></span></label><div><div class="wsite-form-field wsite-name-field" style="margin:5px 0px 5px 0px;">
        <label class="wsite-form-label"><span class="form-required"></span><span class="wsite-instructions-help"></span></label>
        <div style="clear:both;"></div>
        <div class="wsite-form-input-container wsite-form-left wsite-form-input-first-name">
          <input aria-required="true" id="input-651828880640408381" class="wsite-form-input wsite-input" placeholder="Имя" type="text" name="_u651828880640408381[first]">
          <label class="wsite-form-sublabel" for="input-651828880640408381">Имя</label>
        </div>
        <div class="wsite-form-input-container wsite-form-right wsite-form-input-last-name">
          <input aria-required="true" id="input-651828880640408381-1" class="wsite-form-input wsite-input" placeholder="Фамилия" type="text" name="_u651828880640408381[last]">
          <label class="wsite-form-sublabel" for="input-651828880640408381-1">Фамилия</label>
        </div>
        <div id="instructions-651828880640408381" class="wsite-form-instructions" style="display:none;">[object Object]</div>
      </div>
      <div style="clear:both;"></div></div>

<div><div class="wsite-form-field" style="margin:5px 0px 5px 0px;">
        <label class="wsite-form-label" for="input-976678287136140335">Адрес электронной почты <span class="form-required"></span></label>
        <div class="wsite-form-input-container">
          <input aria-required="true" id="input-976678287136140335" class="wsite-form-input wsite-input wsite-input-width-370px" type="text" name="_u976678287136140335">
        </div>
        <div id="instructions-976678287136140335" class="wsite-form-instructions" style="display:none;"></div>
      </div></div>

<div><div class="wsite-form-field" style="margin:5px 0px 5px 0px;">
        <label class="wsite-form-label" for="input-725041284895155450">Суть запроса, кто направил? <span class="form-required"></span></label>
        <div class="wsite-form-input-container">
          <textarea aria-required="true" id="input-725041284895155450" class="wsite-form-input wsite-input wsite-input-width-370px" name="_u725041284895155450" style="height: 200px"></textarea>
        </div>
        <div id="instructions-725041284895155450" class="wsite-form-instructions" style="display:none;"></div>
      </div></div>
      </ul>
      
    </div>

    <div style="display:none; visibility:hidden;">
      <input type="hidden" name="wsite_subject">
    </div>
    <div style="text-align:left; margin-top:10px; margin-bottom:10px;">
      <input type="hidden" name="form_version" value="2">
      <input type="hidden" name="wsite_approved" id="wsite-approved" value="approved">
      <input type="hidden" name="ucfid" value="326867494739260084">
      <input type="hidden" name="recaptcha_token">
      <input type="submit" role="button" aria-label="Отправить запрос" value="Отправить запрос">
      <a class="wsite-button">
        <span class="wsite-button-inner"></span>
      </a>
    </div>

  </form>

</form>
