# jquery-font-size-event
>


## Description

Method to detect change in font-size of the document

## Installation
### bower
`bower install https://github.com/FCOO/jquery-font-size-event.git --save`

## Demo
http://FCOO.github.io/jquery-font-size-event/demo/ 

## Usage

    $.onFontSizeChanged( handler, context );

    /*
    handle = function( event, fontSize );
    fontSize = { 
        fontSizeRem    : 1,         //Always 1 
        fontSizePx     : [number],  //font-size in px,
        fontSizePercent: [number]   //font-size in %. Based on $.DEFAULT_BROWSER_FONT_SIZE
    }
    */

    //Default font-size for the browser is set in $.DEFAULT_BROWSER_FONT_SIZE. Default value is 16px
    $.DEFAULT_BROWSER_FONT_SIZE = '16px';



## Copyright and License
This plugin is licensed under the [MIT license](https://github.com/FCOO/jquery-font-size-event/LICENSE).

Copyright (c) 2017 [FCOO](https://github.com/FCOO)

## Contact information

Niels Holt nho@fcoo.dk

