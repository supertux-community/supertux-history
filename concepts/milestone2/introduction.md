# Milestone 2 Goals

Now that Milestone1 is out and up and running, its time to take some preperations for Milestone2. Goals should of course include:

* new enemies
* at least one new tileset
* 15-30 new levels

However that are of course just generic goals that pretty much apply to any Milestone, more detail goals follow below and will be extented and refined over the comming month:

* intelligent horizontal and vertical scrolling as seen in most later jump'n runs, which means tha camera should automatically change the viewpoint so that the player has a good view onto things that are comming onto him, it should also be possible for the player to manually turn the camera to move to the left/right, the camera should also be sensitive to the speed of the player, so if he runs fast the camera should give more to see infront of the player, then when walking at normal speed, Yoshi Island demonstrates this camera behaviour quite well
* together with vertical scrolling levels of course should have both variable heights and width
* parallax scrolling backgrounds should be build out of tiles instead of plain huge jpg/png graphics, multilpe configurable background layers would be good as well (ie. gradient, parallax tilemap 1, parallax tilemap 2, playfield bg, interactive playfield, playfield fg, parallax tilemap foreground)
* the game should support sublevels, so that one can walk through pipes or doors to enter other sections of a level
* butt-jump as described on the development page should be implemented, in addition to that there would be a need for a new tiletype that reacts on a butt-jump and gets smashed
* flaping as described on the described should be implemented, it should basically provide the player with an additional 'up boost' in the down-phase of a jump and giving him more ability to land precisly.
* one-tile problem should be fixed, meaning Tux should be able to fall through small 1 tile wide holes, instead of just walking over them, this could/should be fixed by the use collision/tile shapes that are not rects, but rects with round edges or elipses
* Tux should be able to jump again/bounce while jumping on an enemy (ie. by holding down the jump button), this is standard Mario behaviour
* non-square tiles, as the ones used for sliding would be good to have, sliding itself isn't strictly necessary for Milestone2, could be suspended for Milestone3
* At least one final boss is a minimum for this release, a second mini-boss would be good as well.
* info-boxes that present a dialog-window on jump would be good to teach the player new moves and actions
* multilanguage support (via gettext or such) might be good with the number of text increasing
* ice and fireflower should get more specifc meaning and abilities