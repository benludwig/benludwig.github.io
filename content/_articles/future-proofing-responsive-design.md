---
title: Future-proofing responsive design
img: "https://res.cloudinary.com/benludwig/image/upload/c_fill,f_auto,h_500,q_auto:best,w_1000/v1572903130/article_future_proofing_klqw1c.png"
copy: "How to prepare for devices that aren't built yet."
order: 2
layout: standard
---
<div class="page">
  <div class="image-column-1000">
    <img src="https://res.cloudinary.com/benludwig/image/upload/c_fill,f_auto,h_500,q_auto:best,w_1000/v1572903130/article_future_proofing_klqw1c.png" alt="Individual working">
  </div>
  <div class="type-column">
    <h1>Future-proofing Responsive Design</h1>
    <p>When responsive design was first developed, it was intended to shrink websites from desktop screens to smartphones. Media queries—the code that made responsive design possible &#8212; became a standard in 2012 shortly after the release of the iPhone 5.</p>
    <p>In 2016 mobile traffic officially outpaced all other devices. Instead of continuing to shrink layouts, designers started with mobile and worked outward. The outlier became the benchmark and the term Mobile-First was coined.</p>
    <p>Not much has changed since then. Most design software today defaults to mobile devices and Mobile-First is a certified buzzword. Google even started reducing quality scores for websites that aren’t mobile-friendly.</p>
    <p>What has changed over the years is the point in which layouts stop expanding. There are no requirements for supporting large screens. Google doesn’t downgrade websites that support laptops but not televisions. So why acknowledge them?</p>
    <p>Devices and design trends change. Back when designers were Desktop-First, they needed a place to start. The <a href="https://960.gs/" target="_blank">960 Grid System</a> was the unofficial standard defining a maximum width as 960 pixels. Now layouts are reaching 1600 and 1800 pixels wide &#8212; an 87% increase in just a few years.</p>
    <p>What’s more, retail stores are transforming into experiential spaces complete with big interactive displays. Most modern sites today would need an extensive overhaul to scale from the screen in your hand to a screen on the wall. A few small changes today can prepare teams for the future. To do that, we have to look at what constitutes a layout: typography, photography and video.</p>
    <h2>Typography</h2>
    <p>There are a handful of ways to define a font size on the web. Pixels are the easiest to use and most common. A <a href="https://www.w3.org/TR/css-values-3/#rem" target="_blank">rem unit</a> is not as widely known or intuitive but it’s extremely powerful. This is because a rem unit is linked to the html font size.</p>
    <p>The html font size defaults to 100% but if it’s manually increased or decreased each instance of a rem unit will respond. It’s akin to a volume control that maintains the sound relationship between each instrument as the music gets louder or quieter.</p>
    <p>Adjusting every font size on a website to accommodate bigger screens is tedious and time intensive. By switching from pixels to rem units, it can be done with a single line of code.</p>
    <h2>Photography</h2>
    <p>The function of a Content Delivery Network is to do exactly that &#8212; deliver content to a website. When an image is uploaded to a CDN it’s available via its own URL. Copying that URL and adding it the code of a website will display the image on the page.</p>
    <p><a href="https://cloudinary.com/" target="_blank">Cloudinary</a> is a CDN that has taken URLs a step further and introduced <a href="https://cloudinary.com/documentation/image_transformations" target="_blank">transformations</a>. After an image is uploaded to Cloudinary the URL can be modified to deliver different versions of the same image. Want a larger image for bigger screens? Change a section of the URL from /w_800/ to /w_2400/ and the image that was 800 pixels wide will be displayed 2400 pixels wide &#8212; all without ever editing the actual photo. Need more extensive positioning and editing? You can also enable things like <a href="https://cloudinary.com/documentation/advanced_facial_attributes_detection_addon" target="_blank">facial recognition</a> and <a href="https://cloudinary.com/documentation/advanced_facial_attributes_detection_addon#eyes_detection_based_cropping" target="_blank">eye detection-based</a> cropping just by changing the URL.</p>
    <h2>Video</h2>
    <p>Most videos on the web are already hosted on YouTube or Vimeo. And because YouTube is the second most popular search engine in the world it should probably stay that way. As layouts expand for bigger screens those videos will expand naturally and maintain their aspect ratios.</p>
    <h2>Changes today</h2>
    <p>Technology changes quickly. As a result, tech culture is captivated by the future. While the methods described in this article are focused on what could come next, there are immediate benefits as well.</p>
    <p>Rem units do a better job of scaling typography, even on smaller screens. Cloudinary’s CDN will drastically reduce the time it takes to make image adjustments on any website, big or small. So even if screens don’t change and experiential retail fades away, these techniques aren’t a gamble waiting for a payoff.</p>
  </div>
</div>
