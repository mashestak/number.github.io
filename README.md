<!DOCTYPE html>
<html lang="en">
<head>
    <title>Shower Presentation Engine</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
    <link rel="stylesheet" href="node_modules/@shower/ribbon/styles/styles.css">
    <style>
        .shower {
            --slide-ratio: calc(16 / 9);
        }
    </style>
</head>
<body class="shower list">

    <header class="caption">
        <h1>Shower Presentation Engine</h1>
        <p>Yours Truly, Famous Inc.</p>
    </header>
     <section class="slide" id="cover">
        <h2>Shower Presentation Engine</h2>
        <p>Brought to you by <a href="https://pepelsbey.net">Vadim Makeev</a></p>
        <figure>
            <img class="cover" src="pictures/cover.jpg" alt="Hands on the orange typewriter in a park">
            <figcaption class="copyright right white">
                <a href="https://fiftyfootshadows.net">© John Carey</a>
            </figcaption>
        </figure>
        <style>
            #cover h2 {
                margin: 30px 0 0;
                color: white;
                text-align: center;
                font-size: 70px;
            }

            #cover p {
                margin: 10px 0 0;
                text-align: center;
                color: white;
                font-style: italic;
                font-size: 20px;
            }

            #cover p a {
                color: white;
            }
        </style>
    </section>

    <section class="slide">
        <h2>Shower key features</h2>
        <ol>
            <li>Built on HTML, CSS and JavaScript</li>
            <li>Works in all modern browsers</li>
            <li>Themes are separated from engine</li>
            <li>Fully keyboard accessible</li>
            <li>Printable to PDF</li>
        </ol>
        <p class="note">Shower ['ʃəuə] noun. A person or thing that shows.</p>
    </section>

    <section class="slide">
        <h2>Plain text on your slides</h2>
        <p>Lorem ipsum dolor sit amet, consectetur <a href="#4">adipisicing</a> elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, <em>quis nostrud</em> exercitation ullamco laboris <strong>nisi ut aliquip</strong> ex ea commodo consequat. Duis aute irure <i>dolor</i> in reprehenderit in voluptate velit esse cillum <b>dolore</b> eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in <code>&lt;culpa&gt;</code> qui officia deserunt mollit anim id est laborum.</p>
    </section>
 </body>
</html>
