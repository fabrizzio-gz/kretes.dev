# Common Problems

## Outdated `node-gyp`

If you're getting an error similar to the following one:

```
TypeError: '>=' not supported between instances of 'tuple' and 'str'
```

it means that the `node-gyp` is outdated. Run the following commands to solve it:

```
npm explore npm -g -- npm install node-gyp@latest
npm explore npm -g -- npm explore npm-lifecycle -- npm install node-gyp@latest
```
