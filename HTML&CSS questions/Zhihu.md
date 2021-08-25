# Questions from Zhihu
This file contains my solutions of the HTML&CSS questions in this [website](https://zhuanlan.zhihu.com/p/158797820). All questions will be translated to English and will be answered in English.

> What is Box model? (什么是盒模型)

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. There is an image on [this link](https://www.w3schools.com/css/css_boxmodel.asp) illustrates the box model.

> Give some examples of inline elements, block elements and void elements. What is the difference between inline and block element? (行内元素有哪些？块级元素有哪些？ 空(void)元素有那些？行内元素和块级元素有什么区别？)

* Block Elements: 
  1. A block-level element always starts on a new line.
  2. A block-level element always takes up the full width available (stretches out to the left and right as far as it can).
  3. A block level element has a top and a bottom margin, whereas an inline element does not.
  
  Examples: `div`, `li`, `ol`, `p`
  
* Inline Elements:
  1. An inline element does not start on a new line.
  2. An inline element only takes up as much width as necessary.

  Examples: `i`, `a`, `img`, `input`, `label`
  
  Looking for the full list? Click [here](https://www.w3schools.com/html/html_blocks.asp)
  
* Void Elements:
  A void element is an element whose content model never allows it to have contents under any circumstances. 
  
  Examples: `br`, `img`

> Explain the differences between `src` and `href`. (简述src和href的区别)

* `src` :  attribute just embeds the resource in the current document at the location of the element's definition such as for `srcipt` tag.
* `href` : attribute specifies the location of a Web resource thus defining a link or relationship between the current element (in case of anchor `a`) or current document (in case of link) and the destination anchor or resource defined by this attribute.

For more information, check out [this page](https://stackoverflow.com/questions/3395359/difference-between-src-and-href/21549827).  

> What is CSS Hack? (什么是css Hack)

For something in your CSS file to be considered a “hack” it must apply its styles only to the browser(s) being targeted while all other browsers ignore it.

However, there is something to notice:
  1. `!important` declarations are not hacks.
  2. Vendor prefixes are not necessarily hacks. If you’re using vendor prefixes, then you’re also supplying valid accompanying standard code. That’s not a hack.

For more detailed information, please click [here](https://www.sitepoint.com/what-is-the-definition-of-a-css-hack/)

> Differences between px and em (px和em的区别)

* `px` means pixel.
* `em` means Relative to the font-size of the element (2em means 2 times the size of the current font).
* `rem` means Relative to font-size of the root element.

> HTML <!DOCTYPE> Declaration (HTML5 为什么只写<!DOCTYPE html>)

 It is an "information" to the browser about what document type to expect. In older documents (HTML 4 or XHTML), the declaration is more complicated because the declaration must refer to a DTD (Document Type Definition).
 
 > HTTP response status codes (Http的状态码有哪些)
 
There are too many codes to memorise so we can check out this [website](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) frequently.

> What happens when you type a URL in the browser and press enter? 

1. You type maps.google.com into the address bar of your browser.
2. The browser checks the cache for a DNS record to find the corresponding IP address of maps.google.com.
3. If the requested URL is not in the cache, ISP’s DNS server initiates a DNS query to find the IP address of the server that hosts maps.google.com.
4. The browser initiates a TCP connection with the server.
5. The browser sends an HTTP request to the webserver.
6. The server handles the request and sends back a response.
7. The server sends out an HTTP response.
8. The browser displays the HTML content (for HTML responses, which is the most common).

For more detailed explanation, please refer to this [website](https://medium.com/@maneesha.wijesinghe1/what-happens-when-you-type-an-url-in-the-browser-and-press-enter-bb0aa2449c1a).

