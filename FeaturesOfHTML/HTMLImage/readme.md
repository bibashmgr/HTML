> # HTML Image tag:

The HTML `<img>` tag is used to embed an image in a web page. The `<img>` tag is empty, it contains attributes only, and does not have a closing tag.
__Synatx:__
```html
<img src="filepath" alt="message" />
```

The <img> tag has two required attributes:

- src :- Specifies the path to the image
- alt :- Specifies an alternate text for the image

> # Image Maps:

The HTML `<map>` tag defines an image map. An image map is an image with clickable areas. The areas are defined with one or more `<area>` tags.
__Synatx:__
```html
<img src="filepath" alt="message" usemap="#imageName" />
<map name="imageName">
    <area shape="" coords="" alt="msg" href="url"/>
</map>
```
__POINTS TO BE REMEMBERED:__
- The image is inserted using the `<img>` tag. The only difference from other images is that you must add a usemap attribute.The usemap value starts with a hash tag "`#`" followed by the name of the image map, and is used to create a relationship between the image and the image map.
- Then, add a `<map>` element.The `<map>` element is used to create an image map, and is linked to the image by using the required name attribute.The name attribute must have the same value as the `<img>`'s usemap attribute .
- Then, add the clickable areas.A clickable area is defined using an `<area>` element.The `<area>` tag has following attributes:
    - __shape attribute:__
        
        You must define the shape of the clickable area, and you can choose one of these values:
        - rect :- defines a rectangular region
        - circle :- defines a circular region
        - poly :- defines a polygonal region
        - default :- defines the entire region

    - __coords attribute:__

        You must also define some coordinates to be able to place the clickable area onto the image.
        - The coordinates for shape="rect" come in pairs, one pair for the x-axis and one pair for the y-axis.
        - To add a shape="circle" area, first locate the coordinates of the center of the circle.Then specify the radius of the circle.
        - The shape="poly" contains several coordinate points, which creates a shape formed with straight lines (a polygon).We have to find the x and y coordinates for all edges of the croissant.
        - If we dont use any shape attribute then the browser automatically defines the entire image as area.That is called default value in shape attributes.Here we dont have to define coords attribute ,since the default value select the entire image.

