## How to set displayContext Name

    const UserContext = React.createContext()
    UserContext.displayName = 'UserContext'
***
## Why ?

React DevTools just display as Context.Provider and Context.Consumer. When we have multiple context then using `displayName` we can easily identfy context in DevTools.

**Author**    
_iLapani_
