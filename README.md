Mock crowdfunding listing page - static version
================================================

Open index.html in any browser (double-click). No server or internet needed.
Keep the img folder next to index.html.

EDITING
All project data is at the top of the <script> block in index.html, in the
PROJECTS list. Change a title, price, backers, days left etc. there and refresh.
"% funded" and the green progress bar are calculated from pledged / goal.
To change the order of the cards, reorder the entries in PROJECTS.

Display switches (CFG, just below PROJECTS):
  site_name          header wordmark (currently a neutral name, FUNDSPARK)
  show_pledged_line  the "$X pledged of $Y goal - N backers" line
  show_blurb, show_tags, show_sidebar, show_funding_rule_on_card
  image_mode         "real" or "none" (grey boxes instead of images)
  columns            cards per row (4 gives the 2x4 grid)
Each project also has staff_pick: true/false for the green "Project We Love" icon.

PLACEHOLDERS TO REPLACE (not visible in the screenshots provided)
  P07 GhostBed:      pledged, goal, backers, and full title
  P08 UniFormation:  pledged, goal, backers, and full title
  P06 WUBEN:         check the blurb wording (top of the screenshot was cut off)

NOTE FOR THE STUDY
The images for P02, P07 and P08 contain Kickstarter's "Project We Love" seal
inside the picture itself, so those three show a staff-pick cue even when
staff_pick is set to false.
