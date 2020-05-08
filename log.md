# 100 Days Of Code - Log

### Day 1: Apr 29, 2020 

**Today's Progress**: 
1. Building on already held basic knowledge of ReactJS, started with dev of YT Browser React App featuring:
	a. Search Videos using YT Api
	b. Render List of Videos fetched from YT Api
	c. Show/ Play a YT video on browser
2.	1a and 1b are done.

**Thoughts:**
1. Hands on react core concepts like controlled components/ tags, 
2. Struggled with revisiting concepts of callbacks/ props and implementation of axios method for YT API
3. Progress is slow but steady, hoping to increase pace with time. 

**Link to work:** [YT Videos Browser App](https://github.com/pseudogeek7/reactive-tuts/tree/master/videos)


### Day 2: Apr 30, 2020 

**Today's Progress**: 
1. Continuing on already built YT Browser App, added function of single video rendering/ playing.
	a.	Video details (Src, Title) etc was passed from child component to parent component using props/ callbacks
	b.	Conditional Rendering was achieved using onClick arrow function.
	c.	Creation of new component to render/ play a single video using iframe
	d.	Styling UI to display Video Player and List, side by side with the help Semantic UI Grid Component
	e.	Default Video selection & rendering using componentDidMount method
2.	Fixing different issues/ warning by
	a.	adding alt property to img
	b.	adding a title to iframe


**Thoughts:**
1. Implementation of childToParent Callbacks, Conditional Rendering using onClick, iframes and semantic-ui gridview
2. Need to work on utilization of componentDidMount and other similar methods

**Link to work:** [YT Videos Browser App](https://github.com/pseudogeek7/reactive-tuts/tree/master/videos)


### Day 3: May 01, 2020 

**Today's Progress**: 
1. Learnt about Redux Basics
	a.	Lifecycle
	b.	Diff components like action creator, action, dispatch, reducers and state
	c.	understanding through analogy with insurance company example
2.	Implementation of stand-alone small redux app analogous to insurance company, using codepen
	a. hands-on over writing action-creators, reducers and managing all components through redux store,
		combineReducers and getState
	b. understanding of js filter function and es6 syntax to return a brand-new array
**Thoughts:**
1. Have to work on it further to remember the concepts and solidfy foundation of redux and its implementation
2. Looking forward to use redux with react application

**Link to work:** [Redux App - Insurance Company](https://codepen.io/pseudgeek7/pen/dyYVeLN)

### Day 4: May 02, 2020 

**Today's Progress**: 
Started learning abt integ of reactjs & redux - dev a simple app to implement action creators, provider, connector & reducers
**Thoughts:**
sruggling with grasping the whole workflow, will work tmrw to solidfy foundation

**Link to work:** [Simple React-Redux App - Insurance Company](https://github.com/pseudogeek7/reactive-tuts/tree/master/songs)

### Day 5: May 03, 2020 

**Today's Progress**: 
1. Revisited Redux & React-Redux concepts. Learnt in detail abt async actions with redux & use of thunk middleware. 
2.	Developing a small app for fetching dummy posts by using Redux & Thunk. 
**Thoughts:**
Everything making some sense with time.. will keep working on it.

**Link to work:** [Simple React-Redux-Thunk App - Blog](https://github.com/pseudogeek7/reactive-tuts/tree/master/blog)

### Day 6: May 04, 2020 

**Today's Progress**: 
1.	Learnt Key Reducer Rules
	a.	must not return undefined object
	b.	only produce data/ state by utilizing previous state & action (required to define state value initially)
	c.	must not reach any external source to decide what to return
	d.	must not mutate its state argument; rather return a brand new array (otherwise react app will not re-render)
2.	Learnt about Javascript mutations, comparison op & switch statement
3.	Implementation of Redux Reducer (fetching dummy blog posts from external API) fol learnt rules.

**Thoughts:**
my life is going on..need to find a lot of time practice..

**Link to work:** [Simple React-Redux-Thunk App - Blog](https://github.com/pseudogeek7/reactive-tuts/tree/master/blog)


### Day 8: May 06, 2020 

**Today's Progress**: 
Refactored code to move logic to mapStateToProps func 4 reusability, learnt/tried #lodash #memoize method 2 solve overfetchng API issue; started working on other soln due 2 limitations
**Thoughts:**
busy day, couldnt do much; memoize & js syntax sucks

**Link to work:** [Simple React-Redux-Thunk App - Blog](https://github.com/pseudogeek7/reactive-tuts/tree/master/blog)


### Day 9: May 07, 2020 

**Today's Progress**: 
wrote new func to deal with API overfetch issue - did nested actioncreator calls, #lodash map, iterator, uniq & chain func 2 fetch unique userIds agst all posts.. code refactoring agst new funcs
**Thoughts:**
react-redux needs alot of practice to grasp over all - challenge accepted

**Link to work:** [Simple React-Redux-Thunk App - Blog](https://github.com/pseudogeek7/reactive-tuts/tree/master/blog)