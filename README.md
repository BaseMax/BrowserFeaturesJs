# BrowserFeatures
Tiny Library for browser features detection.



# How Works?
open `Example.html` file on a browser.
it's a demo file.

# How to Use?
you can access to result of detect and check from variable.

type of all variable is `bool`.

list of variables :

| Variables  | Goal |
| ------------- | ------------- |
| browser.function_generator |  |
|  browser.function_async |  |
|  browser.function_generator_async |  |
|  browser.event_target |  |
|  browser.data_transfer_item |  |
| browser.data_transfer_item_list |  |
|  browser.broad_cast_channel|  |
|  browser.viewport|  |
| browser.font |  |
|  browser.custom_element|  |
|  browser.animate|  |
| browser.svg |  |
| browser.touch |  |
| browser.webgl |  |








# Future capabilities :
- placeholder
- canvas
- querySelectorAll
- More...


# Example :
    <script type="text/javascript" src="BrowserFeatures.min.js"></script>
    <script type="text/javascript">
    window.addEventListener("load",function()
    {
        document.write("<b>" + "FunctionGenerator" + "</b> : " + browser.function_generator + "<br>");
        document.write("<b>" + "FunctionAsync" + "</b> : " + browser.function_async + "<br>");
        document.write("<b>" + "FunctionGeneratorAsync" + "</b> : " + browser.function_generator_async + "<br>");
        document.write("<b>" + "EventTarget" + "</b> : " + browser.event_target + "<br>");
        document.write("<b>" + "DataTransferItem" + "</b> : " + browser.data_transfer_item + "<br>");
        document.write("<b>" + "DataTransferItemList" + "</b> : " + browser.data_transfer_item_list + "<br>");
        document.write("<b>" + "BroadCastChannel" + "</b> : " + browser.broad_cast_channel + "<br>");
        document.write("<b>" + "ViewPort" + "</b> : " + browser.viewport + "<br>");
        document.write("<b>" + "Font" + "</b> : " + browser.font + "<br>");
        document.write("<b>" + "CustomElement" + "</b> : " + browser.custom_element + "<br>");
        document.write("<b>" + "Animate" + "</b> : " + browser.animate + "<br>");
        document.write("<b>" + "SVG" + "</b> : " + browser.svg + "<br>");
        document.write("<b>" + "Touch" + "</b> : " + browser.touch + "<br>");
        document.write("<b>" + "WebGL" + "</b> : " + browser.webgl + "<br>");
    });
    </script>

# Output of Example :

    FunctionGenerator : true
    FunctionAsync : true
    FunctionGeneratorAsync : false
    EventTarget : true
    DataTransferItem : true
    DataTransferItemList : true
    BroadCastChannel : true
    ViewPort : false
    Font : true
    CustomElement : true
    Animate : false
    SVG : true
    Touch : false
    WebGL : true

*The output may be specific to different browsers and systems.*



# License

BrowserFeatures is licensed under the [GNU General Public License](https://github.com/BaseMax/BrowserFeaturesJs/blob/master/LICENSE).
