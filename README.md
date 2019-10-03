# VueJSCheatSheet
A repo used for reference of various VueJS syntax.

## VueX

### StateMutations

**StoreJS state Mutation example:**

`functionName(state, optionalArg) {
  state.stateName = optionalArg;
}`

**Mutating State from Component or View:**

`this.$store.commit('mutationFunctionName', optionalParam)`

## Vue Router

**In Code Routing**

`this.$router.push('/routeName')`

**In Template Routing**

`to="routeName"`

## Random

**Timed Actions**

`setTimeout(() => (doSomethingHere), timeInMS)`
