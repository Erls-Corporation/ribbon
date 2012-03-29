#Ui Parade’s CSS Ribbon on a diet  


I'm an assiduous follower of [UI Parade](http://www.uiparade.com/) and I'm a big fan of their live tools, especially the [Ribbon builder](http://www.uiparade.com/wp-content/themes/artiste/live-tools/ribbon-builder.html).  
It looks amazing and we can costumize the Ribbon's width, end size, stitching & shadows, colors, etc.  
Probably because of so many costumizing options, the generated HTML is long and it doesn't look right to me: 

&lt;div class="ribbon"&gt;
&lt;div class="ribbon-stitches-top"&gt;&lt;/div&gt;
&lt;strong class="ribbon-content"&gt;&lt;h1&gt;&lt;/h1&gt;&lt;/strong&gt;
&lt;div class="ribbon-stitches-bottom"&gt;&lt;/div&gt;
&lt;/div&gt;  


I'm a bit "clean markup" psycho so I had to change it.
In this experiment I managed to achieve the same looks but with the following markup:

&lt;h1 class="ribbon"&gt;&lt;strong&gt;&lt;/strong&gt;&lt;/h1&gt;  



See how it looks [now](http://luis-almeida.github.com/ribbon/) with the new markup.

