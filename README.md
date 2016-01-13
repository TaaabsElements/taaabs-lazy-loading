# TaaabsBehaviors.LazyLoading

`TaaabsBehaviors.LazyLoading` is a Polymer Behavior that is delaying the instanciation of Widgets.

The purpose of this behavior is to handle Widgets using D3.js because
those widgets need some values (displayed width,...) that are accessibles
only when the browser have done the rendering of the Polymer Custom Element.

There is some logic to instanciate the widget only is he is selected.
If you don't want this, for now you can set selected and pageNum to 0. 

@polymerBehavior
