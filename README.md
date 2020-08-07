# AVC2HEVC-detection-network
The project presents a deep network scheme to detect transcoding from AVC to HEVC.

The source code will be open after the paper is accepted

As an additional supplement to the manuscript, the experimental contents of the five training\test sets in content-unaware detection are listed as follows

cif videos
round1
train: akiyo, bridge_close, bus,  coastguard, crew, flower, foreman, husky, mad, news, paris, silent, students, tempete
test: bowing, bridge_far, city, container, deadline, football, hall, highway, mobile, pamphlet, sign_irene, soccer, stefan, waterfall

round2
train: akiyo, bridge_far, bus,  coastguard, container,  foreman, highway, husky, mobile, news, paris, silent, sign_irene, tempete
test: bowing,  bridge_close, city, crew, deadline, flower, football, hall, mad, pamphlet, soccer, stefan,students, waterfall

round3
train:  bowing, bridge_far, bus,   container, deadline, hall, highway, husky, mobile, news,pamphlet, paris, silent, waterfall
test: akiyo,  bridge_close, city,coastguard, crew,  flower, football,foreman, mad,  soccer, sign_irene, stefan,students, tempete

round4
train:  bowing, bridge_far,city, coastguard,  container, deadline, football, hall, husky, mad, mobile, pamphlet,  tempete, waterfall
test: akiyo,  bridge_close,  bus, crew, flower, foreman, highway, news, soccer, sign_irene,silent, stefan,students, paris

round5
train:  bowing, bridge_close, city,   container, deadline, flower, foreman, hall,highway, news,  pamphlet, soccer,   tempete, waterfall
test:  akiyo, bridge_far, bus, crew, coastguard,  football,  husky,  mad, mobile, sign_irene, silent, stefan,students, paris



720P videos
partA: mobcal, shields_ter, stockholm, Johnny, KristenAndSara, park_joy, vidyo3
partB: parkrun_ter, ducks_take_off, FourPeople, in_to_tree, old_town_cross, vidyo1, vidyo4

round1
train: mobcal, shields, stockholm, FourPeople, ducks_take_off, old_town_cross, vidyo4
test: parkrun, Johnny, KristenAndSara, in_to_tree, park_joy, vidyo1, vidyo3

round2
train: parkrun, stockholm, Johnny, KristenAndSara, in_to_tree, park_joy, vidyo1
test: mobcal, shields, FourPeople, ducks_take_off, old_town_cross, vidyo3, vidyo4

round3
train: shields, FourPeople, KristenAndSara, ducks_take_off, park_joy, old_town_cross, vidyo3
test: mobcal, parkrun, stockholm, Johnny, in_to_tree,  vidyo1, vidyo4

round4
train: mobcal, parkrun, FourPeople, Johnny, KristenAndSara, old_town_cross, vidyo1
test: shields, stockholm, ducks_take_off, in_to_tree, park_joy, vidyo3, vidyo4

round5
train: parkrun, shields, stockholm, ducks_take_off, park_joy, vidyo3, vidyo4
test: mobcal, FourPeople, Johnny, KristenAndSara, in_to_tree, old_town_cross, vidyo1
