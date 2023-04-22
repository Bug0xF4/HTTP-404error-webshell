# HTTP 404 Webshell:
PHP-Based webshell/backdoor disguised as a HTTP 404 error page.

In order to use this shell, you need to add the string `L3tM3iN` (case-sensitive) into your user-agent header (you don't need to replace the entire user agent, you can just add this string anywhere within it). If you load up the webshell with a valid user-agent, then a hidden input form will get loaded underneath the HTTP 404 error message, you can then click on this hidden input form to input the commands you wish to execute.
