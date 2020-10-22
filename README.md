# My Maps 

## *Cortney Weintz*

**My Maps** displays a list of maps, each of which show user-defined markers with a title, description, and location. The user can also create a new map. 

Time spent: **6.5** hours spent in total

## Functionality 

The following **required** functionality is completed:

* [X] The list of map titles is displayed.
* [X] After tapping on a map title, the associated markers in the map are shown.
* [X] The user is able to create a new map.

The following **extensions** are implemented:

* [X] When a map marker is created, the pin is animated.
* [X] Custom colors palette selected

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://media.giphy.com/media/16jTosGGfr3UIFwyco/giphy.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [GIPHY](https://giphy.com/).

## Notes

In milestone 4, when trying to save a user-created map, I encountered an error with my call to intent.getStringExtra(EXTRA_MAP_TITLE) within the UserMap constructor. The error said that UserMap was expecting a 'String' but getting a 'String?' from getStringExtra(). To fix this, I expanded the construction to two lines and used the toString() method on getStringExtra() to save it to a variable 'title' and then made the constructor call to UserMap(title, places).

## License

    Copyright [2020] [Cortney Weintz]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
