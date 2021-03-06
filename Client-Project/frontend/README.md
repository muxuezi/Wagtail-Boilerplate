# Shoggoth #

## Installation ##

1. npm install
2. npm scaffold
3. npm start

This will create a base set of containers and components in the app folder that you can work with and start the devserver at [http://localhost:7000](http://localhost:7000).


## CLI commands ##

Start the devserver:
```
npm start
```

Create a new component:
```
npm run new ComponentName
```

Create a container component:
```
npm run new ComponentName -- -c
```

Delete a component:
```
npm run delete ComponentName
```

Delete a container component:
```
npm run delete ComponentName -- c
```

Run tests:
```
npm test
```

Update test snapshots (if added):
```
npm test -- -u
```

Scaffold an example project:
```
npm run scaffold
```

Scaffold an empty project:
```
npm run scaffold -- -e
```

Code formatting via prettier:
```
npm run fixcode
```

To only test that all files are formated correct:
```
npm run fixcode:test
```
