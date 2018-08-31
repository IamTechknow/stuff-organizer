# stuff-organizer
Stuff Organizer is an Android client for [https://github.com/hzeller/stuff-org](stuff-org) instances, mainly the [Noisebridge Parts](http://parts.noisebridge.net/) website. Plans are to use Retrofit, RxJava 2, LiveData, Dagger 2, Data Binding, ViewModel, Mockito, and Glide.

## Product Specification
* [ ] Use the Single Activity architecture combined with MVVM to implement the entry, search, status, and data view
* [ ] Use Dagger for dependency Injection, integrated with ViewModel and LiveData
* [ ] For the status view, use the GridLayoutManager and SnapHelper
* [ ] Use Firebase or some API endpoint to gather a list of compatible endpoints and their API features (and allow auto-select by saving an id in SharedPreferences)
* [ ] Provide a way to add items to the database via a form POST
* [ ] Use the APIs provided by the stuff-org implementation

## User Stories
* [ ] User can choose a list of available websites (most likely just Noisebridge) that use stuff-org
* [ ] User can search for items and see the search results in real time
  * [ ] User can see images being loaded, whether a JPG, PNG, or SVG.
* [ ] User can select items to view more information and edit it within a whitelisted IP
* [ ] User can see the status of the database and view a legend of the grid color
  * [ ] The status grid itself may vary based on the screen size and density
  * [ ] User can scroll down to see the status of every 100 items
* [ ] User can touch the status grid to access the item
