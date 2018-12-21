---
title: "Contact us"
date: 2018-07-09T13:13:41-05:00
draft: false
layout: single
---

---- 

<form name="contact" method="POST" data-netlify="true">
  <p>
	<table>
		<tr>
			<td>Email:</td><td><input type="text" name="email" style="width: 90%"/></td>
		</tr>
		<tr>
			<td>Message:</td><td><textarea name="message" rows=25 style="width: 90%"/></textarea>
		</tr>
	</table>
  </p>
  <div data-netlify-recaptcha="true"></div>
  <p>
    <button type=”submit”>Send</button>
  </p>
</form>
