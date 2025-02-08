# POWER CONSUMPTION ANALYSIS OVERVIEW 
This dataset records power consumption across multiple zones along with enviromental factors such as temprature,humidity,and windspeed,spanning the year 2017
It provides daily measurement of energy usage in diffrent areas.the datasey is useful for analyzing trends,forcasting power demand and optimizing energy distribution .it can help identify patterns influenced by weather condition and improve energy efficiency strategies
# LANDING PAGE
- Date(datetime) -A specific day of the year, typically represented in formats like YYYY-MM-DD or DD/MM/YYYY.
- Temperature – The measure of how hot or cold something is, usually expressed in degrees Celsius (°C) or Fahrenheit (°F).
- Humidity – The amount of water vapor present in the air, usually expressed as a percentage (%).
- Windspeed – The rate at which air moves in a given direction, commonly measured in meters per second (m/s) or kilometers per hour (km/h).
-  General Diffuse Flow – The total amount of diffused solar radiation received at a given location, including all scattered sunlight.
-  Diffuse Flow – The portion of solar radiation that is scattered by atmospheric particles and reaches the surface without direct sunlight.
-  Day of the Week – The name of a specific day in the seven-day cycle (e.g., Monday, Tuesday, etc.).
-  Power Consumption Zone 1, 2, and 3 – The amount of electrical energy used in specific predefined areas (Zone 1, Zone 2, and Zone 3) within a facility, building, or grid system, typically measured in kilowatt-hours (kWh)
# DATA SOURCE
[download here] https://archive.ics.uci.edu/dataset/849/power+consumption+of+tetouan+city
# TOOLS
   -*power bi*
# TYPES OF ANALYSIS USED FOR THIS PROJECT 
power consumption analysis- to analyze power consumption variance across the whole year
power consumption analysis-to analyze the impact of powwer consumption acrosss all zones
atmosphere condition analysis- to identify trends overtime across all the quaters of the year

# KEY PERFORMANCE INDICATORS
1. In which month is the power consumption variance the highest
2.  Which quater of the year recorded highest levels of humidity,temprature,diffuse flow and wind speed
3.  Which zone exhibit the highest power consumption
4.  Was the power consumption taregt of the year archieved
5.  Which month experience the highest overall power consumption
6.  On which day of the week is power consumption at its peak
7.  What is the diffrence between the power consumption in zone 1 and the total power consumption
8.  what is the diffrence between the power consumption in zone 2 and the total power consumption
9.  what is the diffrence between the power consumption in zone 3 and the total power consumption
# DATA ANALYSIS
- Average power consumption ,date by power consumption variance:This indicate that july had the highest average power consumption at 88k while august has recorded the highest power consumption variance with 34k highlighting significant flunctuationsin power usage during these months.
- Average power consumption ,month by zone:This analyis highlights that zone 1 recorded the highest average power consummption in both july and and august , reaching 36k.Zone 2 experience its peak consumption in august at 25k ,while Zone 3 recorded its highest consumption in july at 28k indicating variations in power usage across diffrent zones during these months.
- Humidity , diffuseflows,windspeed and teprature by quarter :this indicates that Qtr 2 recorded the highest humidity at 0.09m and the highest diffuse flows at 0.93m and the highest diffuse flows at 1.36m. in contrast,Qtr 3 experienced the highest temprature at 0.033m and the highest temprature at 0.33m and the highest windspeed at 0.05
- kpi:The KPI analysis indicates that the total monthly power consumption reached 275.40M, significantly exceeding the peak target of 96.62K. This represents a deviation of -284,947.02% from the target, highlighting a substantial increase in energy usage. 
- power consumption by month: The monthly power consumption analysis shows that July recorded the highest consumption at 393.61M, followed by a decline in the following months. Additionally, Zone 2 had a total power consumption of 1.1B kWh. This data highlights variations in energy usage across different periods, with a peak in July.
-power consumption by days(days of the week): The analysis of power consumption by day indicates that Thursday recorded the highest energy usage at 73K kWh, followed closely by Wednesday and Tuesday at 72K kWh each. The lowest consumption was observed on Sunday at 68K kWh.
- Power consumption by zone 1: Zone 1 accounted for 1.7B kWh of power consumption, contributing to the overall total of 3.7B kWh. This suggests that Zone 1 is a major consumer, significantly impacting the overall energy usage.
- Power consumption by zone 2:The analysis shows that power consumption peaked in July at 393.6M kWh, with a decline towards December. Zone 2 consumed 1.1B kWh, contributing significantly but not dominantly to the total 3.7B kWh. This highlights seasonal variations in energy use and the substantial role of Zone 2 in overall consumption.
- power consumption by zone3:Zone 3 recorded a total power consumption of 0.9B kWh, contributing to the overall energy usage of 3.7B kWh. These insights highlight peak consumption periods and variations in energy demand across different days and zones.




# DASHBOARD
[Power consumption analysis] ![Dashboard 1](https://github.com/user-attachments/assets/68bb3963-9162-44b8-98e9-ebe9b9c62e01)
![dashboard2](https://github.com/user-attachments/assets/ececbce6-5223-4b22-9c9a-be55de4f7492)
# INSIGHT
1. Month by total power consumption we recorded the highest power consumption in july with 393,606kwh
2. power consumption by all zones ,zone 1 recorded the highest power consumption in july with 393,606kwh
3. We recorded the highest humidity in qtr1 ,highest diffuse in qtr2, highest temprature in qtr3 , and highest windspeed in qtr3
4. KPI visulization 275.40M
5. target 96.62k(-284964)
6. we recorded the highest average power consumption in july 88kwh and power consumption variance in august with 35k
7. Thursday has the highest power consumption with 73k kwh

# RECOMMENDATION 
1. investigate the reson behind the spike in power consumption
2. encourage energy efficient pratrice such as using smart meters to alert user of high consumption period or ofeer incentives for off peak usage
3. ensuring infasture can handle high load of peak in peak month
4. conduct zone specific energy audit to identify high consumption appliances ,processesor behaviour contributing to spike in zone 1
5. promoting renewable energy solutions by installing solar panels or other renewable sources in high consumption zones to offset demand
6. introdue targeted programs such as energy savings campaigns or smart grid technologies to manage zone 1 high demands
7. humidty(q1)install dehumidifier or energy efficient cooling system to reduce impact of humidy on power consumption
9. diffuse energy (q2) use this quater quater high diffuse energy for solar energy harvsting ,increasing renewable usage
10. temprature and wind (q3) optimize HVAC systems for efficient and leveraging and turbines if feasible in Q3 to supplement power supply
     
 

