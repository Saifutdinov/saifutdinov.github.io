<!DOCTYPE html>
<html lang="{{ page.lang | default: site.default_lang }}">
<head>
    <meta charset="UTF-8">
    <title>{{ page.title }}</title>
    <link rel="stylesheet" href="/assets/styles.css">
</head>
<body>
    <nav>
        <a href="/en/">English</a> | 
        <a href="/ru/">Русский</a> | 
        <a href="/fr/">Français</a>
    </nav>
    <main>
        {{ content }}
    </main>
</body>
</html>
