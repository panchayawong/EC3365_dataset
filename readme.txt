Badi H. Baltagi, Peter H. Egger, and Michaela Kesina, "Firm-level
Productivity Spillovers in China's Chemical Industry: A Spatial
Hausman-Taylor Approach", Journal of Applied Econometrics, Vol. 31,
No. 1, 2016, pp. 214-248.

The data used in the article are information on Chinese firms in
the Chemical industry. It is retrieved by firm-level surveys.

The file bek-data.txt contains the data. There are in total 12,552
firms observed over three years (2004-2006), yielding a total number of
observations of 37,656.

The columns contain the following variables in the order given: 
year: 			2004-2006
id:			individual firm identifier
lsales:			sales (in logs)
lk:			capital (in logs)
lemp:			labor (in logs)
h:			share of skilled labor
lm:			materials (in logs)
fdir:                   foreign-owned capital ratio
expid:			exporter (binary)
innd:                   intangible asset intensity (binary)
strd:                   state-owned/publicly-owned (binary)
lat:                    latitude (in radians)
lon:                    longitude (in radians)

The file functions.m contains the matlab functions that are needed to
reproduce the estimators in the tables.

Both files are ASCII files in DOS format. They are zipped in the file
bek-files.zip. Unix/Linux users should use "unzip -a".



