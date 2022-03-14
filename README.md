# HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="row">
                <div class="col w-3 left">
                    <div class="logo">
                        <a href="/"><img src="https://thedevdrawer.com/assets/img/logo-header.png"></a>
                    </div>
                </div>
                <div class="col w-9">
                    <div id="menu">
                        <button type="button" id="menu-btn">Menu</button>
                    </div>
                    <nav id="nav">
                        <ul>
                            <li><a href="/" class="active">Home</a></li>
                            <li><a href="/about.html">About</a></li>
                            <li><a href="/contact.html">Contact</a></li>
                        </ul>
                    </nav>
                </div>
            </div>
        </div>
    </header>
    <main>
        <div class="hero">
            <div class="container">
                <div class="row">
                    <div class="col w-7 left">
                        <h1>Sample Header Here</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima eum, molestias animi aliquam ipsum architecto unde ut, neque quo laborum deserunt veritatis repellendus fugit dolore quisquam, quas quam porro rem.</p>
                        <a href="/contact.html" class="btn">Contact</a>
                    </div>
                    <div class="col w-5">
                        <div class="card">
                            <h2>Join Our Mailing List</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima eum, molestias animi aliquam.</p>
                            <form action="">
                                <input type="text" placeholder="First Name">
                                <input type="text" placeholder="Last Name">
                                <input type="text" placeholder="Email Address">
                                <p class="text-center"><button type="submit">Submit</button></p>
                            </form>
                            <p><small><em>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima eum, molestias animi aliquam ipsum architecto unde ut, neque quo laborum deserunt veritatis repellendus fugit dolore quisquam, quas quam porro rem.</em></small></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class="col text-center">
                    <div class="icon"></div>
                    <h4>Service 1</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
                <div class="col text-center">
                    <div class="icon"></div>
                    <h4>Service 2</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
                <div class="col text-center">
                    <div class="icon"></div>
                    <h4>Service 3</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
                <div class="col text-center">
                    <div class="icon"></div>
                    <h4>Service 4</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
        </div>
    </main>
    <footer>
        <p class="text-center hidden-sm">
            <a href="/index.html" class="active">Home</a> | <a href="/about.html">About</a> | <a href="/contact.html">Contact</a>
        </p>
        <p class="text-center">
            Fake Copyright 2021 &copy; The Dev Drawer
        </p>
    </footer>
    <script src="js/init.js"></script>
</body>
</html>
