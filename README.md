# swagshop-web-answer
This is the practice for the sample website for firing Facebook pixels

## Signals:
Exercise 1a - views/partials/header.ejs
Implement Pixel base code

Exercise 1b - views/partials/header.ejs
Implement Advanced Matching

Exercise 2 - views/contactus.ejs
Implement firing of Lead event

Exercise 3 - views/shipping.ejs
Implement firing of custom event

## Dynamic Ads:
Exercise 4a - views/product.ejs
Implement firing of ViewContent event

Exercise 4b - public/js/cart.js
Implement firing of AddToCart event

Exercise 4c - views/successs.ejs
Implement firing of Purchase event

Exercise 5 - views/checkout.ejs
Implement firing of InitiateCheckout event

## Pixel sample base code
<!-- Facebook Pixel Code -->
<script>
!function(f,b,e,v,n,t,s)
{if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};
if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];
s.parentNode.insertBefore(t,s)}(window, document,'script',
'https://connect.facebook.net/en_US/fbevents.js');
fbq('init', '1086318514786699');
fbq('track', 'PageView');
</script>
<noscript><img height="1" width="1" style="display:none"
src="https://www.facebook.com/tr?id=1086318514786699&ev=PageView&noscript=1"
/></noscript>
<!-- End Facebook Pixel Code -->
