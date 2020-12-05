## Display Biography - CLI :smiley: :fire: :heart_eyes: :snowflake:

#### `#!` - shebang
    - It should be written in the first line of the index.js file to run a file without `node` command

```
#!/usr/bin/env node
```

#### To run a cli with differenct name - ```package.json```

```
"bin": {
    "guna": "index.js"
  },
```
#### Need to check you are logged in with npm

```
$ npm login - followed by credentials

$ npm whoami - To verify
```

#### Publish package

``` 
$ npm link 
```
``` 
$ npm publish 
```

#### Throws 403 error if package name already exist in npm so try changing the package name

- Stack Overflow Solution](https://stackoverflow.com/questions/54950544/npm-publish-registry-403-forbidden-you-dont-have-permission-to-publish#)

