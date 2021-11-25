# #include <stdio.h>
    main()
{
int unit ;
float Pay ;
printf ("Electric power (unit) :");
scanf("%d",&unit);

if (unit<=15)
(Pay = unit * 2.3488 );
else if (unit<=25)
(Pay = unit * 2.9882 );
else if (unit<=35)
(Pay = unit * 3.2405 );
else if (unit<=100)
(Pay = unit * 3.6237 );
else if (unit<=150)
(Pay = unit * 3.7171 );
else if (unit<=400)
(Pay = unit * 4.2218 );
else if (unit>401)
( Pay = unit * 4.4217 );    
    
printf(" Electric power unit =  %d ,Pay = %f Baht", unit, Pay);
}
