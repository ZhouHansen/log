## generals

__syntax sugar__

`bail!(X)` is equivalent to writing: `return Err(format_err!(X))`

__module dependency__

how to use a local crate: https://stackoverflow.com/questions/33025887/how-to-use-a-local-unpublished-crate

__other__

how to import mod from current crate.

__cooperation__

To evaluate a task, It's better to read the talks first.

__ownership__
When would an implementation want to take ownership of self in Rust: 

https://stackoverflow.com/questions/36531671/when-would-an-implementation-want-to-take-ownership-of-self-in-rust

Can't borrow File from &mut self (error msg: cannot move out of borrowed content):

https://stackoverflow.com/questions/28034646/cant-borrow-file-from-mut-self-error-msg-cannot-move-out-of-borrowed-content

Cannot move out of borrowed content: 
https://stackoverflow.com/questions/28158738/cannot-move-out-of-borrowed-content

## hypercore

## front-end

__workflow__
"start": "node server.js && react-scripts start" not work, replace the `&&` to `&`: https://stackoverflow.com/questions/39172536/running-npm-scripts-sequentially.

__user experience__
Use IndexedDb instead of Localstorage, it store larger and does not block the dom because it's asyncronous.Storing the application state in IndexedDB can be a great way to speed up the load time for repeat visits. The app can then sync up with any API services in the background and update the UI with new data lazily.Another good use for IndexedDB is to store user-generated content, either as a temporary store before it is uploaded to the server or as a client-side cache of remote data - or, of course, both.


__todo__

1. learn [bit](https://github.com/teambit/bit) to organize your reusable components and use them in your different app to build faster by just composing them together.

2. [choose the suitbale boilerplate](https://blog.bitsrc.io/11-react-application-boilerplates-for-2019-b49a8226ea54) 

So, I need to read the code first, then choose a boilerplate.

4. boilerplate requires: Init a store. support experimental syntax decorators. prettify . react-dom-router. history. I want a boilerplate for middle project, 36nodes/sketch/react-redux is for large project.
