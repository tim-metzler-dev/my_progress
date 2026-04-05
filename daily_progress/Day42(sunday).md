Hey! So today I made a google page and I checked also a little bit for accesibility and also tried google light house.
I used aria-label and clean html. I don't have CSS at this moment but that will come later. Today I needed 23 minutes.


<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>Google</title>
        <meta name="description" content="Google search engine">
        <meta property="og:type" content="website">
        <meta property="og:title" content="Google search engine">
        <meta property="og:url" content="google.com">
        <meta property="og:image" content="Pictures/google.png">
    </head>
    <body>
        <header>
            <p>
                <a href="#">About</a>
                <a href="#">Store</a>
            </p>
            <p>
                <a href="#">Gmail</a>
                <a href="#">Images</a>
                <a href="#"><img src="Pictures/google-app (1).png" alt="go to google apps" width="20"></a>
            </p>
            <button>Sign in</button><hr/>
        </header>
        <main>
            <img src="Pictures/google-app (2).png" alt="Google logo" height="100">
            <form action="" class="input-group">
                <button type="button" aria-label="Add new Tab">+</button>
                <input type="text" placeholder="Search Google or type a URL" size="30">
                <button aria-label="Voice search"><img src="Pictures/google-voice.png" alt="" width="20"></button>
                <button aria-label="Picture search"><img src="Pictures/google-picture.png" alt="" width="20"></button>
                <button aria-label="AI search"><img src="Pictures/google-ai.png" alt="" width="60"></button>
            </form>
            <section class="search-buttons">
                <button>Google Search</button>
                <button>I'm Feeling Lucky</button>
            </section>
        </main>
    </body>
</html>
