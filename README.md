# The best practices of class-component.js programming

- A template is not a view.
- A dom object is a view.
- Use Model-View-Presenter pattern.
- Use dom hierarchy as Presenters' hierarchy.
- Use dom event bubbling when a presenter want to pass data to its parents.
- Query on dom when the presenter want to pass data to its children.
- See dom as passive view. Pass information to views from the presenters.
- Presenter should manupilate the view if it belongs directly to the presenter.
- Presenter should send command the children views if the change doesn't belongs to the Presenter.
- Models are implemented somewhere isolated from dom tree.
- Application state should be stored in presenter.
