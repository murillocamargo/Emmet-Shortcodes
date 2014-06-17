## wordpress sidebar widget

> section.widget>(header>h2)+div.inner-widget    
> section.widget>(header>h2)+div.inner-widget+footer

## wordpress main-content

> div#main-content.container>.row>article.the_single>((header.the_title>h2)+(.the_content>p*2>lorem50))|c   

## Bootstrap Header padrão ( Logo - Menu )

> header#header>.container>.row>(.col-md-4>.logo>h1>a>img)+(.col-md-8>nav#main-nav>ul>(li>a)*7)|c

## Slider padrão somente imagens

> (#slider-container>.container>.row>#slider>(.cycle-prev.left+.cycle-next.right)+(a.item.image>img.thumbnail-slider)+.cycle-pager)+.clearfix|c
