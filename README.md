# GWL-elecTRON
A profile gallery for all members of Guild elecTRON! Made using basic HTML and CSS.

## Contributing Guide

If you are a member of guild elecTRON and want to rep your card on this webpage, follow the steps given below!

1. Fork the project repo.
2. Clone the forked repo on your machine.
3. Add your photo (preferably 1:1) inside the `images` folder. Make sure to rename it as your own name.
4. Add your card inside the `index.html` file as follows.
5. Paste the following card template above the `<!-- ADD YOUR CARD ABOVE THIS LINE! :D -->`
```html
  <div class="col-sm-12 col-md-6 col-lg-4 col-xl-3 mb-4">
      <div class="card member_card" style="width: 100%;">
          <img src="images/<YOUR IMAGE FILE NAME HERE>.jpg" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title"><YOUR NAME HERE></h5>
            <h6><YOUR DISCORD USERNAME HERE></h6>
            <p class="card-text"><YOUR SHORT BIO HERE></p>
            <div class="btn-group" role="group">
              <a href="<YOUR GITHUB PROFILE URL HERE>"><button type="button" class="btn btn-outline-dark"><i class="bi bi-github"></i></button></a>
              <a href="<YOUR INSTAGRAM PROFILE URL HERE>"><button type="button" class="btn btn-outline-dark"><i class="bi bi-instagram"></i></button></a>
              <a href="<YOUR TWITTER PROFILE URL HERE>"><button type="button" class="btn btn-outline-dark"><i class="bi bi-twitter"></i></button></a>
              <a href="<YOUR LINKEDIN PROFILE URL HERE>"><button type="button" class="btn btn-outline-dark"><i class="bi bi-linkedin"></i></button></a>
              </div>
          </div>
          <div class="fav-movie"><span><i class="bi bi-heart-fill"></i> <i class="bi bi-film"></i></span><span><YOUR FAVOURITE MOVIE HERE></span></div>
          <div class="fav-song"><span><i class="bi bi-heart-fill"></i><i class="bi bi-music-note-beamed"></i></span><span><YOUR FAVOURITE SONG HERE></span></div>
      </div>
  </div>
```
6. Make changes by adding your information wherever mentioned.
7. That's it! Stage your changes (`git add .`)
8. Commit your changes (`git commit -m 'Added my card'`)
9. Push to the changes to your forked repo (`git push origin master`)
10. Open a pull request to get your changes merged to this original repo!
