# GS Unblocker
A bookmarklet to unblock searches on Google without rewrites!

### NOTE
#### This is only fully confirmed to work with Securly and only unblocks Google searches.

### Instructions

**1** - Install uBlock origin or adBlock Plus (experimental - see discussion [#1081](https://github.com/3kh0/ext-remover/discussions/1081) for more info)

**2** - For uBlock Origin, follow the instructions in the ext-remover README [here](https://github.com/3kh0/ext-remover?tab=readme-ov-file#ublock-run-run-code-on-pages)

**3** - Once you have set up code execution on your adblocker, go to [Google](https://www.google.com)

**4** - Press **Ctrl**+**Alt**+**~** and run this bookmarklet:

```javascript
document.querySelector('iframe').src = 'https://www.google.com'
```

**5** - Once that is done, click on the apps button (the profile button has been confirmed NOT to work)

**6** - You should see an iframe displaying Google's homepage. Search and enjoy! If you are having any issues, feel free to submit them.
