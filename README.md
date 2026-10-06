# Assignment-___2
DATA CLEANING AND TRANSFORMATION

* find the median and filling missing values
8category colum correction (select column with ctrl+H, Home >find &select>filling the find what and replace with)
*=VLOOKUP(A6,A:F,6,TRUE)
*data cleaning and trimming(data>get data>transform in data>column select>trim>cleaning >capitalized).
* splitting and merging 
  *product id column splitting >manufactu
ring date and country code
*manufacturing date=LEFT([@[Product ID]],6)
*country code =RIGHT([@[Product ID]],2)
*product brand =[@[Brand Name]]&" "&[@[Product Name]]
*price column to currency format(column select>home>number section>currency$>ok)
*conditional formatting (price column select>home>conditional formatting>color scale)
                         (category column select>home>conditional formatting>highlights cell rules>test that contains> electronics )
  
