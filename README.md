## ew-onboarding-first-email-template
## Purpose
To get the customer to buy the product it is important to send emails shortly after they downloaded the trial.  This template is used to send out a nice looking email.
## Timing
Emails are sentout from EmbroideryWare when a time event is triggered.  The trigger occurs when a period of time has elasped since they download the trial.  
## Method
The email has a message and a call to action.  The main message is a discount but they are also informed about support and social media resources.  The discount elaspes to build a sense of urgency.
## Keywords
Each template is setup with key words that are replaced with customer data from the database.
The following keywords are used in this template. `[client-first], [coupon-value], [your-message1], [your-message2]`
```html
<p style="margin: 0 0 16px;">Hi [client-first],</p>
<p style="margin: 0 0 16px;">We are so glad you are taking 
    EmbroideryWare for a test drive. Soon you will be creating
    designs of your own. Have fun!</p>
<p style="margin: 0 0 16px;">[client-first] we have created 
    an offer just for you. For the next seven days of your
    trial, we are offering <b>[coupon-value] off</b>. To get 
    the offer just use the coupon below at checkout.</p>
<p style="margin: 0 0 16px;">
    <b>[your-message1]</b>
</p>
<p style="margin: 0 0 16px;">
    <b>[your-message2]</b>
</p>
```
## Customizable html
The neat thing about using a template is that the email is customizable by simply changing the html.  For example it can be replaced with a seasonal one during the holidays or a promotional one that changes the suggested products.  The possiblities are endless.
## Personable
We have found that it is nice to address the customer by thier name and calculate the dollar savings for each product.  They are more likely to buy if you help them understand the deal.
## Images
Include a few images of the product so they know what they are buying.  Also style the call to action button with an image.  The images are always links.  It is not good practice to send binary equivalents of your images in your email.  It is just too much data and some email systems will strip this information out.  
>**Note:** Always include alternate text with all images.
```html
<img src="url of image" alt="image description" height="150" width="150">
```
## Example
![Example of Template](https://github.com/JimmySoftLLC/ew-onboarding-first-email-template/blob/master/Ew%20img%20assets/EmailTemplateImage.jpg)
