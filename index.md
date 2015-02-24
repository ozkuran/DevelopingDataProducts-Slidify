2015 Model Car Mileage Per Gallon Explorer
========================================================
author: Mahmut Ali ÖZKURAN
date: 20-02-2015

Problem
========================================================

  As ecological thinking is grow up in the public. People begin to think more about their spendings effect on the Earth. While the automobiles have a big impact on ecology as they produced greenhouse gasses. 

Solution
========================================================

I think that if i could be help people to choose a better car which has less effects on environment. Hence, i have developed this application to help people to choose which car to use.


User Friendly
========================================================

The aplication is developed as Web Application which is located at http://ozkuran.shinyapps.io/2015ModelCarMPGExplorer/. 
As application have filtering option with both sliders and text input it is so easy to use. 

Extra Properties
========================================================

As many properties of application present also after every filter you can see summary of data at top of the page. 


```r
data <- read.csv("data/15tstcar-2014-11-13.csv")
data <- data[,c("Represented.Test.Veh.Make")]
summary(data)
```

```
        ACURA  Aston Martin          AUDI       Bentley       BENTLEY 
           27            12           298             5            26 
          BMW       BUGATTI         BUICK      CADILLAC     CHEVROLET 
          781             5            22            67           243 
     Chrysler         Dodge       Ferrari          Fiat          Ford 
           38            89            32            23           208 
         FORD           GMC         HONDA       Hyundai       HYUNDAI 
            6             8           162            72            83 
     INFINITI        Jaguar        JAGUAR          Jeep           Kia 
          132            43             4            96            45 
          KIA   LAMBORGHINI    Land Rover         LEXUS       Lincoln 
           77            18            20           187            24 
     MASERATI         Mazda         MAZDA       McLaren Mercedes-Benz 
           24            25            59            10           202 
         Mini    MITSUBISHI        NISSAN       Porsche           RAM 
           70            34           163           130            56 
  Rolls Royce         SCION           SRT        SUBARU        TOYOTA 
           14            13             6            70           260 
   Volkswagen    VOLKSWAGEN         Volvo            VW W204E63-Z1011 
           15           132            71             2             2 
```

