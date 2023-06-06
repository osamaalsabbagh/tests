## PHP

#### Q1. What does this script do?

```php
$email = filter_input(INPUT_POST, 'email', FILTER_VALIDATE_EMAIL);
if ($email === false) {
    $emailErr = "Please re-enter valid email";
}
```

**A)** It makes sure the email address is a good and functioning address  
**B)** It makes an email safe to input into a database  
**C)** It assigns an email to a variable and then removes all illegal characters from the \$email variable  
**D)** It verifies that an email address is well formed.  

<br>

#### Q2. In the following script, which line(s) will cause an error(s)?

```php
1 <?php
2       $count = 0;
3       $_xval = 5;
4       $_yval = 1.0;
5       $some_string = "Hello there!";
6       $some_string = "How are you?";
7       $will i work = 6;
8       $3blindmice = 3;
9 ?>
```

**A)** Line 6 will cause an error because you can't reassign a new value to a variable that has already been set.  
**B)** Line 7 and 8 will cause an error. Line 7 has whitespace in $will i work and should be $will_i_work. Line 8 cannot start with a number befcause it is a variable.  
**C)** Line 5 will cause an error because some_string should be someString.  
**D)** Line 3 and 4 will cause an error because a variable cannot start with an underscore(\_).  


<br>

#### Q3. All variables in PHP start with which symbol?

**A)** &  
**B)** %  
**C)** \_  
**D)** $  

<br>

#### Q4. What is a key difference between GET and POST?

**A)** GET is used with the HTTP protocol. POST is used with HTTPS.  
**B)** GET displays the submitted data as part of the URL. During POST, this information is not shown, as it's encoded in the request body.  
**C)** GET is intended for changing the server state and it carries more data than POST.  
**D)** GET is more secure than POST and should be used for sensitive information.  

<br>

#### Q5. The **operator is useful for sorting operations. It compares two values and returns an integer less than, equal to, or greater than 0 depending on whether the value on the** is less than, equal to, or greater than the other

**A)** greater-than; right  
**B)** spaceship; left  
**C)** equality; right  
**D)** comparison; left  

<br>

#### Q6. Which value equates to true?

**A)** 0  
**B)** NULL  
**C)** ''  
**D)** -1  

<br>

#### Q7. What is missing from this code, which is supposed to create a test cookies?

```php
1 $string_name = "testcookie";
2 $string_value = "This is a test cookie";
3 $expiry_info = info()+259200;
4 $string_domain = "localhost.localdomain";
```

**A)** The `$_REQUEST` is missing.  
**B)** The `$_COOKIES` array is missing.  
**C)** The cookie session is missing.  
**D)** The call to `setcookie()` is missing.  

<br>

#### Q8. What is the value of \$total in this calculation?

`$total = 2 + 5 * 20 - 6 / 3`

**A)** 44  
**B)** 138  
**C)** 126  
**D)** 100  

<br>

#### Q9. What is the purpose of adding a lowercase "u" as a modifier after the final delimiter in a Perl-compatible regular expression?

**A)** It makes the dot metacharacter match anything, including newline characters.  
**B)** It makes the pattern match uppercase letters.  
**C)** Both the pattern and subject string are treated as UTF-8.  
**D)** It inverts the greediness of the quantifiers in the pattern so they are not greedy by default.  

<br>

#### Q10. Which code snippet uses the correct syntax for creating an instance of the Pet class?

**A)** `$dog = new Pet;`  
**B)** all of these answers  
**C)** `$horse = (new Pet);`  
**D)** `$cat = new Pet();`  

<br>

#### Q11. What is the best way to explain what this script does?

```php
1 if (!$_SESSION['myusername'])
2 {
3   header('locaton: /login.php');
4   exit;
5 }
```

**A)** This script times out the session for myusername.  
**B)** Cookies are starting to be stored as a result of this script.  
**C)** This script validates the username and password.  
**D)** This script is on a page that requires the user to be logged in. It checks to see if the user has a valid session.  

<br>

#### Q12. Which is the correct format for adding a comment to a PHP script?

**A)** all of these answers  
**B)** #This is a comment  
**C)** `/* This is a comment */`  
**D)** // This is a comment  

<br>

#### Q13. PHP supports multiple types of loops. If you wanted to loop through a block of code if and as long a specified condition is true, which type of loop would you use?

**A)** for  
**B)** do-while  
**C)** while  
**D)** foreach  

<br>

#### Q14. The `ignore_user_abort( )` function sets whether a client disconnect should abort a script execution. In what scenario would you, as a web developer, use this function?

**A)** You would use it to stop a user from clicking the back button if they decide not to view as a result of a click.  
**B)** You would use this function if you have some important processing to do and you do not want to stop it, even if your users click Cancel.  
**C)** You would use this function if you wanted to abort the script for all logged-in users, not just the one who disconnected.  
**D)** You would use this function if you want a PHP script to run forever.  

<br>

#### Q15. The PHP function array_reduce() takes a callback function that accepts a value carried over each iteration and the current item in the array, and reduces an array to a single value. Which code sample will sum and output the values in the provided array?

**A)**

```php
  1 <?php
  2 echo array_reduce([1, 2, 5, 10, 11], function ($item, $carry) {
  3     $carry = $carry + $item;
  4 });
  5?>
```

**B)**

```php
  1 <?php
  2 echo array_reduce([1, 2, 5, 10, 11], function ($carry, $item) {
  3     return $carry = $item + $item;
  4 });
  5?>
```

**C)**

```php
  1 <?php
  2 array_reduce([11 2, 5, 10, 11], function ($item, $carry) {
  3     echo $carry + $item;
  4 });
  5?>
```

**D)**

```php
  1 <?php
  2 echo array_reduce([1, 2, 5, 10, 11], function ($carry, $item) {
  3     return $carry += $item;
  4 });
  5?>
```
