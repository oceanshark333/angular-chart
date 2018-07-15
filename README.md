# angular-chart

#pull the chart module code 
# add the module 
#import module in app.module.ts 

import {ChartModule} from './components/chart/chart.module';

#in imports declaration  add CharModule example
imports: [
    BrowserModule,
    NgbModule.forRoot(),
   
    ChartModule,
    ....
    ]
    
#Basic use in your component say html  Basic . Configure  your data provider  and use that wit chart component in below
    <chart ...  > </chart>
    
 #Advance add series bar colors and other properties
 
