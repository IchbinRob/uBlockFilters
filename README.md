# uBlockFilters
List of custom filters :)
 - link to subscribe https://raw.githubusercontent.com/IchbinRob/uBlockFilters/main/list.txt

## Contents

- [All](#all)
- [PayWalls](#paywalls)
- [Twitter](#twitter)

## All
No time ? Copy/Paste this in your uBlock Filters
```
!Webedia (Didomi Paywall)
*###didomi-host
*##body.didomi-popup-open:style(overflow:inherit!important)
!ios
*##body.didomi-popup-open-ios:style(position:initial!important)

! 2022-02-28 https://www.lachainemeteo.com
www.lachainemeteo.com##.popinBackground
www.lachainemeteo.com##html>body:style(overflow:inherit!important)

!Twitter: scrolling logging-in
twitter.com##.r-zchlnj.r-1xcajam.r-12vffkv.r-1d2f490.r-1p0dtai.r-aqfbo4.css-1dbjc4n
twitter.com##html:style(overflow:auto !important)
twitter.com##.r-ipm5af.r-zchlnj.r-1xcajam.r-1d2f490.r-1p0dtai.r-11z020y.css-1dbjc4n
twitter.com##.r-11uj9h2.r-y5suh3.r-1dqxon3.r-16y2uox.r-kemksi.css-1dbjc4n

!Twitter Subjects
twitter.com##article[data-testid="tweet"]:has(a[href*="topics"])
```

## PayWalls
Remove Paywall screen and reactive scrollbar
```
!Webedia (Didomi Paywall)
*###didomi-host
*##.didomi-popup-open:style(overflow:inherit!important)
!ios
*##.didomi-popup-open-ios:style(position:inherit!important;width:inherit!important)

! 2022-02-28 https://www.lachainemeteo.com
www.lachainemeteo.com##.popinBackground
www.lachainemeteo.com##html>body:style(overflow:inherit!important)
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
* Subjects
```
!Twitter Subjects
twitter.com##article[data-testid="tweet"]:has(a[href*="topics"])
```
