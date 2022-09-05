# web-vulnerabilites
Creating basic vulnerable pages and patching the vulnerabilities.

In the vulnerable-pages folder, hello.php page has a basic text input that prints out to the page. It is vulnerable to XSS attacks. And in patched-pages folder XSS attacks prevented by using htmlentitites function.

And login.php has a basic login panel that is vulnerable to SQL injections. It is prevented by using prepared statements (PDO) in the patched-pages folder.

And comments.php has a basic text input and inserting function that is vulnerable to XSS attacks. It is prevented by using htmlentities function when inserting comments to the database. It is tested by using XSS-payloads.
