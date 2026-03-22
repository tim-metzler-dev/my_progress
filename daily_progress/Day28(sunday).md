I used the form and fieldset element and I learned about the span element wich you can use instead of the label element.
I made this in 35min. I copyed the casio checkout protockol because today I bought a casio GBD-200-1.


<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="description" content="Checkout of your product">
        <meta property="og:title" content="Casio GBD-200-1">
        <meta property="og:type" content="website">
        <meta property="og:image" content="https://www.casio.com/content/dam/casio/product-info/locales/de/de/timepiece/product/watch/G/GB/GBD/gbd-200-1/assets/GBD-200-1.png">
        <meta property="og:url" content="https://www.casio.com/us/checkout/#shipping">
        <title>Checkout</title>
    </head>
    <body>
        <header>
            <p><a href="#"><strong>G-SHOCK</strong></a> | <a><strong>CASIO</strong></a></p>
            <hr />
        </header>
        <main>
            <section>
                <form>
                    <fieldset>
                        <p>* indicates required field</p>
                    <legend>Shipping Information</legend>
                    <span>Phone number*</span><input required type="number" min="6" > <br />
                    <span>First name*</span><input required type="text">
                    <span>Last name*</span><input required type="text">
                    <span>Line 1*</span><input required type="text"> <br />
                    <span>Line 2*</span><input required type="text"> <br />
                    <span>City*</span><input required type="text"> <br />
                    <span>State/Province*</span><input required type="text"> <br />
                    <span>Country*</span><input required type="text"> <br />
                    <span>Zip/Postal Code*</span><input required type="number" > <br />
                    <span>Company Name</span><input type="text"> <br />
                        <p><input type="checkbox" checked>Yes, I’d like to receive emails about special offers and new products.</p>
                        <p>Please confirm you have entered your shipping address correctly. If you are still experiencing issues, please contact Customer Service at 123-456-7890.</p>
                    </fieldset>
                </form>
            </section>
        </main>
    </body>
</html>
