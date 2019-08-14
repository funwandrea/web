# web
 
Skip to content
 
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@funwandrea 
1
0 0 funwandrea/web
 Code  Issues 0  Pull requests 0  Projects 0  Wiki  Security  Insights  Settings
web/landing.css
 Andrea Fung index.html
e30c60a 1 minute ago
681 lines (680 sloc)  68.1 KB
    
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="Content-Style-Type" content="text/css">
  <title></title>
  <meta name="Generator" content="Cocoa HTML Writer">
  <meta name="CocoaVersion" content="1671.5">
  <style type="text/css">
    p.p1 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica}
    p.p2 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; min-height: 14.0px}
    span.Apple-tab-span {white-space:pre}
  </style>
</head>
<body>
<p class="p1"><span class="Apple-tab-span">	</span>body {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin: 0;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>padding: 0;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>:root {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>--web-view-ids: Landing_Page___1;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Landing_Page___1 * {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin: 0;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>padding: 0;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Landing_Page___1 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>box-sizing: border-box;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>background: #E5E5E5;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 1920px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 1080px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>background-color: rgba(255,255,255,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: hidden;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin: 0;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>padding: 0;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>--web-view-name: Landing Page – 1;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>--web-view-id: Landing_Page___1;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>--web-refresh-for-changes: true;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>--web-enable-deep-linking: true;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Rectangle_1 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>fill: rgba(167,199,211,0.502);</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>stroke: rgba(167, 199, 211, 0.5);</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>stroke-width: 1px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>stroke-linejoin: miter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>stroke-linecap: butt;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>stroke-miterlimit: 4;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>shape-rendering: auto;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>.Rectangle_1 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 1920px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 186px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 894px;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Rectangle_2 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>opacity: 0.5;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>fill: rgba(11,125,166,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>.Rectangle_2 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 1920px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 200px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Andrea_Fung {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 679px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 10px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 563px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 120.00000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -17.500003814697266px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: bold;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 85px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Symbol {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 276px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 69px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 822px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 228.191px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#About_me {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 1px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 276px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 120.00000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -30.000003814697266px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 60px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#pic_me {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 170.445px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 488px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 875px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 322px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Rectangle_3 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>fill: url(#Rectangle_3_A2_Rectangle_4_pattern);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>.Rectangle_3 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 170.445px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 488px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Symbol_3 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 195px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 69px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 627px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 742px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Github {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 195px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 120.00000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -30.000003814697266px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 60px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Github_A2_Text_4 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 143px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 569px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 50px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 21.600000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -3.3000001907348633px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: lighter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#contact_menu {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 222px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 69px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 1098.256px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 471.191px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Contact {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 223px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 120.00000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -30.000003814697266px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 60px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#About_Me {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 176px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 923px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 84px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 21.600000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -1.8000001907348633px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_3 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 92px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 203.487px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 946.547px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Introduction {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 92px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 25.200000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -5.100000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 123px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 203px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 1011px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Creative_Resume {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 123px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 25.200000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -5.100000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_3_A2_SymbolInstance_7 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 58px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 204px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 968px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Resume {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 59px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 25.200000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -5.100000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_A2_SymbolInstance_8 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 125px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 204px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 989px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Curriculum_Vitae {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 126px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 25.200000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -5.100000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Group_1 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 71px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 21px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 385px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 923px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_3_A2_SymbolInstance_9 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 71px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 21px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Projects {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 71px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 21.600000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -1.8000001907348633px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_3_A2_SymbolInstance_10 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 66px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 21px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 1491px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 948px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Git_Hub {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 2px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 56px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 25.200000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -5.100000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Group_13 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 167px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 385px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 947px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#MDQ_website_prototype {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 168px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 25.200000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -5.100000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Group_5 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 129px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 385px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 969px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#MDQ_ad_campaign {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 130px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 25.200000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -5.100000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Group_9 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 192px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 385px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 990px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#PALM_project_ad_campaign {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 193px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 25.200000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -5.100000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_A2_SymbolInstance_11 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 260px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 72px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 1045px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 738px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Linkedin {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: hidden;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 261px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 72px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 120.00000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -30.000003814697266px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 60px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_A2_SymbolInstance_12 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 234px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 69px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 588px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 471px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Projects_A2_Text_17 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 235px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 120.00000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -30.000003814697266px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 60px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_A2_SymbolInstance_13 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 134px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 627px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 947px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Therapy_Materials {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 135px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 25.200000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -5.100000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_A2_SymbolInstance_14 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 80px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 628px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 967px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Zone_Game {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 81px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 25.200000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -5.100000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_A2_SymbolInstance_15 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 64px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 1491px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 975px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Linkedin_A2_Text_20 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 65px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 25.200000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -5.100000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_A2_SymbolInstance_16 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 67px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 21px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 1458px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 923px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Contact_A2_Text_21 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 67px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 21.600000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -1.8000001907348633px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 18px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_A2_SymbolInstance_17 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 60px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 21px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 1491px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 996px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Kaggle {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 2px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 50px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 25.200000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -5.100000381469727px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 15px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#https___www_linkedin_com_in_an {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 1473px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: -111px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: hidden;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 301px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 300px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: Helvetica Neue;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 20px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(11,125,166,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Component_24___6 {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 220px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>height: 52px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 651px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 540px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#UX_Based_ {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>opacity: 0.6;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 6px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 0px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 220px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 120.00000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -37.500003814697266px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 45px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p1"><span class="Apple-tab-span">	</span>#Data_Based {</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>opacity: 0.58;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>position: absolute;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>left: 651px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>top: 607px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>overflow: visible;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>width: 243px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>white-space: nowrap;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>line-height: 120.00000762939453px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>margin-top: -37.500003814697266px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>text-align: left;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-family: American Typewriter;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-style: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-weight: normal;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>font-size: 45px;</p>
<p class="p1"><span class="Apple-tab-span">	</span><span class="Apple-tab-span">	</span>color: rgba(0,0,0,1);</p>
<p class="p1"><span class="Apple-tab-span">	</span>}</p>
<p class="p2"><br></p>
<p class="p2"><br></p>
<p class="p1">Warnings:</p>
<p class="p1">1. Border support: Border position "inside" on "Rectangle_1"<span class="Apple-converted-space">  </span>is not supported</p>
<p class="p1">2. ID truncated: The auto generated ID starting with 'https___www_linkedin' was truncated</p>
<p class="p1">3. Duplicate ID: The Rectangle named, "Rectangle 3" on artboard, "Landing Page – 1" was renamed to, "Rectangle_3_A2_Rectangle_4"</p>
<p class="p1">4. Duplicate ID: The Text named, "Github" on artboard, "Landing Page – 1" was renamed to, "Github_A2_Text_4"</p>
<p class="p1">5. Duplicate ID: The SymbolInstance named, "Component 3" on artboard, "Landing Page – 1" was renamed to, "Component_3_A2_SymbolInstance_7"</p>
<p class="p1">6. Duplicate ID: The SymbolInstance named, "Component" on artboard, "Landing Page – 1" was renamed to, "Component_A2_SymbolInstance_8"</p>
<p class="p1">7. Duplicate ID: The SymbolInstance named, "Component 3" on artboard, "Landing Page – 1" was renamed to, "Component_3_A2_SymbolInstance_9"</p>
<p class="p1">8. Duplicate ID: The SymbolInstance named, "Component 3" on artboard, "Landing Page – 1" was renamed to, "Component_3_A2_SymbolInstance_10"</p>
<p class="p1">9. Duplicate ID: The SymbolInstance named, "Component" on artboard, "Landing Page – 1" was renamed to, "Component_A2_SymbolInstance_11"</p>
<p class="p1">10. Duplicate ID: The SymbolInstance named, "Component" on artboard, "Landing Page – 1" was renamed to, "Component_A2_SymbolInstance_12"</p>
<p class="p1">11. Duplicate ID: The Text named, "Projects" on artboard, "Landing Page – 1" was renamed to, "Projects_A2_Text_17"</p>
<p class="p1">12. Duplicate ID: The SymbolInstance named, "Component" on artboard, "Landing Page – 1" was renamed to, "Component_A2_SymbolInstance_13"</p>
<p class="p1">13. Duplicate ID: The SymbolInstance named, "Component" on artboard, "Landing Page – 1" was renamed to, "Component_A2_SymbolInstance_14"</p>
<p class="p1">14. Duplicate ID: The SymbolInstance named, "Component" on artboard, "Landing Page – 1" was renamed to, "Component_A2_SymbolInstance_15"</p>
<p class="p1">15. Duplicate ID: The Text named, "Linkedin" on artboard, "Landing Page – 1" was renamed to, "Linkedin_A2_Text_20"</p>
<p class="p1">16. Duplicate ID: The SymbolInstance named, "Component" on artboard, "Landing Page – 1" was renamed to, "Component_A2_SymbolInstance_16"</p>
<p class="p1">17. Duplicate ID: The Text named, "Contact" on artboard, "Landing Page – 1" was renamed to, "Contact_A2_Text_21"</p>
<p class="p1">18. Duplicate ID: The SymbolInstance named, "Component" on artboard, "Landing Page – 1" was renamed to, "Component_A2_SymbolInstance_17"</p>
</body>
</html>
© 2019 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
