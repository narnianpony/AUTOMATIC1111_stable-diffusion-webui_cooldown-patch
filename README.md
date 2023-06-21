# AUTOMATIC1111_stable-diffusion-webui_cooldown-patch
A patch to add a cooldown feature to Automatic1111's stable diffusion web ui "Generate forever" button



## How to use

- After installing it, now when you right-click the Generate button you will see the "Generate forever with cooldown" option
![Contextual menu](https://i.ibb.co/BntR0zP/1.png)
 
- Clicking it will show a prompt to introduce the number of seconds of cooldown, use 0 to avoid having a cooldown
![Seconds prompt](https://i.ibb.co/StDqJXG/2.png)
 
- And that's it. Now it will wait that amount of seconds between each image generation and display the counter in the button
![Cooldown](https://i.ibb.co/pyKLsKm/3.gif)


## How to install
### Apply Patch:
Download cooldown.patch to your stable-diffusion-webui and apply the patch in the code using
```
git apply cooldown.patch
```

### Replace file:
If you are not comfortable dealing with git, just download contextMenus.js and replace the file in stable-diffusion-webui/javascript
