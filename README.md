# akaripay
One-file Bitcoin Cash payment/donate page       
(No code-editing required!) Responsive, Cross-browser, Tablet/Smartphone Friendly, 3 Payment options (QR/Copy/Mobile)  

<a href="http://agf.earth/addr=qrrk8mndzxvkpme3mufwaenl70zljzsgvgv6rvmx8r.html"><img src="http://agf.earth/donate_button_mini.png"></a>

<a href="http://agf.earth/addr=qrrk8mndzxvkpme3mufwaenl70zljzsgvgv6rvmx8r.html">Demo Link</a><br>

<br>
UPDATE: See <a href="https://github.com/AKARI-B3/apb">APB (AKARI-PAGES BUILDER)</a> for the latest version of AKARI-PAGES, a more recent version of AKARI-PAY, and the Builder tool as a much easier to use 'all-in-one' bundle: https://github.com/AKARI-B3/apb 
<br>

<a href="https://github.com/AKARI-B3/akaripay"><img src="http://agf.earth/akari_pay_info.png"></a>


Instructions:

1. Rename the .html filename to have your Bitcoin Cash address (CashAddr) instead.    
(Be sure not to remove the "addr=" prefix or file extension, don't include the "bitcoincash:" cashaddr prefix on the filename).     
It should look something like this: addr=qyb8z6f73youraddress741vz9betc.html (CashAddr, typically starts with a q)    

2. Upload the .html file to a web-server that you own.    

3. Simply [link](https://www.scaler.com/topics/html/html-links/) a button or href to your new .html page location. Done!    

Keep your page self-hosted. When you browse to your page, it will use the filename to prepare the payment page with included QR, copy-paste address, or mobile payment options.  Since it is self-hosted on your own servers, that gives users more trust who are looking to pay or donate. If you're worried about it being modified via the FTP, setup an ftp monitor to alert you if files are changed. Enjoy your new payment / donate page!

OPTIONAL: Are you looking for a way to show how much people have donated? Use the file labelled includes_total_donated, simply rename it to .html instead (without anything extra).

-----

UPDATE:
AKARI-PAY Advanced Released

Raise funds for anything using Bitcoin Cash.

AKARI-PAY Advanced has all akaripay features (fully responsive, device friendly, etc) but includes:

* Easily title your self-hosted fund page.
* Specify a short donation incentive message (Why donate?)
* Set a Fundraising Goal!
* You can include your first goal in the Why Donate area.
* Goal Graph! (Fills up automatically thanks to http://rest.bitbox.earth/ api!)
* Instant feedback when a donation comes in, included an instant estimate of received funds.
* Live updating donation count!
* Live updating total donations received!
* Flexible Color Themes (Easily update themes, by simply editing .txt files)
* Completely match the branding of your organization.

Instructions for AKARI-PAY Advanced: 
1. Upload the .html file in the 'advanced' folder after renaming it to have your Bitcoin Cash address. (Make sure it is from the new CashAddr format: http://agf.earth/guide/akaripages/images/cashaddress-892.jpg)
2. Upload the text files to the same folder, then edit the .txt files. Colors are specified in hex, you can use a simple tool like this: https://www.w3schools.com/colors/colors_picker.asp to pick your color scheme. Make sure you refresh your cache after uploading new .txt files otherwise your changes may not appear. Be sure to change the fund_title.txt

If you get stuck or need any help, ask us anything in our <a href="http://webchat.freenode.net/?randomnick=1&channels=%23akari&prompt=1">Dev-Chat</a>!

-----

UPDATE 2:
<a href="https://github.com/AKARI-B3/akaripages">AKARI-PAGES</a> LAUNCHED, a professional-looking, clean and detailed, customizable, fundraising page that links to your akaripay payment/donation link, that you can host completely for free using Github.io Pages (or bitbucket!). See the <A href="http://agf.earth/guide/akaripages">visual guide here</a>.

-----

AKARI GLOBAL FOUNDATION - <a href="http://agf.earth">AGF.EARTH</a>

-----
Thank you to BITBOX for the awesome REST API! https://rest.bitbox.earth/       
FOSS AKARI-PAY uses MIT License: https://opensource.org/licenses/MIT      
