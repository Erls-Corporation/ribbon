#Ui Parade’s CSS Ribbon on a diet  


I'm an assiduous follower of [UI Parade](http://www.uiparade.com/) and I'm a big fan of their live tools, especially the [Ribbon builder](http://www.uiparade.com/wp-content/themes/artiste/live-tools/ribbon-builder.html).  
It looks amazing and we can costumize the Ribbon's width, end size, stitching & shadows, colors, etc.  
Probably because of so many costumizing options, the generated HTML is long and it doesn't look right to me: 

<div class="ribbon">
<div class="ribbon-stitches-top"></div>
<strong class="ribbon-content"><h1>A Pure CSS Ribbon</h1></strong>
<div class="ribbon-stitches-bottom"></div>
</div>  


I'm a bit "clean markup" psycho so I had to change it.
In this experiment I managed to achieve the same looks but with the following markup:

<h1 class="ribbon"><strong>Ui Parade's CSS Ribbon on a diet</strong></h1>  

