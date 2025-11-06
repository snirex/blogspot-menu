# blogspot-menu
Add menu to a blogspot site, that list all the posts in that blog.  
In order to keep the code permanently active globally - on every page load,  
follow these steps:
- [x] Log in to your Blogger dashboard.
- [x] Go to Layout.
- [x] Choose a section that appears on all pages (etc. Sidebar or Footer).
- [x] Click “Add a Gadget.”
- [x] Select the “HTML/JavaScript” option.
- [x] In the window that opens:

 - You can leave the `Title` field empty
 - In the Content field, paste your code inside a `<script>` tag, like this:

```html
<script>
(() => {
/** All your javascript code **/
})();
</script>
```
---
This script and more are published in my [Snir.blogSpot](https://snir.blogspot.com)
