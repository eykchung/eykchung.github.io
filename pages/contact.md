---
layout: default
title: Contact
id: contact
---
<!--HTML FORM TO EMAIL: https://www.quackit.com/html/codes/html_form_to_email.cfm -->

<div id="contact">
<form method="post" >
<fieldset>
<legend>Thank you for taking a look at my portfolio.  Have anything to say?  please put it down in the form below!</legend>
<div class="form-group row">
<label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
<div class="col-sm-10">
<input type="text" readonly="" class="form-control-plaintext" id="staticEmail" value="eykdes@gmail.com">
</div>
</div>
<div class="name">
<label for="InputName">Name </label>
<input type="text" name="first_name" required class="form-control" id="InputName" aria-describedby="aria-label" placeholder="Enter first name">
</div>
<div class="form-group">
<label for="exampleInputEmail1">Email address </label>
<input type="email" name="email_address" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
<small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
</div>
<div class="form-group">
<label for="exampleTextarea">Any comments? </label>
<textarea class="form-control" name="comments" id="exampleTextarea" rows="3"></textarea>
</div>
<button type="submit" class="btn btn-primary">Submit</button>
</fieldset>
</form>
</div>
