# CATS-Lab-ACC-data
CATS Lab ACC data is the car-following trajectory dataset including both mix traffic and pure AV traffic.

Supported reserach:

Shi, X. and Li, X., 2021. Empirical Study on Car Following Characteristics of Automated Vehicles with Different Headway Settings. Transportation Research Part C: Emerging Technologies. https://doi.org/10.1016/j.trc.2021.103134

Shi, X. and Li, X., 2021. Constructing Fundamental Diagram for Traffic Flow with Automated Vehicles: Methodology and Demonstration. Transportation Research Part B: Methodological. Preprint: https://doi.org/10.13140/RG.2.2.25353.67681

Li, Q., Li, X., Yao, H., and Liang, Z., 2021. Automated Vehicle Identification Based on Car-following Dynamics (Under review). Preprint: https://doi.org/10.13140/RG.2.2.15044.45445

Shi, X., Yao, H., Liang, Z. and Li, X., 2021. An Empirical Study on Fuel Consumption of Commercial Automated Vehicles (Under review). Preprint: https://doi.org/10.13140/RG.2.2.22363.90407

Due to the limited upload size for each file, some datasets are uploaded partially for illustration purposes. Contact xiaoweishi@usf.edu if you want to request the complete datasets or have any questions regarding the datasets.


Q & A:
Q1: I tried to convert the GPS time. But, I could not totally get the converted regular time in excel file. Is there quick cleaning/conversion process for the GPS time?

The uploaded datasets are with a frequency of either 10hz or 1hz. So, the front digits of GPS time are the same and are meaningless for analysis. You can delete them to facilitate the conversion process. For example, for 2103:016382.000, you can delete the 2103:01 since the duration of each dataset is less than one hour. 

Q2: What is the meaning of SoG?
It is the abbreviation for Speed over Ground.
