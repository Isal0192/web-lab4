#index.html

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana</title>
    <link rel="stylesheet" href="style.css">
    </head>
    <body>
    <div id="container">
        <header>
            <h1>Layout Sederhana</h1>
            </header>
            <nav>
            <a href="home.html" class="active">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Kontak</a>
            </nav>
            <section id="wrapper">
                <section id="main"></section>
                <aside id="sidebar"></aside>
                </section>
            <section id="hero">
                <h1>Hello World!</h1>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
                elit, iaculis innisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
                vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
                pretium ac.</p>
                <a href="home.html" class="btn btn-large">Learn more &raquo;</a>
                </section>
            <aside id="sidebar">
                <div class="widget-box">
                <h3 class="title">Widget Header</h3>
                <ul>
                <li><a href="#">Widget Link</a></li>
                <li><a href="#">Widget Link</a></li>
                <li><a href="#">Widget Link</a></li>
                <li><a href="#">Widget Link</a></li>
                <li><a href="#">Widget Link</a></li>
                </ul>
                </div>
                <div class="widget-box">
                <h3 class="title">Widget Text</h3>
                <p>Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt
                arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer
                pharetra est nunc, nec pretium nunc pretium ac.</p>
                </div>
            </aside>
            <section id="main">
                <div class="row">
                <div class="box">
                <img src="https://dummyimage.com/120/db7d25/fff.png" alt=""
                class="image-circle">
                <h3>Heading</h3>
                <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
                euismod.</p>
                <a href="#" class="btn btn-default">View detail</a>
                </div>
                <div class="box">
                <img src="https://dummyimage.com/120/3e73e6/fff.png" alt=""
                class="image-circle">
                <h3>Heading</h3>
                <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
                euismod.</p>
                <a href="#" class="btn btn-default">View detail</a>
                </div>
                <div class="box">
                <img src="https://dummyimage.com/120/71e6d4/fff.png" alt=""
                class="image-circle">
                <h3>Heading</h3>
                <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
                euismod.</p>
                <a href="#" class="btn btn-default">View detail</a>
                </div>
                </div>
            </section>
            <hr class="divider" />
        <article class="entry">
            <h2>First featurette heading.</h2>
            <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
            elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
            vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
            pretium ac.</p>
        </article>
        <hr class="divider" />
        <article class="entry">
            <h2>First featurette heading.</h2>
            <img src="https://dummyimage.com/150/7b8a70/fff.png" alt=""
            class="right-img">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
            elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
            vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
            pretium ac.</p>
        </article>
    
      <section class="section">
          <div class="header">
              <h1>About Me</h1>
          </div>
          <div class="about-content">
              <div class="about-text">
                  <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Earum accusantium obcaecati quo corrupti corporis necessitatibus. Voluptatibus quod veniam natus deserunt? Cumque consequatur iusto sunt dignissimos blanditiis recusandae odit tempora quisquam?</p>
                  <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ut, error repellat quasi quam quisquam et aspernatur ullam molestiae commodi, quas nemo repudiandae placeat nostrum minima id cum? Eos, consectetur inventore!</p>
              </div>
          </div>
      </section>
    
      <!-- Portfolio Section -->
      <section class="section">
          <div class="header">
              <h1>My Portfolio</h1>
          </div>
          <div class="portfolio">
          </div>
      </section>
      <!-- Contact Section -->
      <section class="section">
          <div class="header">
              <h1>Contact Me</h1>
          </div>
          <div class="contact-form">
              <form action="#" method="post">
                  <div class="form-group">
                      <label for="name">Name</label>
                      <input type="text" id="name" name="name" required>
                  </div>
                  <div class="form-group">
                      <label for="email">Email</label>
                      <input type="email" id="email" name="email" required>
                  </div>
                  <div class="form-group">
                      <label for="subject">Subject</label>
                      <input type="text" id="subject" name="subject" required>
                  </div>
                  <div class="form-group">
                      <label for="message">Message</label>
                      <textarea id="message" name="message" rows="5" required></textarea>
                  </div>
                  <button type="submit">Send Message</button>
              </form>
          </div>
      </section>
          <footer>
              <p>&copy; 2021 - Universitas Pelita Bangsa</p>
          </footer>
    </div>
    </body>
    </html>

#style.css
    /* import google font */
    @import
    url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap');
    @import
    url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0,300;0,700;1,300&display=swap');
    /* Reset CSS */
    * {
    margin: 0;
    padding: 0;
    }
    body {
    line-height:1;
    font-size:100%;
    font-family:'Open Sans', sans-serif;
    color:#5a5a5a;
    }
    #container {
    width: 980px;
    margin: 0 auto;
    box-shadow: 0 0 1em #cccccc;
    }
    /* header */
    header {
    padding: 20px;
    }
    header h1 {
    margin: 20px 10px;
    color: #b5b5b5;
    }
    
    /* navigasi */
    nav {
    display: block;
    background-color: #1f5faa;
    }
    nav a {
    padding: 15px 30px;
    display: inline-block;
    color: #ffffff;
    font-size: 14px;
    text-decoration: none;
    font-weight: bold;
    }
    nav a.active,
    nav a:hover {
    background-color: #2b83ea;
    }
    /* Hero Panel */
    #hero {
    background-color: #e4e4e5;
    padding: 50px 20px;
    margin-bottom: 20px;
    }
    #hero h1 {
    margin-bottom: 20px;
    font-size: 35px;
    }
    #hero p {
    margin-bottom: 20px;
    font-size: 18px;
    line-height: 25px;
    }
    
    /* main content */
    #wrapper {
    margin: 0;
    }
    #main {
    float: left;
    width: 640px;
    padding: 20px;
    }
    /* sidebar area */
    #sidebar {
    float: right;
    width: 260px;
    padding: 20px;
    }
    
    /* widget */
    .widget-box {
    border:1px solid #eee;
    margin-bottom:20px;
    }
    .widget-box .title {
    padding:10px 16px;
    background-color:#428bca;
    color:#fff;
    }
    .widget-box ul {
    list-style-type:none;
    }
    .widget-box li {
    border-bottom:1px solid #eee;
    }
    .widget-box li a {
    padding:10px 16px;
    color:#333;
    display:block;
    text-decoration:none;
    }
    .widget-box li:hover a {
    background-color:#eee;
    }
    .widget-box p {
    padding:15px;
    line-height:25px;
    }
    
    /* footer */
    footer {
    clear:both;
    background-color:#1d1d1d;
    padding:20px;
    color:#eee;
    }
    /* box */
    .box {
    display:block;
    float:left;
    width:33.333333%;
    box-sizing:border-box;
    -moz-box-sizing:border-box;
    -webkit-box-sizing:border-box;
    padding:0 10px;
    text-align:center;
    }
    .box h3 {
    margin: 15px 0;
    }
    .box p {
    line-height: 20px;
    font-size: 14px;
    margin-bottom: 15px;
    }
    box img {
    border: 0;
    vertical-align: middle;
    }
    .image-circle {
    border-radius: 50%;
    }
    .row {
    margin: 0 -10px;
    box-sizing: border-box;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    }
    .row:after, .row:before,
    .entry:after, .entry:before {
    content:'';
    display:table;
    }
    .row:after,
    .entry:after {
    clear:both;
    }
    
    .divider {
    border:0;
    border-top:1px solid #eeeeee;
    margin:40px 0;
    }
    /* entry */
    .entry {
    margin: 15px 0;
    }
    .entry h2 {
    margin-bottom: 20px;
    }
    .entry p {
    line-height: 25px;
    }
    .entry img {
    float: left;
    border-radius: 5px;
    margin-right: 15px;
    }
    .entry .right-img {
    float: right;
    }
    
    
    .section {
        padding: 40px 0;
    }
    
    .header {
        text-align: center;
        padding-bottom: 20px;
    }
    
    .header h1 {
        font-size: 2.5em;
        color: #333;
    }
    
    .about-content {
        display: flex;
        align-items: flex-start;
        gap: 20px;
    }
    
    .about-content img {
        max-width: 100%;
        height: auto;
        border-radius: 10px;
    }
    
    .about-text {
        max-width: 600px;
    }
    
    .about-text p {
        color: #555;
        line-height: 1.6;
    }
    
    
    .contact-form {
        max-width: 600px;
        margin: 0 auto;
        padding: 20px;
        background-color: #fff;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    
    .contact-form form {
        display: flex;
        flex-direction: column;
    }
    
    .form-group {
        margin-bottom: 15px;
    }
    
    .form-group label {
        font-weight: bold;
        color: #333;
        margin-bottom: 5px;
        display: block;
    }
    
    .form-group input,
    .form-group textarea {
        width: 100%;
        padding: 10px;
        border-radius: 5px;
        border: 1px solid #ddd;
        font-size: 1em;
        color: #333;
    }
    
    .form-group input:focus,
    .form-group textarea:focus {
        border-color: #555;
        outline: none;
    }
    
    button[type="submit"] {
        background-color: #333;
        color: #fff;
        padding: 12px;
        border: none;
        border-radius: 5px;
        font-size: 1em;
        cursor: pointer;
        transition: background-color 0.3s;
    }
    
    button[type="submit"]:hover {
        background-color: #555;
    }


#gambar
![Screenshot 2024-10-28 115836](https://github.com/user-attachments/assets/cc97ad95-e065-467d-bdc0-ddb6710e5b65)
![Screenshot 2024-10-28 120034](https://github.com/user-attachments/assets/efa0362e-c450-4520-bc63-e78cd020746f)


