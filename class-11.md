# CSS Images

## Controlling size of images in CSS

**The size of an image can be controlled in CSS just like the size of any box using the properties :**

`width` and `height `  


**When loading a webpage, the HTML and CSS codes load before the images, that's why it's helpful to specify the size of the images so the browser what space to leavr for the images and render smoothly**  

**It's common in websites to use the same sized images across all their pages**  

**Using sized image consistently across a website allows you to use CSS to control the dimension of images by organizing them in classless instead of specifying that dimensions in HTML** 


## Aligning Images in CSS 

**`float` property is commonly used to  align images.** 

- images by default are `inline` elements that flow within the surrounding text.

- for images to be *centerd* they must be turned into `block` level elements using the `display` property. 

## Background Images

**Background images by default repeat to fill the entire box they're applied to.**

 ```
background-image : url ("image-path") ;
```

- background position :
    When an image is not being repeated, you can use the `background-position` property to specify where in the browser window the background image should be placed. 

##Image Rollovers and Sprites

**In CSS, you can create a link or button that changes to a second style when a user moves their mouse over it (known as a _rollover_) and a third style when they click on it.**

**When a single image is used for several different parts of an interface, it is known as a  _sprite_.** 

- You can add the logo and other interface elements, as well as buttons to the image.

- The advantage of using sprites is that the web browser only needs to request one image rather than many images, which can make the web page load faster.


-------------------------------------------------


# Practical Information


## SEO : Search Engine Optimization

- SEO is the practice to make youe website appear in the top seach results when people search about the topics covered in your website 

- SEO is mainly about working out what terms people are most likely to use when searching about the topica you cover and usig them in a certain way in your website such that you increase tbe chance to get your website appear in the search results

- SEO is often split into two areas: 
    - on-page techniques 
      the methods you can use on your web pages to improve their rating in search engines

    - off-page techniques
      how to rank your site by looking at the number of other sites that link to yours


### On-page SEO: How to identify keywords

1. Brainstorm
1. Organize
3. Research
3. Compare
4. Refine
5. Map


----------------------------------------------------------

# HTML5 video and audio

**You can embed video and audio to your website im HTML using the `<video>` and `<audio>` elements**

**You can use the `controls` attribute with these elements to enble the default set of playback controls**

## The HTMLMediaElement API


**the `HTMLMediaElement` API provides features to allow you to control video and audio players programmatically, i.e.:**

- `HTMLMediaElement.play()`
- `HTMLMediaElement.pause()`
