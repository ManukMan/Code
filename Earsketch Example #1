

from earsketch import *

init()
setTempo(105)

Horn1 = Y22_HORNS_1
Horn2 = Y22_HORNS_2

fitMedia(Horn1, 3, 1, 29)
fitMedia(Horn2, 4, 1, 29)

synth = Y12_BRASS_1
drums = YG_HOUSE_DRUMS_1
drums1 = CIARA_MELANIN_DRUMBEAT_1
beat1 = "00-00+++00--0-0-"
beat2 = "0+-0++000+00-0-0"
beat3 = "-0-0++0-0++0-00-"

setEffect(1, VOLUME, GAIN, -60, 1, 0, 20)
setEffect(2, VOLUME, GAIN, -40, 1, 0, 20)

for measure in range(1,29):
   makeBeat(synth, 1, measure, beat1)
   makeBeat(drums, 2, measure, beat2)
   makeBeat(drums1, 5, measure, beat3)

finish()
