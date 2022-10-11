
This Report is an Analysis of School Math and Reading Scores Based on Budget and Size with the conclusion summarized at the end of the report.



The data source came from 2 files: schools_complete and students_complete.

This summarizes the 15 schools in our District, PyCity,  for this study.

#1 Created a District Summary
	Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	15			39,170		$24,649,428.00	78.985371	      	81.87784	           	74.980853	   	 85.805463		65.17232

#2 Created a School Summary

School Type	School Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Bailey High School	District	4976	$3,124,928.00	$628.00			77.048432			81.033963			66.680064		81.933280		54.642283
Cabrera High School	Charter	1858	$1,081,356.00	$582.00			83.061895			83.975780			94.133477		97.039828		91.334769
Figueroa High School	District	2949	$1,884,411.00	$639.00			76.711767			81.158020			65.988471		80.739234		53.204476
Ford High School		District	2739	$1,763,916.00	$644.00			77.102592			80.746258			68.309602		79.299014		54.289887
Griffin High School	Charter	1468	$917,500.00		$625.00			83.351499			83.816757			93.392371		97.138965		90.599455
Hernandez High School	District	4635	$3,022,020.00	$652.00			77.289752			80.934412			66.752967		80.862999		53.527508
Holden High School	Charter	427	$248,087.00		$581.00			83.803279			83.814988			92.505855		96.252927		89.227166
Huang High School		District	2917	$1,910,635.00	$655.00			76.629414			81.182722			65.683922		81.316421		53.513884
Johnson High School	District	4761	$3,094,650.00	$650.00			77.072464			80.966394			66.057551		81.222432		53.539172
Pena High School		Charter	962	$585,858.00		$609.00			83.839917			84.044699			94.594595		95.945946		90.540541
Rodriguez High School	District	3999	$2,547,363.00	$637.00			76.842711			80.744686			66.366592		80.220055		52.988247
Shelton High School	Charter	1761	$1,056,600.00	$600.00			83.359455			83.725724			93.867121		95.854628		89.892107
Thomas High School	Charter	1635	$1,043,130.00	$638.00			83.418349			83.848930			93.272171		97.308869		90.948012
Wilson High School	Charter	2283	$1,319,574.00	$578.00			83.274201			83.989488			93.867718		96.539641		90.582567
Wright High School	Charter	1800	$1,049,400.00	$583.00			83.682222			83.955000			93.333333		96.611111		90.333333

#3 Derived the top 5 schools with % Passing for Math and Reading
	School 			Type	School Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
	Cabrera High School	Charter		1858		$1,081,356.00		$582.00			83.061895			83.975780			94.133477		97.039828		91.334769
	Thomas High School	Charter		1635		$1,043,130.00		$638.00			83.418349			83.848930			93.272171		97.308869		90.948012
	Griffin High School	Charter		1468		$917,500.00			$625.00			83.351499			83.816757			93.392371		97.138965		90.599455
	Wilson High School	Charter		2283		$1,319,574.00		$578.00			83.274201			83.989488			93.867718		96.539641		90.582567
 	Pena High School		Charter		962		$585,858.00			$609.00			83.839917			84.044699			94.594595		95.945946		90.540541

#4 Derived the bottom 5 schools with % Not Passing Match and Reading
	School 			Type	School Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
	Rodriguez High School	District	3999			$2,547,363.00		$637.00			76.842711			80.744686			66.366592		80.220055		52.988247
	Figueroa High School	District	2949			$1,884,411.00		$639.00			76.711767			81.158020			65.988471		80.739234		53.204476
	Huang High School		District	2917			$1,910,635.00		$655.00			76.629414			81.182722			65.683922		81.316421		53.513884
	Hernandez High School	District	4635			$3,022,020.00		$652.00			77.289752			80.934412			66.752967		80.862999		53.527508
	Johnson High School	District	4761			$3,094,650.00		$650.00			77.072464			80.966394			66.057551		81.222432		53.539172

#5 Checked Match Scores by Grade
				9th		10th		11th		12th
Bailey High School	77.083676	76.996772	77.515588	76.492218
Cabrera High School	83.094697	83.154506	82.765560	83.277487
Figueroa High School	76.403037	76.539974	76.884344	77.151369
Ford High School		77.361345	77.672316	76.918058	76.179963
Griffin High School	82.044010	84.229064	83.842105	83.356164
Hernandez High School	77.438495	77.337408	77.136029	77.186567
Holden High School	83.787402	83.429825	85.000000	82.855422
Huang High School		77.027251	75.908735	76.446602	77.225641
Johnson High School	77.187857	76.691117	77.491653	76.863248
Pena High School		83.625455	83.372000	84.328125	84.121547
Rodriguez High School	76.859966	76.612500	76.395626	77.690748
Shelton High School	83.420755	82.917411	83.383495	83.778976
Thomas High School	83.590022	83.087886	83.498795	83.497041
Wilson High School	83.085578	83.724422	83.195326	83.035794
Wright High School	83.264706	84.010288	83.836782	83.644986

#6 Checked Reading Scores by Grade

				9th		10th		11th		12th
Bailey High School	81.303155	80.907183	80.945643	80.912451
Cabrera High School	83.676136	84.253219	83.788382	84.287958
Figueroa High School	81.198598	81.408912	80.640339	81.384863
Ford High School		80.632653	81.262712	80.403642	80.662338
Griffin High School	83.369193	83.706897	84.288089	84.013699
Hernandez High School	80.866860	80.660147	81.396140	80.857143
Holden High School	83.677165	83.324561	83.815534	84.698795
Huang High School		81.290284	81.512386	81.417476	80.305983
Johnson High School	81.260714	80.773431	80.616027	81.227564
Pena High School		83.807273	83.612000	84.335938	84.591160
Rodriguez High School	80.993127	80.629808	80.864811	80.376426
Shelton High School	84.122642	83.441964	84.373786	82.781671
Thomas High School	83.728850	84.254157	83.585542	83.831361
Wilson High School	83.939778	84.021452	83.764608	84.317673
Wright High School	83.833333	83.812757	84.156322	84.073171

#7 Looked at the Correlation of Scores Based on School Spending

	School 		Type		School Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing	Spending Ranges (Per Student)
Bailey High School	District	4976				$3,124,928.00		$628.00			77.048432			81.033963			66.680064		81.933280		54.642283		$585-630
Cabrera High School	Charter	1858				$1,081,356.00		$582.00			83.061895			83.975780			94.133477		97.039828		91.334769		<$585
Figueroa High School	District	2949				$1,884,411.00		$639.00			76.711767			81.158020			65.988471		80.739234		53.204476		$630-645
Ford High School		District	2739				$1,763,916.00		$644.00			77.102592			80.746258			68.309602		79.299014		54.289887		$630-645
Griffin High School	Charter	1468				$917,500.00			$625.00			83.351499			83.816757			93.392371		97.138965		90.599455		$585-630
Hernandez High School	District	4635				$3,022,020.00		$652.00			77.289752			80.934412			66.752967		80.862999		53.527508		$645-680
Holden High School	Charter	427				$248,087.00			$581.00			83.803279			83.814988			92.505855		96.252927		89.227166		<$585
Huang High School		District	2917				$1,910,635.00		$655.00			76.629414			81.182722			65.683922		81.316421		53.513884		$645-680
Johnson High School	District	4761				$3,094,650.00		$650.00			77.072464			80.966394			66.057551		81.222432		53.539172		$645-680
Pena High School		Charter	962				$585,858.00			$609.00			83.839917			84.044699			94.594595		95.945946		90.540541		$585-630
Rodriguez High School	District	3999				$2,547,363.00		$637.00			76.842711			80.744686			66.366592		80.220055		52.988247		$630-645
Shelton High School	Charter	1761				$1,056,600.00		$600.00			83.359455			83.725724			93.867121		95.854628		89.892107		$585-630
Thomas High School	Charter	1635				$1,043,130.00		$638.00			83.418349			83.848930			93.272171		97.308869		90.948012		$630-645
Wilson High School	Charter	2283				$1,319,574.00		$578.00			83.274201			83.989488			93.867718		96.539641		90.582567		<$585
Wright High School	Charter	1800				$1,049,400.00		$583.00			83.682222			83.955000			93.333333		96.611111		90.333333		<$585

#8 Looked at Spending Rates per Student to Average Scores

					Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Spending Ranges (Per Student)					
<$585					83.455399	83.933814	93.460096	96.610877	90.369459
$585-630				81.899826	83.155286	87.133538	92.718205	81.418596
$630-645				78.518855	81.624473	73.484209	84.391793	62.857656
$645-680				76.997210	81.027843	66.164813	81.133951	53.526855


#9 Derived Scores Based on School Size

	School 		Type	School Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing	School Size
Bailey High School	District	4976			$3,124,928.00		$628.00			77.048432			81.033963			66.680064		81.933280		54.642283	Large (2000-5000)
Cabrera High School	Charter	1858			$1,081,356.00		$582.00			83.061895			83.975780			94.133477		97.039828		91.334769	Medium (1000-2000)
Figueroa High School	District	2949			$1,884,411.00		$639.00			76.711767			81.158020			65.988471		80.739234		53.204476	Large (2000-5000)
Ford High School		District	2739			$1,763,916.00		$644.00			77.102592			80.746258			68.309602		79.299014		54.289887	Large (2000-5000)
Griffin High School	Charter	1468			$917,500.00			$625.00			83.351499			83.816757			93.392371		97.138965		90.599455	Medium (1000-2000)
Hernandez High School	District	4635			$3,022,020.00		$652.00			77.289752			80.934412			66.752967		80.862999		53.527508	Large (2000-5000)
Holden High School	Charter	427			$248,087.00			$581.00			83.803279			83.814988			92.505855		96.252927		89.227166	Small (<1000)
Huang High School		District	2917			$1,910,635.00		$655.00			76.629414			81.182722			65.683922		81.316421		53.513884	Large (2000-5000)
Johnson High School	District	4761			$3,094,650.00		$650.00			77.072464			80.966394			66.057551		81.222432		53.539172	Large (2000-5000)
Pena High School		Charter	962			$585,858.00			$609.00			83.839917			84.044699			94.594595		95.945946		90.540541	Small (<1000)
Rodriguez High School	District	3999			$2,547,363.00		$637.00			76.842711			80.744686			66.366592		80.220055		52.988247	Large (2000-5000)
Shelton High School	Charter	1761			$1,056,600.00		$600.00			83.359455			83.725724			93.867121		95.854628		89.892107	Medium (1000-2000)
Thomas High School	Charter	1635			$1,043,130.00		$638.00			83.418349			83.848930			93.272171		97.308869		90.948012	Medium (1000-2000)
Wilson High School	Charter	2283			$1,319,574.00		$578.00			83.274201			83.989488			93.867718		96.539641		90.582567	Large (2000-5000)
Wright High School	Charter	1800			$1,049,400.00		$583.00			83.682222			83.955000			93.333333		96.611111		90.333333	Medium (1000-2000)

#10 Summarized Scores on School Size

			Average Math Score	Average Reding Score	% Passing Math	% Passing Reading	% Overall Passing
School Size					
Small (<1000)	 83.821598			83.929843			93.550225		96.099437		89.883853
Medium (1000-2000) 83.374684			83.864438			93.599695		96.790680		90.621535
Large (2000-5000)	 77.746417			81.344493			69.963361		82.766634		58.286003

#11 Finding:

		Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
School Type					
Charter	83.473852			83.896421			93.620830		96.586489		90.432244
District	76.956733			80.966636			66.548453		80.799062		53.672208


In conclusion , the PyCity Schools Analysis shows that size not budget contributes to better math and reading scores and Charter Schools have better scores than District schools.
More analysis needs to be done to see if that is based on size.

# PyCity Schools Analysis

* As a whole, schools with higher budgets, did not yield better test results. By contrast, schools with higher spending 645-675 per student actually underperformed compared to schools with smaller budgets (585 per student).

* As a whole, smaller and medium sized schools dramatically out-performed large sized schools on passing math performances (89-91% passing vs 67%).

* As a whole, charter schools out-performed the public district schools across all metrics. However, more analysis will be required to glean if the effect is due to school practices or the fact that charter schools tend to serve smaller student populations per school. 
