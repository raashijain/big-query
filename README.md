# big-query
Select * From `bigquery-public-data.austin_311.311_request`
Order by complaint_description ASC 
Limit 10 
unique_key	complaint_type	complaint_description	owning_department	source	status	status_change_date	created_date	last_update_date	close_date	incident_address	street_number	street_name	city	incident_zip	county	state_plane_x_coordinate	state_plane_y_coordinate	latitude	longitude	location	council_district_code	map_page	map_tile
16-																							
16-00165485	AFDWILPR	AFD - Wildfire Concern / Presentation	Austin Fire Department	Spot311 Interface	Closed	2016-08-15 13:37:38 UTC	2016-07-02 21:29:57 UTC	2016-08-15 13:37:39 UTC	2016-08-15 13:37:38 UTC	"11004 CROSSLAND DR, AUSTIN, TX 78726"	11004	CROSSLAND	AUSTIN	78726	TRAVIS	3088072.75173802	1.01325039978834E7	30.43946524	-97.8214893	"(30.43946524, -97.8214893)"	6	433X	ME37
16-00166372	AFDWILPR	AFD - Wildfire Concern / Presentation	Austin Fire Department	Spot311 Interface	Closed	2016-08-15 13:37:20 UTC	2016-07-03 21:45:35 UTC	2016-08-15 13:37:20 UTC	2016-08-15 13:37:20 UTC	"12100 MILLWRIGHT PKWY, AUSTIN, TX 78750"	12100	MILLWRIGHT	AUSTIN	78750	WILLIAMSON	3093817.22050453	1.01369382395395E7	30.45129661	-97.80294507	"(30.45129661, -97.80294507)"	6	433Q	MF38
19-00021955	AFDWILPR	AFD - Wildfire Concern / Presentation	Austin Fire Department	Spot311 Interface	Open	2019-01-20 10:52:17 UTC	2019-01-20 10:52:17 UTC	2019-01-29 23:00:05 UTC		"14821 FM 1825 RD, PFLUGERVILLE, TX 78660"	14821	1825	Pflugerville	78660	TRAVIS	3136795.92794037	1.0133896337328E7	30.44017468	-97.66681471	"(30.44017468, -97.66681471)"	7	437W	MN37
19-00273276	AFDWILPR	AFD - Wildfire Concern / Presentation	Austin Fire Department	Spot311 Interface	Open	2019-07-19 08:04:47 UTC	2019-07-19 08:04:47 UTC	2019-07-26 23:00:05 UTC		"13681 N US 183 HWY SVRD NB, AUSTIN, TX 78729"	13681	US 183 HWY SVRD	AUSTIN		WILLIAMSON	3097557.25070637	1.01388839988538E7	30.45641084	-97.79093737	"(30.45641084, -97.79093737)"	6	434J	MG38
16-00242834	AFDWILPR	AFD - Wildfire Concern / Presentation	Austin Fire Department	Phone	Closed	2017-01-04 15:18:17 UTC	2016-09-15 12:28:20 UTC	2017-01-04 15:18:17 UTC	2017-01-04 15:18:17 UTC	"10502 PICKFAIR DR, AUSTIN, TX 78750"	10502	PICKFAIR	AUSTIN	78750	TRAVIS	3091292.75164969	1.01299679982835E7	30.43229371	-97.81145634	"(30.43229371, -97.81145634)"	6	463C	MF36
17-00363389	AFDWILPR	AFD - Wildfire Concern / Presentation	Austin Fire Department	Phone	Open	2017-12-06 16:28:07 UTC	2017-12-06 16:28:07 UTC	2017-12-06 16:28:07 UTC		"11101 COMISO PALA PATH, AUSTIN, TX 78726"	11101	COMISO PALA	AUSTIN	78726	TRAVIS	3086087.00030875	1.01307449986076E7	30.43475303	-97.82791479	"(30.43475303, -97.82791479)"	6	463A	ME36
16-00164974	AFDWILPR	AFD - Wildfire Concern / Presentation	Austin Fire Department	Spot311 Interface	Closed	2016-08-15 13:38:17 UTC	2016-07-01 22:45:48 UTC	2016-08-15 13:38:17 UTC	2016-08-15 13:38:17 UTC	"12005 MILLWRIGHT PKWY, AUSTIN, TX 78750"	12005	MILLWRIGHT	AUSTIN	78750	WILLIAMSON	3094078.58601159	1.01368311668213E7	30.45098593	-97.80212353	"(30.45098593, -97.80212353)"	6	433R	MF38
16-00166425	AFDWILPR	AFD - Wildfire Concern / Presentation	Austin Fire Department	Spot311 Interface	Closed	2016-08-15 13:37:02 UTC	2016-07-03 22:09:30 UTC	2016-08-15 13:37:03 UTC	2016-08-15 13:37:02 UTC	"11316 BRISTLE OAK TRL, AUSTIN, TX 78750"	11316	BRISTLE OAK	AUSTIN	78750	WILLIAMSON	3089668.25291989	1.01394079281842E7	30.45834435	-97.81593186	"(30.45834435, -97.81593186)"	6	433K	ME38
18-00307202	AFDWILPR	AFD - Wildfire Concern / Presentation	Austin Fire Department	Phone	Closed	2018-09-19 09:55:00 UTC	2018-09-14 16:00:00 UTC	2018-09-19 09:55:00 UTC	2018-09-19 09:55:00 UTC														

Select country_name,year
From `bigquery-public-data.census_bureau_international.birth_death_growth_rates`
where country_name="France"

country_name	year
France	1990
France	1991
France	1992
France	1993
France	1994
France	1995
France	1996
France	1997
France	1998
France	1999
France	2000
France	2001
France	2002
France	2003
France	2004
France	2005
France	2006
France	2007
France	2008
France	2009
France	2010
France	2011
France	2012
France	2013
France	2014
France	2015
France	2016
France	2017
France	2018
France	2019
France	2020
France	2021
France	2022
France	2023
France	2024
France	2025
France	2026
France	2027
France	2028
France	2029
France	2030
France	2031
France	2032
France	2033
France	2034
France	2035
France	2036
France	2037
France	2038
France	2039
France	2040
France	2041
France	2042
France	2043
France	2044
France	2045
France	2046
France	2047
France	2048
France	2049
France	2050

Select country_name,year
From `bigquery-public-data.census_bureau_international.birth_death_growth_rates`
where country_name="France"
and year = 2000
country_name	year
France	2000

Select country_name,year, crude_birth_rate
From `bigquery-public-data.census_bureau_international.birth_death_growth_rates`
where country_name="France" oR  year = 2000 or crude_birth_rate > 0
limit 10
country_name	year	crude_birth_rate
Chad	1993	47.8
Chad	1994	47.71
Chad	1995	48.02
Chad	1996	48.35
Chad	1997	48.74
Chad	1998	49.24
Chad	1999	49.82
Chad	2000	50.48
Chad	2001	51.2
Chad	2002	51.95

Select country_name,year, crude_birth_rate
From `bigquery-public-data.census_bureau_international.birth_death_growth_rates`
where not country_name= "France" 
limit 10
country_name	year	crude_birth_rate
Chad	1993	47.8
Chad	1994	47.71
Chad	1995	48.02
Chad	1996	48.35
Chad	1997	48.74
Chad	1998	49.24
Chad	1999	49.82
Chad	2000	50.48
Chad	2001	51.2
Chad	2002	51.95

Select MIN(duration_minutes)
From `bigquery-public-data.austin_bikeshare.bikeshare_trips`
f0_
0

Select MAX(duration_minutes)
From `bigquery-public-data.austin_bikeshare.bikeshare_trips`
f0_
34238

Select AVG(duration_minutes)
From `bigquery-public-data.austin_bikeshare.bikeshare_trips`
f0_
29.032961731747758

Select COUNT(duration_minutes)
From `bigquery-public-data.austin_bikeshare.bikeshare_trips`
f0_
1216805

Select SUM(duration_minutes)
From `bigquery-public-data.austin_bikeshare.bikeshare_trips`
f0_
35327453
