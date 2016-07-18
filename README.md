# The best practices of class-component.js programming

- A template is not a view.
- Each dom object is a view.
- Use dom hierarchy as Presenters' hierarchy
- Use dom event bubbling when a presenter want to pass data to its parents.
- Query on dom when the presenter want to pass data to its children.
- See dom as passive view. Pass information to views from the presenters.
- Models are implemented somewhere isolated from dom tree.
