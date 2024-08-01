## History of PHP

- The first version of PHP was available in early 1995.

## What is PHP?

- Programming language that used to build web applications and websites.
- PHP stands for Hypertext Preprocessor.
- PHP is a server site scripting language.
- PHP is faster than other scripting languages, such as ASP, and JSP.

## What is Scripting language?

- A programming language that is interpreted at runtime rather than compiled.
  1. Server side scripting language.
  2. Client side scripting language.

## What is server side scripting language?

- Server side scripting is used for backend processes and secure data handling, running on the server and generating content before it reaches the client.
- Which code is executes on server side.

## What is client side scripting language?

- Client side scripting is used for frontend processes and for enhancing user experience, running in the user's browser and directly interacting with the user.
- Which code is executes on client side.

## PHP Features?

- Open source: PHP is free to download and use.
- Platform independent: PHP code can run on any platform.
- Faster: PHP scripts are usually faster than other scripting languages.
- PHP automatically converts a variable's data type.
- PHP is a Dynamically types programming language.

## PHP Installation on Windows

- Download Xampp.
- Install Xampp.
- Start Apache in Xampp.
- Make a Folder and File for PHP.
- Test PHP is Installed or Not.

## ECHO in PHP?

- What is Echo in PHP?
  1. In PHP Echo is a language construct that outputs one or more strings to the screen.It is commonly used to display content, such as HTML or plain text, in a web page.
- Use of Echo?
  - **Example**
  ```php
  <?php
      echo "Hello World"
      echo 10 + 20
      echo "<h1>Hello World</h1>"
  ?>
  ```
- Case insensitive.
  - **Example**
  ```php
  <?php
      // These all are will give same output because of the Echo is Insensitive
      echo "Hello World";
      ECHO "Hello World";
      ecHo "Hello World";
  ?>
  ```
- Multiple Echo in a single line.
  - **Example**
  ```php
  <?php
      // You can write Multiple echo in a single line
      // Always remember use semicolon in the end of every Echo commmand either it will give you error
      echo "My name is Pritam"; echo "I am 21 years OLD"; echo "I am from INDIA";
  ?>
  ```
- Line break in Echo.
- **Example**
  ```php
  <?php
      // To Give a Line Break You can use '</br>' tag in same line or with a new echo command
      // 1 way
      echo "My name is Pritam </br>"; echo "I am 21 years OLD </br>"; echo "I am from INDIA";
      // 2 way
      echo "My name is Pritam"
      echo "</br>"
      echo "I am 21 years OLD";
      echo "</br>"
      echo "I am from INDIA";
      echo "</br>"
  ?>
  ```
- Interview question.
    1. Can we use Echo as a Function like **echo()**
- **Example**
  ```php
  <?php
      // If you want to use echo as a function there is no issue you can use it and the output will be same.
      // Echo as normal
      echo "Hello World"

      // Echo as function : After using Echo as a function it stills a language construct.
      echo("Hello World")
  ?>
  ```

## Variable in PHP?

- What are **variables?**
    1. The variables are storage locations.
    2. Or the variables are abstract storage location?
    3. The variable can store any kind of data.
    - **Example:** Name, Number, data from database, any type of ui like header, footer, any other component.

- Use of **variables?**
    1. The same data is used in multiple times.
    2. Display the name in multiple places on the website.
    3. Use the same number multiple times.
    4. It means which data or value you use multiple times you can store that in a variable.

- Example of **variables?**
```php
<?php
    // Task: Print My name is Peter 4 times
    echo "My name is Peter";
    echo "My name is Peter";
    echo "My name is Peter";
    echo "My name is Peter";

    // Now Change Peter to My name is Harry and remove OLD ones

    echo "My name is Harry";
    echo "My name is Harry";
    echo "My name is Harry";
    echo "My name is Harry";

    // But Using Variable we can make these repetitive programs to ease
    
    // Task: Print My name is Peter 4 times

    // Now Change Peter to My name is Harry = Now you don't need to replace the name in every line of code just change in '$name' variable

    $name = "Peter"
    $name = "Harry"

    echo "My name is " + $name
    echo "My name is " + $name
    echo "My name is " + $name
    echo "My name is " + $name

?>
```

- Why PHP **variables** are smarter than some other languages?
    - The PHP variables are smart it means the variable in PHP are dynamically typed we don't need to specify or tell the variable which type of values we are storing on it, it will automatically detect the stored variable data type.

- Variable Rules in PHP
    1. A variable should start with the '$' sign.
    2. A variable name cannot start with a number.
    3. A variable name should start with a letter or underscore ('_') character.
    4. A variable name cannot start with a special characters.
    5. A variable name can only contain alpha-numeric characters and underscores ('_')
    6. In PHP the variable names are case-sensitive like: $name, $NAME, $Name are three different variables.
    7. Variable Syntax: $name="Developer"
        - **Example:**
        ```php
        <?php
            // Wrong way variable Declaration ❌
            $@name = "Harry"
            $2name = "Harry"
            $-name = "Harry"
            $name@ = "Harry"

            // Right way variable Declaration ✅
            $name = "Peter";
            $_name = "Peter";
            $name_ = "Peter";
            $name2 = "Peter";
            $name_2 = "Peter";
            $name_2_ = "Peter";

            // And variables are case-sensitive in PHP

            $name = "Harry";
            $Name = "Peter";
            $NAME = "Tommy";

            echo $name // Harry
            echo $Name // Peter
            echo $NAME // Tommy
        ?>
        ```

- **Interview Question.**

## PHP With HTML
- What do we need to PHP and HTML?
- Write HTML inside PHP.
- Write PHP inside HTML tags.
- Add some style with PHP.

