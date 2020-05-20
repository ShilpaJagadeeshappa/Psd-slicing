# Psd-slicing
On the journey from Psd to HTML conversion for an psd file. A part of it, that is Psd slicing can be done by this method with psd-tools library.
# Manual steps involved in Psd to HTML conversion
## STEP 1 – HAVE ALL THE KEY COMPONENTS OF A PSD DESIGN
To begin with the conversion process, you need to have a PSD design. Make sure that it is created in Photoshop Layers as this will help to select the right things at the right time without having to use the Photoshop slice tool.Build an eye catching website design that has all the elements like Header, Footer, Navigation Bar, Sidebar, etc. placed sequentially. Once you have a PSD website with all its essential components, you are ready to convert it to HTML.

## STEP 2 – KNOW YOUR TOOLS
Converting a website design from PSD to HTML requires clear understanding and expertise in front end development. This encompasses, but is not limited to, HTML, CSS, JQuery and JavaScript. PSD to HTML conversion is not just about smattering HTML, adding a dash of CSS, and a bit of JavaScript for good measure. Converting modern web pages is critical and demands extensive knowledge of not just the markup language (HTML) and styling (CSS), but also the key features of a web page, including JQuery and JavaScript. Moreover, website design for mobiles and tablets is the call of the age and hence, those factors also need to be considered while translating a PSD design to HTML.

## STEP 3 – GETTING THE PSD FILES READY FOR CONVERSION
Once you are ready with your PSD design and conversion tools, you will have to create a directory folder that will include /images directory for images and /jsdirectory for JavaScript.

## STEP 4 – START WITH SIMPLE STARTER LAYOUT
To begin with building the HTML layout, it is important to analyze the design first by considering the Photoshop layout and identifying the sections that are unique. Some of the important components to consider are the background, header, slides, Service, Media, widget, Client, and footer. Pay attention when you name the id or class as these are the names that you will use to markup the HTML. Now, based on these, you create an HTML layout.

## STEP 5 – WORK ON EACH SECTION ELABORATELY TO MARK UP THE HTML
Next, to mark up the HTML, you will have to focus more on individual sections like the Header, Slider, Service, Media, Background, Widget, Client, and Footer. Mark up the HTML elements that can be identified in each section and focus on them elaborately. Style the Navigation with a height, width and gradient, and you can apply Cascading Styling Sheet here.

Your HTML design is ready! PSD to HTML conversion is intricate, especially if you are working on the complex HTML5/CSS3 standards.Hire a professional PSD to HTML conversion company like Satvik Infotech who have the knowledge and experience to create visually appealing, eye catching, responsive HTML website designs.

### Note: To play with different designs or to make interactive websites for different screens rendering on various devices we need to pitch into responsive coding.

## Lets jump into the code to convert psd to slices

### Run pip install psd-tools

Note:
In order to extract images from 32bit PSD files PIL/Pillow must be built with LITTLECMS or LITTLECMS2 support.

## Code
```
from psd_tools import PSDImage

psd = PSDImage.open('example.psd')
psd.composite().save('example.png')

for layer in psd:
    print(layer)
    layer_image = layer.composite()
    layer_image.save('%s.png' % layer.name)
  ```
  
  Refer the below output:
  
 ![alt text](http://url/to/img.png)



