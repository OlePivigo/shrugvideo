# ShrugVideo.fun \_(ツ)_/¯

[![Build status](https://dev.azure.com/dearruda/ShrugVideo/_apis/build/status/shurgvideo%20-%20CI)](https://dev.azure.com/dearruda/ShrugVideo/_build/latest?definitionId=1)

A flask base web app that user(IP) can submit their video just after watch the last video submitted.

This application displays the last video submitted by the last user(IP), users are only able to submit his video after watch the currently video until the end.
Videos shorter than 5 minutes has priority.

Logic:
-User as selected by IP
-Users are only able to skip video if finish currently video, reload page wont work.
-Video starts muted to enable auto-play, audio start if user interact with the page. No able to select video iframe.

[![Demo ShrugVideo](https://media.giphy.com/media/KatGxhd061hWHHATj0/giphy.gif)](https://www.youtube.com/watch?v=m2Ep9eaB0_Q&feature=youtu.be)



Framework:
- SPECTRE.CSS - https://picturepan2.github.io/spectre/index.html
- jQuery - https://jquery.com/
- Flask - http://flask.pocoo.org/
- flask-sqlalchemy - http://flask-sqlalchemy.pocoo.org
- pafy - https://pythonhosted.org/Pafy/

website available at http://shrugvideo.fun
Hosted in a Raspberry PI 3A running Apache2 and mod_wsgi.
You can find the configuratin file at: https://gist.github.com/arrudaricardo/73cc13da07c71213792b80cc17d8c814
