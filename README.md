# Flights Data Exploration
This project explores a dataset containing flight cancellation and delays registered between 1st of January 2018 until 31st of December 2019 for approximately 5 million flights within the United States and Canada.

# Dataset
The dataset was retrieved from the [Bureau of Transportation Statistics](https://www.transtats.bts.gov/Fields.asp?Table_ID=236). Data was not available as one .csv file, multiple files worth of data were joined to consolidate as one dataset. Not all variables available in the website are interesting for the analysis, therefore a selection was made to collect relevant data.

## Variables Description
- fl_date              
- origin_airport       
- origin_city          
- origin_state         
- dest_airport         
- dest_city            
- dest_state           
- crs_dep_time         
- actual_dep_time      
- dep_delay            
- taxi_out             
- wheels_off           
- wheels_on            
- taxi_in              
- crs_arr_time         
- actual_arr_time      
- arr_delay            
- cancelled            
- cancellation_desc    
- diverted             
- crs_elapsed_time     
- actual_elapsed_time  
- air_time             
- distance             
- carrier_delay        
- weather_delay        
- nas_delay            
- security_delay       
- late_aircraft_delay 
