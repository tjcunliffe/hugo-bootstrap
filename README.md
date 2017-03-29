# Hugo Bootstrap boilerplate

## Dependencies

```
brew install hugo
npm install -g hugulp
```

## Development 

```
hugulp watch
```

Enable/disable Bootstrap components by commenting/uncommenting `@import` lines in `assets/styles/styles.less`.

Set Bootstrap variables in `assets/less/variables.less`.

Add custom styles by creating new `.less` files in `assets/less` and importing them **at the end** of `assets/styles/styles.less`. 
