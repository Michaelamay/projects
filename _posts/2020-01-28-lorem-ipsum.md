---
layout: post
title: Top Ten Stock Market Symbols <br><font style="color:gray"><small>Information/Educational Website</small></font>
description: Lorem Ipsum is simply dummy text
summary: A JAVA program that display the top 10 stock symbols from the stock market.<br><br><strong>Written:</strong> JAVA, Hashmaps, Trees
---
<style>
h1{
    color: Black;
}
</style>
A JAVA program that calculates the top ten stock market symbols according to volume from a feed of input data. The volume of any particular stock can be define by E (order executed ) + P (trade)  = Volume. The program assumes input order messages from the feed pitch data file below which contains approxmatiely 2000 lines of order messages ready to be processed. It will execute any of the order messages: Add, Order Executed, Order Cancel, Trade, Trade Break, Auction Update, or Auction Summary, and return the top ten stocks by volume.

Furthermore, you will find the offical specification to the order message here. <a href="https://github.com/Michaelamay/StockMarketSymbols/blob/main/PITCH_Specification.pdf" target="_blank" rel="noopener noreferrer">Visit specification document.</a>

To run the program on your computer: 
1. Make sure you have Java installed, you can confirm by entering 'Java -version' on the command line or terminal. If Java is install on your machine, you should get the version number upon return.

2. Extract the files in the zip file; open the command line and navigate to the directory where the files are extracted, and simply type 'java PitchDriver', the class will will look for and find the feed pitch data file automatically and return the results as shown in the screenshot below.

<a href="https://github.com/Michaelamay/StockMarketSymbols/blob/main/PitchDriver.java">View source code</a> &#x2022;
<a href="https://github.com/Michaelamay/StockMarketSymbols/raw/refs/heads/main/StockMarketSymbols.zip" download="true">Download Program Zip File</a> &#x2022; 


<!-- Image section -->
<!--<img src="https://i.ibb.co/mcgTnfM/Chuck-home.png" alt="Main front page" border="3">-->

<img src="https://i.ibb.co/hMK4S1n/Screen-Shot-2024-04-28-at-8-12-38-PM.png" alt="Main front page">




