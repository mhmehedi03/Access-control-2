# Access-control-2
User role controlled by request parameter
if the access-control (ac) bug is not in the url and js code,then should find in the request parameter
process----->>
1. go to login section and login 
2. capture the req by burpsuit with the id parameter
3. where Admin = false change to true.
4. then load the code (request in browser)
5. in web page inspect it,
6. go to cookies,and chnage the Admin value false to true.
7. reload the web page admin panel should be shown.
   
