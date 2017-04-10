# demos
Demo scenarios and resources for IBM anayltics tooling 

The following scenarios are available in this repository

    E2E NY citibike Demo 
    
      - data_load_and_update: 
        Python scripts for initial data load and continuous update. 
      - data_prep:
        iPython notebooks to calculate maximal waiting times for the 
        * the next bike to become available on an empty  rental station
        * the next dock being freed up on a full station 
              
      - data_exploration: 
        iPython notebooks to explore trip_data and station_data to find proof that "waiting situations" are a frequent event 
      
      - data_modeling: 
        iPython notebooks using MLlib algorithms to build a regression model for wating time prediction
        
      - waiting_time_prediction: 
        Python script to apply regression model on realtime data and visualize waiting time on a NY city map 
   
