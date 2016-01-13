# Ractive Transition-Teardown Bug

This demo contains a ractive view with a component inside a transition element.

When the element is toggled in, the component is constructed before the transition completes :)

When the element is toggled away, the component is torn down before the transition completes :(

This doesn't look very good, since fancy components are destroyed before they become hidden to the user.

Try it: https://rawgit.com/evs-chris/ractive-transition-teardown-bug/master/demo.html
