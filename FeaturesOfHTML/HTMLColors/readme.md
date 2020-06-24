> # HTML Colors:

HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.

- Color Names:

    In HTML, a color can be specified by using a color name such as Red , Orange , Black and soon.

- Color Values:

    In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.

    1. RGB Values:

        An RGB color value is specified with: rgb(red, green, blue).Each parameter (red, green, and blue) defines the intensity of the color as an integer between `0` and `255`.
        
        __Syntax:__
        ```html
        rgb(0,0,0)

        rgb(255,255,255)
        ```

    2. HEX Values:
    
        A hexadecimal color is specified with: `#RRGGBB`. `RR` (red), `GG` (green) and `BB` (blue) are hexadecimal integers between `00` and `FF` specifying the intensity of the color.
        
        __Syntax:__
        ```html
        #ffffff

        #000000
        ```


    3. HSL Values:

        HSL stands for hue, saturation, and lightness.HSL color values are specified with: hsl(hue, saturation, lightness).
        - Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, 240 is blue.
        - Saturation is a percentage value; 0% means a shade of gray and 100% is the full color.
        - Lightness is also a percentage; 0% is black, 100% is white.

        __Syntax:__
        ```html
        hsl(0,0%,0%)

        hsl(360,100%,100%)
        ```

    4. RGBA Values:
        The RGBA values is similar to RGB values but it has an Alpha channel.Alpha channel indicates the opacity which ranges from 0 to 1.
        
        __Syntax:__
        ```html
        rgb(0,0,0,0)

        rgb(255,255,255,1)
        ```

    5. HSLA Values:
        The HSLA values is similar to HSL values but it has an Alpha channel.Alpha channel indicates the opacity which ranges from 0 to 1.

        __Syntax:__
        ```html
        hsl(0,0%,0%,0)

        hsl(360,100%,100%,1)
        ```


