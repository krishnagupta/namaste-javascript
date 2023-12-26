any js program is run
global execution context is created
code will run line by line in GEC
call stack is inside JS engine
web api - setTimeout, DOM api, fetch, localstorage, console, location through window object browser give access to JS engine
event loop - check callback queue and push in call stack, monitor call stack and queue
setTimeout vs Fetch ?
-> microtask queue which has higher priority than callback queue
network call go to microtask queue
promises and mutation observer(DOM update) callback fn goes inside microtask queue
Starvation of callback queue bcz of long waiting due to microtask queue
