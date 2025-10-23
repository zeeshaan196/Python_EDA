# Python_EDA

#ADVERTISEMENT DATA SET

1. It has 24 columns 

2. Maker column has 88 No.of unique elements in which Ford has highest overall
   counts = 26937

3. In AB when grouping 'Maker' , 'BodyType' to check 'Price' having the counts from which
   price of 995.0 occurs higher that is 226(counts) and next higher counts are
   180(counts) of price 3995.0 

4. In BC when grouping 'Maker' , 'Color' to see 'Reg_year' counts , so the higher counts
   manufactured in the year 2015.0 (count = 14) of maker Abarth and color black 

5. visualizing a Bar plot where it shows the distribution of different body types
   based on their Transmission . Here Hatchback have top most counts(i.e 3.5K) under manual

6. next Bar plot indicates 'REPORT ON TRANSMISSION TYPES According to various Colors' ,
    here we can see highest trend counts of color black  under Manual Transmission.

7. visualized the HistPlot of Data AB to check price skewness('outliers' : no.of Cars that

   are more costly).  

8. After plotting Pie chart we observe Manual transmission has extra percentage.

9. In data of A ,I selected 'Length' Column in which outliers was present alot showing
   extreme points but i have Detected outliers using Quantile and removed according to
   condition using the lower and higher limits , so mean can be applicable.

10. In 'Height' Column, i applied Median since it was have outliers and filled Nan values
    too.

11. I made a CD in which,By Using GROUPBY FUNCTION on 'Maker' to Check 'Width' we see SsangYong maker 
    dominates with SUV's and MPV's where as VW , Tesla ; etc appears with smaller
    contribution and Land Rover in Automatic Transmission does have HIGHER counts than all
    1784 .

12. similarly done with DE using GROUPBY FUNCTION but with 'Length' we notice that Land rover have highest
    counts dominating with lengthier models among top 30 length cars.

13. Nextly thing is to Merge CD and DE in EF to see common 'Makers' 

14. Here Comes PLOTTING OF LINE in SEABORN(REPORT OF MAKERS ON SIZE) From the Data's CD , DE  and EF .
    RESULT : ==> In Length of Makers the greatest Length is approx 6K
             
             ==> In Width of Makers the greater width is around 2.3K
             ==> In Merge of Makers Count_x > count_y

15. Next comes PLOTTING OF SCATTER IN SEABORN(SCATTERED REPORT OF MAKERS BASED ON SIZE)      

    From Data's CD and DE .
    RESULT : ==> In Length of Cars points are lieing from 5.5K to 6.5K where greater have 250 counts of having length around 5.9K
             ==> In Width of Cars mostly points are below 2.5K width depicting of low width 
and have 1 car of around 2.6K 

16. Plotting HistPlot of CD[Width], Result => Increasing of width till 2.6K
    Plotting HistPlot of DE[Length], Result => Increasing of Length till 6K
