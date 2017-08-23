# Pre-work - *SimpleTodo*

*SimpleTodo* is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: Jingjing Zhang

Time spent: **16** hours spent in total

## User Stories

The following **required** functionality is completed:

* [x] User can **successfully add and remove items** from the todo list
* [x User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [x] User can **persist todo items** and retrieve them properly on app restart

The following **optional** features are implemented:

* [x] Persist the todo items [into SQLite](http://guides.codepath.com/android/Persisting-Data-to-the-Device#sqlite) instead of a text file
* [x] Improve style of the todo items in the list [using a custom adapter](http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView)
* [x] Add support for completion due dates for todo items (and display within listview item)
* [x] Use a [DialogFragment](http://guides.codepath.com/android/Using-DialogFragment) instead of new Activity for editing items
* [x] Add support for selecting the priority of each todo item (and display in listview item)
* [ ] Tweak the style improving the UI / UX, play with colors, images or backgrounds

The following **additional** features are implemented:

* [x ] List anything else that you can get done to improve the app functionality!
use menu to add item instead of normal button.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/OjWhPoP.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1:** "What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used."

**Answer:** [I am currently work on backend of web application by using java. They look familiar.  To develop layout, Android's approach is similar to web UI tools. but for develop android, it have different structure then web app development].

**Question 2:** "Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android? Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`."

**Answer:** [An adapter is an object that provides views for a list view. Whenever list view needs to draw a view at a particular list position, it gets it from the adapter. The adapter makes the view for that position and returns it. It play a important role in handling list view's display and data, isolate developer to focus on business. It pack data and the logic for creating views out of the data. The data can be a cursor or a list of objects. ConvertView`in getView`method reflects dsiplayed ListView window. ListView and ArrayAdapter combine together will minimize memory usage by recycling views.
].

## Notes

Describe any challenges encountered while building the app.
<<<<<<< HEAD

When I am trying to add more layers of dialogs ,it's easy to make mistakes.

=======
interaction between activity and dialogs has more challenges. It's easy to make mistakes when we add more layer of dialogs.
boiler plate code also confuse people to get important point.
>>>>>>> e36c6331cbd3581c15f1e4fe62ad5c5efe993b25

## License

    Copyright [2017] [Jingjing Zhang]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
