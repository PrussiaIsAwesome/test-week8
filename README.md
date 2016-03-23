# test-week8

What do jQuery selectors start with?

$

What's the problem with this code
in your html:
<div class="my-element">Hide me</div>
in your javascript:
$(".another-element").hide();

needs to be the same name or $(".my-element").hide();

What's wrong with this code:
in your html:
<div class="my-element">Hide me</div>
in your javascript:
$("#hideMe").hide();

the code is not an id so it has to be $(".hideMe").hide();

If you have a FOLDER named lib and a FILE named app.js, why won't this link to your javascript work?
<script src="app.js"></script>

need to link to the file ex. <script src="lib/app.js"><script>

What can you tell me about this: <input type="text"/> what is it? what will we be using them for?

to put a place for the user to type info
