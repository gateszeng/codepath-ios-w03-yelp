# Project 3 - *Name of App Here*

**Holler** is a Yelp search app using the [Yelp API](http://www.yelp.com/developers/documentation/v2/search_api).

Time spent: **3.5** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] Table rows for search results should be dynamic height according to the content height.
- [x] Custom cells should have the proper Auto Layout constraints.
- [x] Search bar should be in the navigation bar (doesn't have to expand to show location like the real Yelp app does).

The following **optional** features are implemented:

- [ ] Search results page
   - [ ] Infinite scroll for restaurant results.
   - [ ] Implement map view of restaurant results.
- [ ] Implement the restaurant detail page.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!
- [x] Set the color of the navigation bar and added cancel button

Please list two areas of the assignment you'd like to **discuss further with your peers** during the next class (examples include better ways to implement something, how to extend your app in certain ways, etc):

1. I would like to talk about good procedures to set constraints.
2. I would like to discuss the difference between content hugging priority and content compression priority.

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/gylmbha.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.
I faced a compiler error that said "Class 'BusinessCell' has no initializers". I had never faced this compiler error before and it took me a while to figure out that the business object that we created must be force unwrapped.
Additionally, there was an inconsistancy between the video and this version of iOS, since we did not need to implement 'preferredMaxLayoutWidth' and 'layoutSubviews' anymore.

## License

    Copyright [2017] [Gates Zeng]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
