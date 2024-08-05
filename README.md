# Portfolio

## Overview
This is a portfolio website to show some services provided by the company "Some company name". This is currently under development. We will keep adding new features in the website and the readme as we move further.

## Components

### Header
Header had logo and name of the compant, along with the navigation bar to different pages such as, Home, About, Services and Contact. Here is the code for the header:
```html
<header>
    <div class="logo-name">
        <a href="#">
            <img src="https://coderacademy.edu.au/images/footerLogo.png" alt="CA Logo">
        </a>
        <p class="name">
            <span class="coder-text">Coder</span>
            <span class="academy-text">Academy</span>
        </p>
    </div>
    <nav>
        <a href="#">Home</a>
        <a href="pages/services.html">Services</a>
        <a href="pages/about.html">About</a>
        <a href="pages/contact.html">Contact</a>
    </nav>
</header>
```


### Footer
Footer has social media links and some other informations such as contact and address. Here is the code we have for the footer:
```html
<footer>
    <div class="social-media">
        <a href="https://www.facebook.com" target="_blank"><i class="fa-brands fa-facebook"></i></a>
        <a href="https://www.linkedin.com"><i class="fa-brands fa-linkedin" target="_blank"></i></a>
        <a href="https://www.x.com"><i class="fa-brands fa-twitter" target="_blank"></i></a>
    </div>
    <div class="info">
        <p>Contact: 0400000000</p>
        <p>Address: 1 street, suburb</p>
    </div>
</footer>
```

Note: Header and Footer components have been made responsive dependant on screen size.

## Pages

### Home
Home is the starting page of the website which consists of a cover image and some detail about the company.

### Services
Services page shows different services provided by the company such as web development.