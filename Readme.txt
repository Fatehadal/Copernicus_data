 					   Environmental Data Collection
					    Adriatic Sea (Venice, Italy)
                                                   (2015 - 2020)

Copernicus website link:
https://resources.marine.copernicus.eu/products

Coordinates for the extraction of the Copernicus data:
12.1875, 43.5833
14.0208, 45.8333

Environmental Variables: SST (Sea surface Temperature), wind, wave height, salinity, etc.

***After collecting envirornmental data (NC/NetCDF file):
	1. Extract variable and dimensions from the NetCDF file
	2. Convert and write the data into CSV file (netcdf_csv_github.ipynb)
	3. Merge Raw AIS data, landing report data and environmental data
	4. For season selection, use the following four time frames: 
		i. JFM -> Winter
		ii. AMJ -> Spring
		iii. JAS -> Summer
		iv. AND -> Autumn
