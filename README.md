# CVSExtraCare-coupon-sender

This queries all the buttons with the class "send to card" and clicks them for you!

1. Navigate to the coupons page
2. Make sure to scroll down as far as you can to get the coupons to load
3. Open the console (F12 then click on Console)
4. Insert the code in the JS file in the text field and hit enter.


Alternatively, you can add a bookmark to your bookmarks bar with this address: 

`javascript:(let sendToCardButtons = document.querySelectorAll("send-to-card-action > button"); for(let i = 0; i<sendToCardButtons.length;i++){ sendToCardButtons[i].click(); } console.log("Success");)`

Clicking it when at the coupons page should give the same effect!
