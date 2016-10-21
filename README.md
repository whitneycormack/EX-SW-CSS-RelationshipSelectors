#Selectors and relationships

##Setup

These commands are a helpful quick start. You may choose to ignore them completely and create your own directory structure. If you choose to use this recommendation, just copy the commands below. It doesn't matter what directory you are currently in.

```
mkdir -p ~/workspace/exercises/the-static-web/css-selectors && cd $_
touch index.html
touch selectors.css
```

###Instructions

Paste the code below into your HTML document.

The header element should have a 1px border. Color, you pick.

Convert the ul in the navigation element into a series of horizontal links with # as the href value, without bullets, and have some space between them horizontally.

Ensure that the navigation is semantically marked as such (i.e. wrap it in the correct HTML tag).

Any text in an element with class "disabled" should be colored grey, unless it is inside an anchor tag. If inside an anchor, it should be colored purple.

Any text inside an element with a class of "active" should be colored yellow.

Section elements should be contained within an article element.

There are two missing closing tags in this document. Make sure you add them back in.

Make the "I'm red" text colored red

Make the "I'm blue" text colored blue

The sibling h4 of the red element should have a background color of red

The sibling h4 of the blue element should have background color of blue

Any h4 that is a direct child of grandparent should have a 1px border with rounded corners.

Elements with a class of promo should have bold text that is also colored gold.

Without adding any other attributes to the input fields in the footer, write a CSS selector that makes any text input field have a height of 25px.


```
<header>
  <ul>
    <li>Home</li>
    <li>Profile</li>
    <li>Blog</li>
  </ul>
</header>

<section>
  <div class="month-list">
    <ul>
      <li>
        <a href="#">January</a>
        <span class="disabled">My favorite month</span>
      </li>
      <li>
        <a href="#">
          <span class="active">February</span>
        </a>
      </li>
      <li>
        <a href="#">
          <span class="disabled">March</span>
        </a>
      </li>
      <li>
        <a href="#">April</a>
      </li>
      <li>
        <a href="#">
          <div class="promo">
            <span class="disabled">May</span>
          </div>
        </a>
      </li>
      <li>
        <a href="#">June</a>
      </li>
      <li>
        <a href="#">July</a>
      </li>
      <li>
        <a href="#">August</a>
        <span class="disabled">My least favorite month</span>
      </li>
      <li>
        <a href="#" class="disabled">September</a>
      </li>
    </ul>
  </div>
</section>

<section>
  <div class="grandparent">
    <div class="parent">
      <h4>Child of parent</h4>
      <div>
        <div>I'm red!</div>
        <h4>I'm red's sister
        <div>I'm blue!</div>
        <h4>I'm blue's brother</h4>
      </div>
    </div>
    <h4>Child of grandparent</h4>
  </div>
</section>

<footer class="padded">

  <div class="disclaimer">
    Only one purchase per household. 
    <a href="#">
      <span class="footer-link">
        <span class="disabled">
          Privacy Policy
        </span>
      </span>
  </div>

  <div class="promo">
    Purchase a book today and receive the eBook for free!
  </div>

  <span>
      <input type="text" name="email" placeholder="Enter your email address">
      <input type="text" name="name" placeholder="Enter your name">
      <input type="tel" name="telephone" placeholder="Enter your telephone number">
  </span>

</footer>
```


>completed


