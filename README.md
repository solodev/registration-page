# registration-page
Registration pages are the "make it or break it" web page of your website. This is where a user will decide whether or not to register for your product or service with all of the knowledge they have gained up to this point.

## Tutorial

For detailed instructions, view Solodev's [Building an Effective Registration Page](https://www.solodev.com/blog/web-design/building-an-effective-registration-page.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/tmpxaqon/).

## HTML

The registration page features the following basic HTML markup.
```
<div id="highlighted" class="hl-basic hidden-xs">
   <div class="container-fluid">
      <div class="row">
         <div class="col-sm-9 col-sm-offset-3 col-md-9 col-md-offset-3 col-lg-10 col-lg-offset-2">
            <h1>Register</h1>
         </div>
      </div>
   </div>
</div>
<div id="content" class="interior-page">
<div class="container-fluid">
<div class="row">
   
<!--Sidebar-->
<div class="col-sm-3 col-md-3 col-lg-2 sidebar equal-height interior-page-nav hidden-xs">
   <div class="dynamicDiv panel-group" id="dd.0.1.0">
      <div id="subMenu" class="panel panel-default">
         <ul class="subMenuHighlight panel-heading">
            <li class="subMenuHighlight panel-title" id="subMenuHighlight">
               <a class="subMenuHighlight" href=""><span class="subMenuHighlight">Register</span></a>
            </li>
         </ul>
         <ul class="panel-heading">
            <li class="panel-title">
               <a class="subMenu1" href=""><span>Forgot Password</span></a>
            </li>
         </ul>
         <ul class="panel-heading">
            <li class="panel-title">
               <a class="subMenu1" href=""><span>Login</span></a>
            </li>
         </ul>
      </div>
      <div class="item item-nopad item-noborder item-gold">
         <a href="" class="btn btn-primary btn-block" role="button">LEARN MORE</a> 
      </div>
</div>
</div>

<!--Content-->
<div class="col-sm-9 col-md-9 col-lg-10 content equal-height">
<div class="content-area-right">

<div class="content-crumb-div">
   <a href="">Home</a> | <a href="">Your Account</a> | Create An Account
</div>
   <form id="registration_form" name="contentForm" enctype="multipart/form-data">
      <p>Thank you for joining us. Please register by completing the information below.</p>
      <div class="row">
         <div class="col-md-4">
            <label class="label-default" for="Fname">First Name</label> <input class="form-control required" id="Fname" name="Fname" type="text" required>
         </div>
         <div class="col-md-4">
            <label class="label-default" for="Lname">Last Name</label> <input class="form-control required" name="Lname" type="text" required>
         </div>
      </div>
      <div class="row">
         <div class="col-md-4">
            <label class="label-default" for="email">Email</label> <input class="form-control validate[required,custom[email]]" id="email" name="email_add" type="email" value="" required>
         </div>
         <div class="col-md-4">
            <label class="label-default" for="mobile">Mobile</label>&nbsp;(e.g. 555-555-5555) <input class="form-control validate[required,custom[mobile]]" id="mobile" name="mobile_add" type="tel" value="" required pattern="^\d{3}-\d{3}-\d{4}$">
         </div>
      </div>
      <div class="row">
         <div class="col-md-4">
            <label class="label-default" for="pass_word">Password</label> <input class="form-control required" id="pass_word" name="pass_word" type="password" required>
         </div>
         <div class="col-md-4">
            <label class="label-default" for="pass_word_confirm">Confirm Password</label> <input class="form-control required" id="pass_word_confirm" name="pass_word_confirm" type="password" required> &nbsp; <span class="confirmation">&nbsp;</span>
         </div>
      </div> 
      <div class="row">
         <div class="col-md-8">
             <input id="reg_login" class="btn btn-primary" type="submit" value="REGISTER">
         </div>
      </div>
   </form>
</div>
</div>
```
## CSS

All necessary CSS is in registration.css

## External Includes

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="registration.css">

<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
