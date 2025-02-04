# This study explores multi-step time series forecasting for individual household electricity consumption.
## Employing models like Encoder-Decoder LSTMs, CNN-LSTM Encoder-Decoder, and Conv-LSTM Encoder-Decoder.  

Using a multivariate time series dataset spanning four years, the research aims to predict total active power usage over the next seven days.
## [Research](https://github.com/BhavyaChawlaGit/Encoder-Decoder-LSTMs-on-Individual-Household-Electricity-Consumption-Data/blob/main/Report.pdf)

## Data Collection
For the project, the [Individual Household Electric Power Consumption provided by the UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption) was chosen.  
The dataset has fields such as Date, Time, Global Active Power, Global Reactive Power, Voltage, Global Intensity,  
sub_metering_1 which corresponds to the kitchen,  
sub_metering_2 which corresponds to the Laundry Room,  
and sub_metering_3 which corresponds to an electric water heater and an air-conditioner.  
The dataset comprises 2075259 measurements gathered in a house located in Sceaux (7km from Paris, France) between December 2006 and November 2010 (47 months).  

## Results show promising efficiency: 
EncoderDecoder LSTM displays accuracy on specific days, CNN-LSTM captures trends with fine-tuning needs and Conv-LSTM adeptly handles data complexities.  
While the models show promise, limitations necessitate refinement, calibration, and consideration of outlier events.  
This study contributes insights for advancing time series forecasting for household power consumption, laying the foundation for innovative predictive models.

![image](https://github.com/BhavyaChawlaGit/Encoder-Decoder-LSTMs-on-Individual-Household-Electricity-Consumption-Data/assets/112718303/454455a7-46a2-4dff-a2bf-9bd63c193e5b)
