
## react-reconciler
- function components
- class components
- props, state
- effects, lifecycles
- key, ref, context
- React.lazy, error boundaries
- concurrent mode, and Suspense


# reconciler modes

### mutation mode

* react native
 - view = createView()
 updateView(view, {color: 'red'})

* web
div = document.createElement('div')
div.style.color = 'red'

- update view X to be red
- create a new view
- add that view a child of view Y

### persistent mode

* native
view = createView()
view = cloneView(view, {color: 'red'})

