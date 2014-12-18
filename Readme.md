# FAF setup tool

how to use

```
git clone https://github.com/zigfred/faf-tool.git
npm install

// edit settings.json now!!

grunt setup
```

### settings
Remove unnecessary modules, set branch names for faf, ce and pro
```
"faf-target": "amber2-tests-jsdoc-metrix",
"jrs-ce-target": "trunk",
"jrs-pro-target": "trunk",

"modules" : [
    "jrs-ui",
    "jrs-ui-pro",
    "js-sdk"
]

```