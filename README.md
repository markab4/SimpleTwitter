# Simple Twitter

Simple Twitter is an android app that allows a user to view their Twitter timeline. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).


## User Stories

### Required Stories:

- [x] User can **sign in to Twitter** using OAuth login
- [x]	User can **view tweets from their home timeline**
  - [x] User is displayed the username, name, and body for each tweet
  - [x] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
- [x] User can refresh tweets timeline by pulling down to refresh
- [x] User can **compose and post a new tweet**
- [x] User can click a “Compose” icon in the Action Bar on the top right
- [x] User can then enter a new tweet and post this to twitter
- [x] User is taken back to home timeline with **new tweet visible** in timeline
- [x] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh
- [x] User can **see a counter with total number of characters left for tweet** on compose tweet page
        **Note**: Twitter currently allows up to 280 characters in a tweet, double the previous limit of 140 characters.

### Optional Stories:

- [ ] User can view more tweets as they scroll with infinite pagination
- [ ] User can tap a tweet to display a "detailed" view of that tweet
- [ ] User can open the twitter app offline and see last loaded tweets
- [ ] On the Twitter timeline, leverage the CoordinatorLayout to apply scrolling behavior that hides / shows the toolbar.
- [ ] Replace all icon drawables and other static image assets with [vector drawables](http://guides.codepath.org/android/Drawables#vector-drawables) where appropriate.
- [ ] User can see embedded image media within the tweet detail view
- [ ] User sees an **indeterminate progress indicator** when any background or network task is happening
- [ ] User can **see embedded image media within a tweet** on list or detail view.
- [ ] User can **click a link within a tweet body** on tweet details view. The click will launch the web browser with relevant page opened.
- [ ] User can view following / followers list through any profile they view.
- [ ] User is using **"Twitter branded" colors and styles**
- [x] User can **pull down to refresh tweets timeline**
- [ ] User is using **"Twitter branded" colors and styles**
- [ ] User sees an **indeterminate progress indicator** when any background or network task is happening
- [ ] User can **select "reply" from detail view to respond to a tweet**
  - [ ] User that wrote the original tweet is **automatically "@" replied in compose**
- [ ] User can tap a tweet to **open a detailed tweet view**
  - [ ] User can **take favorite (and unfavorite) or reweet** actions on a tweet
- [ ] User can **see embedded image media within a tweet** on list or detail view.


## GIF Walkthroughs

Some walkthroughs of implemented user stories:

<img src='https://github.com/markab4/SimpleTwitter/blob/master/walkthrough1.gif?raw=true' title='GIF Walkthrough 1' width='' alt='GIF Walkthrough' />
<img src='https://github.com/markab4/SimpleTwitter/blob/master/walkthrough2.gif?raw=true' title='GIF Walkthrough 2' width='' alt='GIF Walkthrough' />
<img src='https://github.com/markab4/SimpleTwitter/blob/master/walkthrough3.gif?raw=true' title='GIF Walkthrough 3' width='' alt='GIF Walkthrough' />


## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright 2019 Mark Abramov

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.