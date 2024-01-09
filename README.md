# jellyfin-themes-beauty

import css

```css
@import url('https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/db332985684795c01abc90c2262dce42ccc41278/jellyfin_style.css');

``` 

## background Images
halloween Desktop
- https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/dfad914984ec2200808626501ac6c9fa3f2da470/images/halloween-desktop.jpg

halloween Smartphone
- https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/dfad914984ec2200808626501ac6c9fa3f2da470/images/halloween-mobile.jpg

galaxy Desktop
- https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/dfad914984ec2200808626501ac6c9fa3f2da470/images/galaxy-desktop.jpg

galaxy Smartphone
- https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/dfad914984ec2200808626501ac6c9fa3f2da470/images/galaxy-mobile.jpg

mountain Desktop
- https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/dfad914984ec2200808626501ac6c9fa3f2da470/images/mountain-desktop.jpg

mountain Smartphone
- https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/dfad914984ec2200808626501ac6c9fa3f2da470/images/mountain-mobile.jpg

nature Desktop
- https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/dfad914984ec2200808626501ac6c9fa3f2da470/images/nature-desktop.jpg

nature Smartphone
- https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/dfad914984ec2200808626501ac6c9fa3f2da470/images/nature-mobile.jpg

noel Desktop
- https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/dfad914984ec2200808626501ac6c9fa3f2da470/images/noel-desktop.jpg

noel Smartphone
- https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/dfad914984ec2200808626501ac6c9fa3f2da470/images/noel-mobile.jpg

Edit this code for change background image

```css
:root {
  --accent: 229, 9, 20;
  --bg_item: rgba(0, 0, 0, 0.5);
  --rounding: 10px;
  --bkg_img_desktop: "https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/dfad914984ec2200808626501ac6c9fa3f2da470/images/galaxy-desktop.jpg";
  --bkg_img_mobile: "https://rawcdn.githack.com/kalibrado/jellyfin-themes-beauty/dfad914984ec2200808626501ac6c9fa3f2da470/images/galaxy-mobile.jpg";
}
```


For showing msg user edit this code 

```css
/* NOTIFICATION USER*/
.skinHeader::before {
  /* Add text to notifie  */
  content: "test notification";
  color: red;
  font-weight: bold;
  position: static;
  width: 100%;
  text-align: center;
  /* uncoment this line to show notification and set time default is 7s pop notification */
  animation: fadeOut 7s linear forwards;
}
```
