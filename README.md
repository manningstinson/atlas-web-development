![atlas-advanced-html-header](https://github.com/manningstinson/atlas-web-development/assets/104523090/5c55f9cf-057c-4901-9e52-3dc9df22d084)

# Atlas School  | HTML Advanced

In this project we were to create the semantic layout of a web static project. We had a wireframe mockup that we followed. No CSS styling was added yet. Below are the wireframes for the project that were followed, and the resulting code. 

The wireframe was created in Figma, and can be accessed here. 
[Figma Wireframe](https://www.figma.com/file/XrEAsu1vQj5fhVaNG38d2W/Homepage?type=design&node-id=0-1&mode=design&t=r2vCvbwwmBs9XkWP-0)

You can access the HTML file here:
[index.html](https://github.com/manningstinson/atlas-web-development/blob/main/html_advanced/index.html)


## Objectives
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
          <div>
            <div class="pro1">
              <img src="img/phillip-massey.png" alt="Phillip Massey" />
              <p>« Smile of the year » 2018 - 2019</p>
            </div>

            <div class="pro2">
              <img src="img/nannie-lawrence.png" alt="Nannie Lawrence" />
              <p>« Best « little smile » 2017</p>
            </div>

            <div class="pro3">
              <img src="img/bruce-walters.png" alt="Bruce Walters" />
              <p>« Best « Friend Smile » live performance 2019</p>
            </div>

            <div class="pro4">
              <img src="img/henry-hughes.png" alt="Henry Hughes" />
              <p>« 24h smiles » winner 2016 - 2019</p>
            </div>
          </div>
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
              « Those tutorials are concise and go straight to the point. I
              can’t think of a better place to learn smiling. And it’s so fun! »
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
          <div class="Diagonal-Smile">
            <div class="tutorial-information">
              <img src="img/phillip-massey.png" alt="Phillip Massey" />
              <h3>Diagonal Smile</h3>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
            </div>

            <div class="rating">
              <img src="img/star-filled.png" alt="Filled Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <p>Review Author - Phillip Massey</p>
            </div>
          </div>

          <div class="Sad-Smile">
            <div class="tutorial-information">
              <img src="img/phillip-massey.png" alt="Phillip Massey" />
              <h3>Sad Smile</h3>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
            </div>

            <div class="rating">
              <img src="img/star-filled.png" alt="Filled Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <p>Review Author - Phillip Massey</p>
            </div>
          </div>

          <div class="Natural-Smile">
            <div class="tutorial-information">
              <img src="img/phillip-massey.png" alt="Phillip Massey" />
              <h3>Natural Smile</h3>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
            </div>

            <div class="rating">
              <img src="img/star-filled.png" alt="Filled Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <p>Review Author - Phillip Massey</p>
            </div>
          </div>

          <div class="Happy-Smile">
            <div class="tutorial-information">
              <img src="img/phillip-massey.png" alt="Phillip Massey" />
              <h3>Happy Smile</h3>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
            </div>

            <div class="rating">
              <img src="img/star-filled.png" alt="Filled Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <img src="img/star-empty.png" alt="Empty Star" />
              <p>Review Author - Phillip Massey</p>
            </div>
          </div>
        </div>
      </section>
```

### Membership
![membership](https://github.com/manningstinson/atlas-web-development/assets/104523090/ed038768-0929-41a8-8c0b-10c5b096b616)

```html
 <section>
        <h1>Free Membership</h1>

        <div>
          <img src="img/member-option-1.png" alt="Membership Option 1" />
          <h2>Membership Option 1</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>

        <div>
          <img src="img/member-option-2.png" alt="Membership Option 2" />
          <h2>Membership Option 2</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>

        <div>
          <img src="img/member-option-3.png" alt="Membership Option 3" />
          <h2>Membership Option 3</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>

        <div>
          <img src="img/member-option-4.png" alt="Membership Option 4" />
          <h2>Membership Option 4</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        <button>Register For Free</button>
      </section>

```


### FAQ
![faq](https://github.com/manningstinson/atlas-web-development/assets/104523090/a24fba43-d610-408c-a185-bbceefc394bc)

```html
      <section>
        <section id="faq">
          <h1>Frequently Asked Questions</h1>

          <div class="row">
            <div class="item">
              <h2>How does this work?</h2>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
                in reprehenderit in voluptate velit esse cillum dolore eu fugiat
                nulla pariatur. Excepteur sint occaecat cupidatat non proident,
                sunt in culpa qui officia deserunt mollit anim id est laborum.
              </p>
            </div>

            <div class="item">
              <h2>How does this work?</h2>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
                in reprehenderit in voluptate velit esse cillum dolore eu fugiat
                nulla pariatur. Excepteur sint occaecat cupidatat non proident,
                sunt in culpa qui officia deserunt mollit anim id est laborum.
              </p>
            </div>
          </div>

          <div class="row">
            <div class="item">
              <h2>How does this work?</h2>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
                in reprehenderit in voluptate velit esse cillum dolore eu fugiat
                nulla pariatur. Excepteur sint occaecat cupidatat non proident,
                sunt in culpa qui officia deserunt mollit anim id est laborum.
              </p>
            </div>

            <div class="item">
              <h2>How does this work?</h2>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
                in reprehenderit in voluptate velit esse cillum dolore eu fugiat
                nulla pariatur. Excepteur sint occaecat cupidatat non proident,
                sunt in culpa qui officia deserunt mollit anim id est laborum.
              </p>
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
            <a href="login.html">Home</a>
            <a href="pricing.html">About</a>
            <a href="courses.html">Services</a>
          </div>
          <p>Copyright - @Copyright Smile School</p>
        </div>
      </div>
    </footer>
```
