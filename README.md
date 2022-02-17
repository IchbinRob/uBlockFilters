# uBlockFilters
List of custom filters :)

## Contents

- [All](#all)
- [Webedia (Didomi)](#webedia)
- [Twitter](#twitter)

## All
No time ? Copy/Paste this in your uBlock Filters
```
!Coucou Je suis un super ajout !
!Webedia (Didomi Paywall)
*###didomi-host
*##.didomi-popup-open:style(overflow:inherit!important)

!Twitter: scrolling logging-in
twitter.com##.r-zchlnj.r-1xcajam.r-12vffkv.r-1d2f490.r-1p0dtai.r-aqfbo4.css-1dbjc4n
twitter.com##html:style(overflow:auto !important)
twitter.com##.r-ipm5af.r-zchlnj.r-1xcajam.r-1d2f490.r-1p0dtai.r-11z020y.css-1dbjc4n
twitter.com##.r-11uj9h2.r-y5suh3.r-1dqxon3.r-16y2uox.r-kemksi.css-1dbjc4n
```

## Webedia (Didomi Paywall)
Remove Paywall screen and reactive scrollbar
```
!Webedia (Didomi Paywall)
*###didomi-host
*##.didomi-popup-open:style(overflow:inherit!important)
```

## Twitter
* Scrolling without logging-in
```
!Twitter: scrolling logging-in
twitter.com##.r-zchlnj.r-1xcajam.r-12vffkv.r-1d2f490.r-1p0dtai.r-aqfbo4.css-1dbjc4n
twitter.com##html:style(overflow:auto !important)
twitter.com##.r-ipm5af.r-zchlnj.r-1xcajam.r-1d2f490.r-1p0dtai.r-11z020y.css-1dbjc4n
twitter.com##.r-11uj9h2.r-y5suh3.r-1dqxon3.r-16y2uox.r-kemksi.css-1dbjc4n
```
