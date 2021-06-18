# refractoring-fun
This Homework 1 repository is for refractoring existing code for a marketing agency called Horiseon. The goal was to make the website more accessible in order for the website to be optimized in search engines. The original code was cleaned up to ensure use of logical structure, semantic HTML elements, and accessible alt attributes for images.

## Technologies Used
This website was written in HTML/CSS on Visual Studio, using Terminal to access the Github repo with git.

## Essential Code
<div> tags were swapped with more specific semantic HTML elements such as <header> and <section> to name a few.

```html
<div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
```
turned into

```html
<header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
```
Image tags were also given accessible alt attributes.

```html
<div id="search-engine-optimization" class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="notebook with search engine optimization components">
            <h2>Search Engine Optimization</h2>
```

## Application Functioning

The final website can be found here: [Horiseon Marketing Agency](https://samyuhan.github.io/refractoring-fun/)