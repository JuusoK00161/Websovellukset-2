<div class="responsive-container">
<div class0="column">Column 1</div>
<div class="column">Column 2</div>
</div>

CSS:
<style>
.responsive-container {
    display: flex;
    flex-wrap: wrap;

}

.column {
    flex: 1;
    padding: 10px;
}

@media (max-width: 600px) {
    .column {
        flex: 100%;
    }
}

<img src="path/to/image.jpg" alt="Responsive Image" class="responsive-image">

.responsive-image {
    max-width: 100%;
    height: auto;
}

<div class="media-query-box {
    padding: 20px;
    text-align: center;
}

@media (max-width: 600px) {
    .media-query-box {
        backround-color: lightblue;
    }
}

<nav class="responsive-nav">
<button class="menu-toggle">☰Menu</button>
<ul class="nav-list">
<li><a href="#">Home</a></li>
<li><a href="#">About</a></li>
<li><a href="#">Contact</a></li>
</ul>
</nav>

CSS:
<style>

.responsive-nav .nav-list {
    display: flex;
    list-style: none;
}

@media (max-width 600pc) {
    .responsive-nav .nav-list{
        display: none;
    }
}

.responsive-nav .menu-toggle {
    display: block;
}


