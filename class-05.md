# HTML - Images

**Using images in your website is important to make it engaging and attractive.  
When choosing images you should consider the folowing things:**

1. the images are *relevent* and connected to the topic and idea of your website/webpage
2. the images communicate information about your website topics
3. the images express the right mood of your website
4. the images are instantly recognisable
5. the images fit the cilor palette

**When building your website, it's a good practice to create a folder for all the images the site uses.  
keeping your images in a separate folder will help you understand how the website is organized as the website grows.  
and you may also add subfolders to the images folder to sort related images.**

## Adding Images Using HTML

- images can be added into a webpage using `<img>` element.
- ` <img> ` element is called an *empty element*, which means it doesn't have a closing tag
- the ` <img> ` element  **_must_**  carry two attributes:
    1. ` src ` 
         - to tell the browser where to find the image file
         - contains a URL pointing to an image
    2. ` alt ` 
        - to describe the image if you can't see it
        - contains text description  (*alt text*) of the image
        - if the image used is not a meaningful image and used only for attractivness, you should use the `alt` attribute, but without the alt text (empty quotes)
- the `title` attribute can be used with the ` <img> ` element to provide additional information about the image

## Height and Width of Images

**To specify the size of an image, two attributes can be used with the `<img>` element:**

1. ` height `
    - to specify the height of the image  **_in pixels_**

2. ` width ` 
    - to specify the width of the image  **_in pixels_**

## Image Placement in Code

**Where an image is placed in the code will affect how it is displayed.**

**Image placements:**

1. when `<img>` is followed by a block-level element which always appear on a new line, such as  
 `<p>` and `<h1>`
    - the image appear before a paragraph  
        \>the paragraph starts on a new line **_after_** the image
2.  when `<img>` is followed by an inline element which sits within a block level element and do not start on a new line
    - the image appear inside the start of a paragraph  
         \> the paragraph strats on the **_same_** line as the image such that the  first row of text aligns with the bottom of the image
    - the image appear in the mIddle of a paragraph 
         \>the  image is placed between the words of the paragraph

## Rule for Creating Images

**1. save images in the right format**
    \> jpeg, png, gif

**2. save images at thr right size**
    \> at the same height and width specified in the attributes

**3. use the correct resolution**
   \> 72 pixels per inch

## Image Formats

**- JPEG**

- use for images with many different colors

**- GIF and PNG**

- use for images with few colors or large areas of the same color

---------------------------------------------------------------------------

# CSS - Color

** CSS `color` property:**

   - to specify the color of *text* inside an element

**COlors in CSS can be specified by:**

- RGB values
- Hex codes
- color names

**CSS `background-color` property:**

   - specifies the color of the background of the CSS box containing the element 

**For the text to be easy to read, there must be enough _contrast_ between the text and the background color**

**CSS3 new properties:**

   - ` opacity ` 
   - ` rgba ` 

------------------------------------------------------

# CSS - Text

**The appearance of text can be controlled in CSS by two groups of properties:**

1. properties that affect the font of the text and the typeface
2. properties that affect the text regardless of the font

**Browsers will display the typeface you choosed only if it is installed on the user's computer.**

- not any typeface you choose will appear to the user
- you can specify the typeface you want for any text inside elements using the CSS property : `font-family`
- you can specify the size of the font using: `font-size` in pixels, percentages or ems
