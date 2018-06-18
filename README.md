# This is an example that an UI element is added to a list (store) based on criteria from another store

If you have not setup your infrastructure for launching React Native, check the session/chapter for that (make sure you have $ create-react-native-app in your path and working).

Imagine that we will have a sort of join operation in the client side. All using local static data for now, so not yet connected to the "AJAX" world (to remote data stores).

```
create-react-native-app mySimpleClientJoinStore
cd mySimpleClientJoinStore
```

Let's install redux and the native compatibility modules:
```
npm install --save redux
npm install --save react-redux
npm install --save redux-thunk
```

(Marcio have no idea what thunk is really for at this point in writing this book)

## References

* https://medium.com/@mosesesan/tutorial-react-native-redux-boilerplate-4899f5c4f431
