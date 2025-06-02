# Media Queries

There are tons of screens and devices with different heights and widths, so it is hard to create an exact breakpoint for each device. To keep things simple you could target five groups:

1. Extra small devices (phones, 600px and down) 
@media only screen and (max-width: 600px) {...}

2. Small devices (portrait tablets and large phones, 600px and up) 
@media only screen and (min-width: 600px) {...}

3. Medium devices (landscape tablets, 768px and up) 
@media only screen and (min-width: 768px) {...}

4. Large devices (laptops/desktops, 992px and up) 
@media only screen and (min-width: 992px) {...}

5. Extra large devices (large laptops and desktops, 1200px and up) 
@media only screen and (min-width: 1200px) {...}


## We can write media queries in 3 ways

1. @media only screen and (max-width:600px){}
2. @media screen and (max-width:600px){}
3. @media (max-width:600px){} ---> Standard

