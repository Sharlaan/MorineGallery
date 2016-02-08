# Morine Gallery

Live site : http://morine.artiste.free.fr
Admin board : http://morine.artiste.free.fr/admin

test site : http://drakensang.optimizer.free.fr/Morine
test site : http://drakensang.optimizer.free.fr/Morine/admin

This responsive gallery is dedicated to my mother's paintings. It consists in two sections:
- a public one where visitors can read about the artist's techniques and inspirations, view her paintings, and drop comments.
- a private one* where the administrator can manage the gallery's contents.
*TODO: authentification is not active yet.

The backend is built with PHP and MySQL.
Both frontend are powered with AngularJS.
The public frontend is built with Angular-Material, and viewerJS*;
while the private frontend is built with raw HTML5/CSS3, angular-draganddrop and the excellent DanialFarid's angular-file-upload.

*TODO: integrate ViewerJS

Admin-board features one simple editor to:
- organize paints into groups
- drop-in (or selects from your drive) an image file
- specify the paint's dimensions
- automatic error display (Angular's ngMessages)
- 
The admin can also dragover paints objects within or between groups.
