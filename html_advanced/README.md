# HTML Advanced
In this project we were to create the semantic layout of a web static project. We had a wireframe mockup that we followed. No CSS styling was added yet. Below are the wireframes for the project that were followed, and the resulting code. 

The wireframe was created in Figma, and can be accessed here. 
[Figma Wireframe](https://www.figma.com/file/XrEAsu1vQj5fhVaNG38d2W/Homepage?type=design&node-id=0-1&mode=design&t=r2vCvbwwmBs9XkWP-0)


## Objectives
- Implement the HTML structure based on the provided wireframes and designer file.
- Create a well-structured HTML document with semantic elements.
- Implement the HTML structure based on the provided wireframes and designer file.
- Create a well-structured HTML document with semantic elements.
- No CSS styles were applied eventhough placeholder classes were included
  

### Header
![header](https://github.com/manningstinson/atlas-web-development/assets/104523090/ff305a6a-d989-4f02-a21c-4445f71aefda)

```html
<header>
  <a href="index.html">
    Advanced HTML<img src="img/logo.png" alt="logo-image" />
  </a>

  <div class="navlinks">
    <a href="login.html">Home</a>
    <a href="pricing.html">About</a>
    <a href="courses.html">Services</a>
  </div>
</header>
```

### Banner
![banner](https://github.com/manningstinson/atlas-web-development/assets/104523090/3bca0e99-c117-491d-a75a-cf7bab16c057)

```html
<section>
  <div>
    <h1>Get schooled</h1>
    <p>Smiles</p>
    <p>Grin</p>
    <p>Laugh</p>
    <button>REGISTER FOR FREE</button>
  </div>

  <div>
    <h2>Learn from the pros</h2>
    <!-- Four blocks with images, headings, and text -->
  </div>
</section>
```

### Quote
![quote](https://github.com/manningstinson/atlas-web-development/assets/104523090/005a34cd-176b-4dd0-870a-e863ffe29416)

```html
<section>
  <h2>Quote</h2>
  <div>
    <img src="img/quote.png" alt="quote" />
  </div>
  <div>
    <blockquote>
      <p>
        « Those tutorials are concise and go straight to the point. I can’t think of a better place to learn smiling. And it’s so fun! »
      </p>
    </blockquote>
    <p>Author/Person Name</p>
    <p>Author Job</p>
  </div>
</section>
```

### Videos
![videos](https://github.com/manningstinson/atlas-web-development/assets/104523090/925940d3-f715-4ee3-8bb1-830ad6e48144)

```html
<section>
  <h1>Most Popular Tutorials</h1>

  <div class="videos">
    <!-- Four video blocks with images, headings, and text -->
  </div>

  <div>
    <!-- Block for author information -->
  </div>
</section>
```

### Membership
![membership](https://github.com/manningstinson/atlas-web-development/assets/104523090/ed038768-0929-41a8-8c0b-10c5b096b616)

```html
<section>
  <h1>Free Membership</h1>

  <div>
    <!-- Four membership options with images, headings, text, and a button -->
  </div>
  <button>Register For Free</button>
</section>
```


### FAQ
![faq](https://github.com/manningstinson/atlas-web-development/assets/104523090/a24fba43-d610-408c-a185-bbceefc394bc)

```html
<section>
  <h1>Frequently Asked Questions</h1>

  <div class="row">
    <div class="item">
      <!-- First FAQ item with a question and answer -->
    </div>
    <div class="item">
      <!-- Second FAQ item with a question and answer -->
    </div>
  </div>

  <div class="row">
    <div class="item">
      <!-- Third FAQ item with a question and answer -->
    </div>
    <div class="item">
      <!-- Fourth FAQ item with a question and answer -->
    </div>
  </div>
</section>
```

### Footer
![footer](https://github.com/manningstinson/atlas-web-development/assets/104523090/5a3a7a65-6e41-4567-916a-6f6d1bb2fa4b)

```html
<footer>
  <div>
    <div class="main-footer">
      <img src="img/footer-image.png" alt="Footer Image" />

      <div class="footerlinks">
        <!-- Three navigation links -->
      </div>
      <p>Copyright - @Copyright Smile School</p>
    </div>
  </div>
</footer>
```
