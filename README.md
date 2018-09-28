# Basic-Portfolio

A few updates (super special bonus points) I did to the assignment, just so I could become more familiar with Heroku. I modified the following from the base assignment: 

1. Renamed index.html to home.html
2. Modified the links on home.html, contact.html and portfolio.html to reference home.html
3. Added index.php. This was required to "fake" Heroku into thinking it was a php site, although it's not even used. There is no buildpack for a static website with Heroku at this time.
4. Added composer.json (needed for Heroku - see above)
5. Leveraged heroku to do automated builds and deploys which was *super* easy.

You can access the site here: https://figgins-portfolio.herokuapp.com/

I followed the gist here: https://gist.github.com/wh1tney/2ad13aa5fbdd83f6a489