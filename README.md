# ember-reset-scroll

A very simple mixin to componentize the code found in [this cookbook](http://guides.emberjs.com/v1.10.0/cookbook/user_interface_and_interaction/resetting_scroll_on_route_changes/). Not the most useful thing at the moment, but ensures that should this pattern ever change, updating the mixin will solve the issue.

## Installation

```
$ ember install ember-reset-scroll
```

## Usage

```javascript
// In a route file
import ResetScroll from 'ember-reset-scroll/mixins/reset-scroll';

export default Ember.Route.extend(ResetScroll, {
  // The rest of your route.
});
```
