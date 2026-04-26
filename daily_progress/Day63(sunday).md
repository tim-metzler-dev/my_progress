So today I made one of the oldest websites (spork.org) and I learned a bit about layout (used my learnings). The style is CSS/spork_style.css

<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="stylesheet" href="CSS/spork_style.css">
        <meta charset="utf-8">
        <title>Spork</title>
        <meta name="description" content="Spork, the best of both worlds!">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        
    </head>
    <body>
        <section class="opening">
        <img src="Pictures/spork.png" alt="Picture of a spork with the text spork">
        <h1>Spork! How do I Love thee? Let me count the prongs...</h1>
        <p id="last-updated">Last updated: 10-Sep-1996</p>
        <hr/>
        </section>
        <div class="gnew">
            <h2>What's gnew?</h2>
            <ol>
                <li>The shirts are here! Check out the Spork Gear page for details.</li>
            </ol>
            <hr/>
        </div>
        <div class="gear">
            <a href="https://spork.org/spork-gear.shtml" id="link">Spork Gear</a>
            <p>The spork shirts are here! We're selling them for $7 a shirt, XL only at the moment. Check it out.</p>
            <hr/>
        </div>
        <section>
            <div>
                <h2>What is a spork?</h2>
                <dt>Spork:</dt>
                <dd>Blend of sp(oon sb. + f)ork sb. A proprietary name for a piece of cutlery combining the features of a spoon, fork, (and sometimes, knife). `Spork' is the colloquial term for `Runcible Spoon'</dd><br/>
                <dt>Patent Information:</dt>
                <dd>1970 Official Gaz. (U.S. Patent Office) 11 Aug. tm 65 Van Brode Milling Co., Inc., Clinton, Mass... Spork for Combination Plastic Spoon, Fork and Knife.</dd><br/>
                <div class="information">
                <h3>Yet a spork is so much more than just a poor excuse for an eating utensil.</h3><br/>
                <p>A spork is a perfect metaphor for human existance. It tries to function as both spoon and fork, and because of this dual nature, it fails miserably at both. You cannot have soup with a spork, it is far too shallow; you cannot eat meat with a spork, the prongs are too small.</p>
                <hr/>
                </div>
            </div>
        </section>
    </body>
</html>
