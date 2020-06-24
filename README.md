# Project 1 - *Tasks*

**Tasks** is an android app that allows building a todo list and basic todo items, with management functionality including adding new items, editing an existing item, and deleting an existing item.

Submitted by: **James Talavera**

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is completed:

* [X] User can **view a list of todo items**
* [X] User can **successfully add and remove items** from the todo list
* [X] User's **list of items persisted** upon modification and and retrieved properly on app restart

The following **stretch** features are implemented:

* [X] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='Kapture 2020-06-23 at 17.42.35.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Kap](https://getkap.co/).

## Notes

Due to this being my first time doing Android development, there was a learning curve that I had to overcome in terms
of comprehending the overall structure and capabilities of an Android app. One issue that I did run into was implementing the ability
to save the content of the todo list. The FileUtils object was not recognizing the readLines method. 'Hung P' commented on the Youtube
 video to change the given import statement to 'import org.apache.commons.io.FileUtils;' which finally worked.

## License

    Copyright [2020] [CodePath]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
