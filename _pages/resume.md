---
layout: page
title: resume
---
<html>
    <head>
        <style>
/*            Each box 0 or 1 can hold 2 frames. To add more frames begin with a box 0 0r 1 properties, insert box a inside for frame.*/
            main {
                margin: 0 auto;
                max-width: 76rem !important;
            }
            /* Optional: Style the container for better control over the iframe size */
            .pdf-container {
                width: 100%;
                height: 600px; /* Adjust height as needed */
                border: 1px solid #ccc;
            }
            /* Ensure the iframe fills its container */
            .pdf-iframe {
                width: 100%;
                height: 100%;
                border: none; /* Removes default iframe border */
            }
 </style>
</head>
<body>

    <h1>Viewing Michael Amay's Resume.</h1>

    <h4>
       <a href="/Amay_Michael.pdf" download="Amay_Michael.pdf">Download </a>Michael's Resume here!
    </h4>

    <div class="pdf-container">
        <!-- The iframe element embeds the PDF -->
        <iframe class="pdf-iframe" src="/Amay_Michael.pdf" title="Embedded PDF Document">
            <!-- Fallback content for browsers that do not support iframes or embedding PDFs directly -->
            Your browser does not support iframes. You can [download the PDF document](Amay_Michael.pdf) instead.
        </iframe>
    </div>

</body>

</html>

<br>
<br>
<br>
<br>
<br>
