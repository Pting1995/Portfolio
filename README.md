# Portfolio Project Alpha

![About me](final_pictures/index.png)
![Portfolio](final_pictures/portfolio.png)
![Contact me](final_pictures/contact.png)

This site was made to showcase me! At the top of the page there is a navigation bar that allows you to switch between the About me page, the Portfolio page and the Contact me page. If you don't see it please click the button in the top right and a drop down menu will appear! All three pages will adjust to the size of the window dynamically. All of the pictures and images are placeholders but will be updated! This site was started with its navigation bar and its container, since all three htmls share them for consistency. The navigation bar was remade later to fit styling preferences. The About me page showcases text wrapping next to a picture and columns, while the Contact me page has a short survey. The portfolio page has seven images that will react to how big your screen is and will fit more pictures on it if it can. Try it! 

## Snips of code

Most of my time on this project was spent making the navigation bar perfect. In its final form it expands the text outside of the dropdown menu when the screen is big enough but if the screen isn't big enough the links will be inside of the dropdown menu. The links will always be on the right hand side of the screen!

```
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
        <!-- my name -->
        <a class="navbar-brand" href="#">Peter Ting</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
            <!-- nav buttons -->
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link" href="contact.html">Contact Me</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="portfolio.html">Portfolio</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="index.html">About me</a>
              </li>
            </ul>
        </div>
    </div>
</nav>
```

*justify-content-end was needed to shift the links to the right while outside of the dropdown menu and to shift the links to the right while inside the menu this was used in the stylesheet:*

```
navbar-nav {
    justify-content: right;
}
```

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [GitHub](https://github.com/)
* [Git](https://git-scm.com/)
* [Bootstrap](https://getbootstrap.com/)

## Deployed Link

* [See Live Site](https://pting1995.github.io/Portfolio/)

## Authors

* Peter Ting

- [Link to Github](https://github.com/Pting1995)
- [Link to LinkedIn](https://www.linkedin.com/in/pting002/)

## License

This project is licensed under the MIT License 

## Acknowledgments

* Thank you to UC Berkeley's Extension Bootcamp for giving me the opportunity to work on this project!