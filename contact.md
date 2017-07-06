---
layout: page
title: Contact
description: 
---
<section>
	<!--<form method="post" action="#">
		<div class="row uniform">
			<div class="6u 12u$(xsmall)">
				<input type="text" name="demo-name" id="demo-name" value="" placeholder="Name" />
			</div>
			<div class="6u$ 12u$(xsmall)">
				<input type="email" name="demo-email" id="demo-email" value="" placeholder="Email" />
			</div>
			<div class="12u$">
				<div class="select-wrapper">
					<select name="demo-category" id="demo-category">
						<option value="">- Category -</option>
						<option value="1">Inquiry</option>
						<option value="1">Training</option>
						<option value="1">Employment</option>
					</select>
				</div>
			</div>
			<div class="12u$">
				<textarea name="demo-message" id="demo-message" placeholder="Enter your message" rows="6"></textarea>
			</div>
			<div class="12u$">
				<ul class="actions">
					<li><input type="submit" value="Send Message" class="special" /></li>
					<li><input type="reset" value="Reset" /></li>
				</ul>
			</div>
		</div>
	</form>-->
	<form action="https://formspree.io/{{ site.email }}" method="POST">
				<div class="field half first">
					<label for="name">Name</label>
					<input type="text" name="name" id="name" />
				</div>
				<div class="field half">
					<label for="email">Email</label>
					<input type="text" name="_replyto" id="email" />
				</div>
				<div class="field">
					<label for="message">Message</label>
					<textarea name="message" id="message" rows="6"></textarea>
				</div>
				<br>
				<ul class="actions">
					<li><input type="submit" value="Send Message" class="special" /></li>
					<li><input type="reset" value="Clear" /></li>
				</ul>
			</form>
</section>
