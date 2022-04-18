# Sus Image Bot
This bot is a example for using canvas to make a sus image.
![](https://cdn.discordapp.com/attachments/885884843374809118/965735161452974120/sus.png)

Time: [![wakatime](https://wakatime.com/badge/user/6dcad35f-5e14-44f1-8e50-62062cfd7011/project/1e761a71-9bd9-4f0c-b9db-34c9c1dda71f.svg)](https://wakatime.com/@Funty) *yes i'm new to canvas*  
Language: JavaScript/Node.js

### Before you start:
Install the used node modules with `npm i canvas discord.js`

## function arguments:
ALL arguments except the [imageURL](#imageURL) are optional but they can personalize the result!<br><br>

Example:  
```js
const image = await createSusImage(message.author.displayAvatarURL({format: 'png'}), size = {x: 128, y: 71});
```

[function arguments:](#function-arguments)
  * [imageURL](#imageURL)
  * [size](#size)

### <ins>imageURL</ins>
**Name:** imageURL<br>
**Type:** String<br>
**Description:** URL of the image that should be turned into these eyes.

### <ins>size</ins>
**Name:** size<br>
**Type:** Object<br>
**Default:** ``{x: 128, y: 71}``

| Sub-Option | Type   | Description                                  | Default (value if you don't give any) |
| ---------- | ------ | -------------------------------------------- | ------------------------------------- |
| x          | Number | the width of the image, specified in pixels  | 128                                   |
| y          | Number | the height of the image, specified in pixels | 71                                    |