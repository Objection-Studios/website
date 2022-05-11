# Team Page

Our team page is one of my (Ethan) favourites,
This is the first bit we have given to the public
and will also contain some stuff on how to do it.
In this 'guide' I will use just a sample of it to
attempt to explain how it works.

### The Cards
This is one of the main parts of the page and the bit
we are looking at here.

(Image here)

```html
<!-- Cards !-->
        <!-- Ethan !-->

        <div class="card1">
          <img src="placeholder.jpg" alt="Avatar" style="width: 100%" />
          <div class="container2">
            <h2 class="profilehead">Ethan</h2>
            <p class="O">
              Founder & CEO <br />
              I make games and websites.
            </p>
          </div>
        </div>
```

The actual cards to go in rows used flexbox which
worked well from what I did. Even though I don't
understand flexbox 100% what I did worked so I
am happy with it.

So let's try and explain this, focus on try.
At the top we have a note saying what it is and who
it's for. Then we give it the card class which in
the css makes it look how it does. (You can see the
css in the attached file). After that there's the image,
currently set as a placeholder it has some width information
and alternate text. 

Then there's the container class which in the css makes stuff
inside it have padding of 3px making the text go in a bit. Then
there is the profile head, this is in each card for the name of
who's profile it is. It sets font size and fonts as well as centres
the text. Under that is the role and description separated by a
line break as they are both the same font and size. Under class 'o',
I use random letters for some reason, it sets the stuff inside it to
be a certain font and size just like the head but smaller.

That is basically it! If you have suggestions or questions let us know
through githubs issue thing or our server! We are glad to help. This is
our first time public-ifing some of our code. 

Note in the CSS there is some more stuff for the gaps between the flexbox
that is not covered in this.

