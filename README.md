# Blade_Template
<h1>Blade Templating in Laravel</h1>
Laravel's Blade is a templating engine that allows developers to create dynamic HTML pages using PHP code in a readable and efficient manner. Blade offers features like template inheritance, reusable components, and automatic escaping to prevent XSS attacks3. Blade files use the .blade.php extension and are stored in the resources/views directory.
Blade Syntax
Blade simplifies embedding PHP code within HTML. To display a variable, {{ $variable }} can be used. Blade automatically handles HTML entity escaping. If an unescaped data needs to be displayed, we can use {{!! $variable !!}}:
<!DOCTYPE html>
<html>
<head>
    <title>{{ $title }}</title>
</head>
<body>
    <h1>Welcome {{ $name }}!</h1>
</body>
</html>
--> In this example, title and name are variables passed to the view <---

References:
Cornea, I. (2025, February 10). Laravel Blade Template Engine: A Beginner’s Guide. DEV Community. https://dev.to/icornea/laravel-blade-template-engine-a-beginners-guide-54bi
