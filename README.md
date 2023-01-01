# "Clone" Disney+ Studios Section 
In this project I've made a "clone" of the Studios Section from Disney+.

<hr>

### Faced Challanges + Fixes
<u>1. Overlapping an image on a video on hover:</u>
When overlapping the used image (= the logo of a studio) with the video, i used: `position: relative/absolute` + `z-index` to be able to overlap the image in on the video. 

The problem I faced was that I still couldn't see the image. But I fixed this by setting `display: block`; 

<br>

<u>2. Video (.mp4) not playing on hover:</u>
When using the video tag / element in HTML and I applied the `loop, autoplay, playsinline` properties. The only thing was, that the video wouldn't play (or just randomly), but eventually I found out that if you use the `muted` property on the video tag / element it will play properly! 

The `muted` needs to be used, because of in-build security from browsers to prevent a video to be played out loud when a user visits a specific page (where this tag / element is used).
- Source: https://stackoverflow.com/questions/69427603/autoplay-on-video-is-not-working-after-refreshing-page

___
### Result
https://user-images.githubusercontent.com/70898181/210183256-07b418f1-cc0b-49d0-b93b-f8ce7d9befba.mp4
P.S: If you want to see the full hover states of the Disney+ Studios Section, make sure to fork this project!
