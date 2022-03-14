# desc_race_A15
CVE-2021-30955 iOS 15.1.1 POC for 6GB RAM devices (A14-A15)

- Made with SwiftUI and C
- Based off of [@b1n4r1b01's](https://twitter.com/b1n4r1b01/status/1498641177498644481?cxt=HHwWgsCj6b6Nn8wpAAAA) exploit
- [Write-up](https://www.cyberkl.com/cvelist/cvedetail/24) of @realBrightiup's POC
- Improves A14-A15 support
- Tested on iPhone 13 Pro Max


![gif](src/vidforgif.gif)



# Results
- Achieves write privileges
- Panic's immediately due to A12+
<img src="src/sc.png" width="100">



generates logs in:



    /Settings/Privacy/Analytics & Improvements/Analytics Data



# Credits
- @realBrightiup
- @b1n4r1b01
- @jakeashacks

