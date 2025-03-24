<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>+7 by Lara Arditi</title>
    <style>
        body {
            font-family: 'Minion', serif;
            font-size: 16px;
            color: black;
            background-color: white;
            margin: 0;
            padding: 16px;
        }
        
        /* Container with padding control */
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            position: relative;
            overflow-x: hidden; /* Prevent horizontal scrollbar from extending backgrounds */
        }
        
        a {
            background-color: black;
            color: white;
            text-decoration: underline;
            padding: 0 3px;
            font-size: 16px;
            line-height: 1;
            display: inline-block;
        }
        
        p {
            line-height: 1.6;
        }
        
        .description {
            margin-bottom: 40px;
        }
        
        .edition {
            margin-top: 60px;
            margin-bottom: 20px;
        }
        
        .edition-links {
            display: flex;
            flex-direction: column;
            position: relative;
        }
        
        .edition-title, .cross-analysis {
            margin: 0;
            padding: 0;
            line-height: 1;
        }
        
        .id-container {
            position: relative;
            margin-top: 0;
        }
        
        /* Create a common left edge for all elements */
        .edition, .id-container {
            padding-left: 0;
        }
        
        /* Style for the ID elements with left extending black background */
        .id-item {
            margin: 0;
            padding: 0;
            position: relative;
            line-height: 1;
            white-space: nowrap;
            margin-bottom: 0; /* No space between items */
        }
        
        .id-item a {
            position: relative;
            z-index: 1;
        }
        
        /* Black background that extends to the left */
        .id-item:before {
            content: "";
            position: absolute;
            height: 100%;
            width: 2000px;
            right: 100%;
            top: 0;
            background-color: black;
        }
        
        /* Add horizontal lines after all ID items with no spacing */
        .id-item:after {
            content: "";
            position: absolute;
            height: 1px;
            left: -2000px; /* Extend to the left */
            right: 0;
            bottom: 0; /* No spacing below */
            background-color: black;
        }
        
        /* Base positioning for the diagonal pattern - using classes instead of IDs */
        .id-item:nth-child(1) { margin-left: 0; }
        .id-item:nth-child(2) { margin-left: 70px; }
        .id-item:nth-child(3) { margin-left: 140px; }
        .id-item:nth-child(4) { margin-left: 210px; }
        .id-item:nth-child(5) { margin-left: 280px; }
        .id-item:nth-child(6) { margin-left: 350px; }
        .id-item:nth-child(7) { margin-left: 420px; }
        .id-item:nth-child(8) { margin-left: 490px; }
        .id-item:nth-child(9) { margin-left: 560px; }
        .id-item:nth-child(10) { margin-left: 630px; }
        .id-item:nth-child(11) { margin-left: 700px; }
        .id-item:nth-child(12) { margin-left: 770px; }
        
        /* Responsive adjustments */
        @media (max-width: 992px) {
            .id-item:nth-child(2) { margin-left: 60px; }
            .id-item:nth-child(3) { margin-left: 120px; }
            .id-item:nth-child(4) { margin-left: 180px; }
            .id-item:nth-child(5) { margin-left: 240px; }
            .id-item:nth-child(6) { margin-left: 300px; }
            .id-item:nth-child(7) { margin-left: 360px; }
            .id-item:nth-child(8) { margin-left: 420px; }
            .id-item:nth-child(9) { margin-left: 480px; }
            .id-item:nth-child(10) { margin-left: 540px; }
            .id-item:nth-child(11) { margin-left: 600px; }
            .id-item:nth-child(12) { margin-left: 660px; }
        }
        
        @media (max-width: 768px) {
            .id-item:nth-child(2) { margin-left: 50px; }
            .id-item:nth-child(3) { margin-left: 100px; }
            .id-item:nth-child(4) { margin-left: 150px; }
            .id-item:nth-child(5) { margin-left: 200px; }
            .id-item:nth-child(6) { margin-left: 250px; }
            .id-item:nth-child(7) { margin-left: 300px; }
            .id-item:nth-child(8) { margin-left: 350px; }
            .id-item:nth-child(9) { margin-left: 400px; }
            .id-item:nth-child(10) { margin-left: 450px; }
            .id-item:nth-child(11) { margin-left: 500px; }
            .id-item:nth-child(12) { margin-left: 550px; }
        }
        
        @media (max-width: 480px) {
            .id-item:nth-child(2) { margin-left: 30px; }
            .id-item:nth-child(3) { margin-left: 60px; }
            .id-item:nth-child(4) { margin-left: 90px; }
            .id-item:nth-child(5) { margin-left: 120px; }
            .id-item:nth-child(6) { margin-left: 150px; }
            .id-item:nth-child(7) { margin-left: 180px; }
            .id-item:nth-child(8) { margin-left: 210px; }
            .id-item:nth-child(9) { margin-left: 240px; }
            .id-item:nth-child(10) { margin-left: 270px; }
            .id-item:nth-child(11) { margin-left: 300px; }
            .id-item:nth-child(12) { margin-left: 330px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="description">
            <p><a href="#">&lt;INGREDIENT&gt;</a>+7 is an ongoing <a href="#">&lt;THESIS&gt;</a> by <a href="#">&lt;LARA ARDITI&gt;</a> exploring the idea that language uses syntax to organize pre-existing morsels of verbal expression to create sensibility is a notion that, when applied to cooking, becomes what is commonly known as a recipe.</p>
            
            <p>When thinking of recipes, the expectation is for them to yield a palatable dish, but the true nature of cooking is more an accident guided by intuition. When given parameters of <a href="#">&lt;INGREDIENTS&gt;</a>, <a href="#">&lt;AUDIENCES&gt;</a>, <a href="#">&lt;PURPOSES&gt;</a>, <a href="#">&lt;SPACES&gt;</a> <a href="#">&lt;PREPARATIONS&gt;</a>, <a href="#">&lt;VESSELS&gt;</a>, <a href="#">&lt;UTENSILS&gt;</a>, people are not necessarily concerned with selecting what is good or bad but manipulating these elements to create a means a discourse, a meal.</p>
            
            <p>This principle is reflected through four books with a stripped-down nature that use the functional aesthetics of the spreadsheet. This serves as an homage to the original function of recipe books in Medieval times when records of food were kept to show the domestic histories of the wealthy and did not make its way into the kitchen until the 19th century. This aligns with contemporary cookbooks, which have taken image-heavy, aspirational roles where they remain on coffee tables and rarely appear in kitchens. This series of hand-sized, loose-bound, word-dominated, monochromatic books use a constructed mathematical process for cooking, rather than a predetermined literary tract to free up space for conceptual thought as the basis for ideation in food.</p>
            
            <p>Inquiries for collaborations and purchases are welcome through <a href="mailto:LARA.ARDITI@HOTMAIL.COM">&lt;LARA.ARDITI@HOTMAIL.COM&gt;</a>. If you'd like to contribute to the project, feel free to fill out the <a href="#">&lt;SURVEY&gt;</a>. Keep scrolling to access the <a href="#">&lt;RESPONSE DATABASE&gt;</a> making up the content of the printed books.</p>
            
            <p>For more text on the project see <a href="#">&lt;INTRODUCTION&gt;</a>.</p>
        </div>
        
        <!-- Edition 1 -->
        <div class="edition">
            <div class="edition-links">
                <div class="edition-title"><a href="#">&lt;EDITION_1&gt;</a></div>
                <div class="cross-analysis"><a href="#">&lt;CROSS_ANALYSIS&gt;</a></div>
            </div>
            <div class="id-container">
                <div class="id-item"><a href="#">&lt;ID@1&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@2&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@3&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@4&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@5&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@6&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@7&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@8&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@9&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@10&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@11&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@12&gt;</a></div>
            </div>
        </div>
        
        <!-- Edition 2 -->
        <div class="edition">
            <div class="edition-links">
                <div class="edition-title"><a href="#">&lt;EDITION_2&gt;</a></div>
                <div class="cross-analysis"><a href="#">&lt;CROSS_ANALYSIS&gt;</a></div>
            </div>
            <div class="id-container">
                <div class="id-item"><a href="#">&lt;ID@1&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@2&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@3&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@4&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@5&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@6&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@7&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@8&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@9&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@10&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@11&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@12&gt;</a></div>
            </div>
        </div>
        
        <!-- Edition 3 -->
        <div class="edition">
            <div class="edition-links">
                <div class="edition-title"><a href="#">&lt;EDITION_3&gt;</a></div>
                <div class="cross-analysis"><a href="#">&lt;CROSS_ANALYSIS&gt;</a></div>
            </div>
            <div class="id-container">
                <div class="id-item"><a href="#">&lt;ID@1&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@2&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@3&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@4&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@5&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@6&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@7&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@8&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@9&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@10&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@11&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@12&gt;</a></div>
            </div>
        </div>
        
        <!-- Edition 4 -->
        <div class="edition">
            <div class="edition-links">
                <div class="edition-title"><a href="#">&lt;EDITION_4&gt;</a></div>
                <div class="cross-analysis"><a href="#">&lt;CROSS_ANALYSIS&gt;</a></div>
            </div>
            <div class="id-container">
                <div class="id-item"><a href="#">&lt;ID@1&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@2&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@3&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@4&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@5&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@6&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@7&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@8&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@9&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@10&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@11&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@12&gt;</a></div>
            </div>
        </div>
        
        <!-- Edition 5 -->
        <div class="edition">
            <div class="edition-links">
                <div class="edition-title"><a href="#">&lt;EDITION_5&gt;</a></div>
                <div class="cross-analysis"><a href="#">&lt;CROSS_ANALYSIS&gt;</a></div>
            </div>
            <div class="id-container">
                <div class="id-item"><a href="#">&lt;ID@1&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@2&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@3&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@4&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@5&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@6&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@7&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@8&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@9&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@10&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@11&gt;</a></div>
                <div class="id-item"><a href="#">&lt;ID@12&gt;</a></div>
            </div>
        </div>
    </div>
</body>
</html>
