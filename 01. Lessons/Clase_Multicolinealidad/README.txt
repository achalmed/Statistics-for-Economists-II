NOTE TO THE USER:

This README.DOC file details the data files included in the data disk. For each example, appendix, section, or table for which there is a data file, README.DOC contains the following information: the name of the example, appendix, section, or table; the filename under which the data are saved; the name of the series in the file; the description of the series; the period covered; and the frequency of the series (A for annual, Q for quarterly, M monthly, N for cross-section series). 

There are two versions for each file. First, each file has an Excel worksheet 3.0 version under the extension XLS. Second, each file has an ASCII (TAB delimited) file under the extension TXT. 

The variable names appear in the first row. The first column of each file contains the variable DATE or the variable OBS (for observations) in the case of cross-sectional data.

Many data files have been obtained from CITIBASE. However, not all CITIBASEs work with the same variable definitions. Therefore, the data contained here may differ from the data you are able to extract from CITIBASE directly. When trying to replicate the textbook examples some differences might arise, since the data used in this data disk may slightly differ from the one used in the book.

-------------------------------------------------------------------------------------------------------------------------------
EXAMPLE/APPENDIX/TABLE 	| FILENAME 
SERIES		|DESCRIPTION						|PERIOD      	|FREQ.
-------------------------------------------------------------------------------------------------------------------------------

**************************************************************************************
EXAMPLE 3.2			FILENAME: EX32

GC		PERSONAL CONSUMPTION EXPENDITURES		1954:1-1995:2	Q
GYD		AGGREGATE DISPOSABLE INCOME			1954:1-1995:2	Q
	
**************************************************************************************
EXAMPLE 3.3 			FILENAME: EX33

GCDAN		PERSONAL CONSUMPTION EXPENDITURES 		1959:1-1995:2 	Q
		NEW AUTOS
GWY		NAT'L INCOME: WAGES AND SALARIES 		1959:1-1995:2 	Q

**************************************************************************************
EXAMPLE 3.5			FILENAME: EX35	

ENB		NUMBER OF INDIVIDUALS PER THOUSAND OF	1-50 		N
		POPULATION ENROLLED IN INSTITUTIONS OF 		
		PUBLIC HIGHER EDUCATION	
ENV		NUMBER OF INDIVIDUALS PER THOUSAND OF	1-50 		N
		POPULATION ENROLLED IN INSTITUTIONS OF 	
		PRIVATE HIGHER EDUCATION

NOTE: THESE VARIABLES ARE ALSO USED IN SECTION 2.6.

**************************************************************************************
EXAMPLE 4.1			FILENAME: EX41

GMPY		PERSONAL INCOME: TOTAL (BIL$,SAAR) 		1975:1-1995:9 	M
FYGN3		INTEREST RATE: U.S. TREASURY BILLS, AUCTION 	1975:1-1995:9 	M
		AVG,3-MO.(% PER ANN,NSA) 
PUNEW		CPI-U: ALL ITEMS (82-84=100,SA) 			1975:1-1995:9	M
GCDAN 	IS IN EXAMPLE 3.3

**************************************************************************************
EXAMPLE 4.2			FILENAME: EX42

FYGN3		INTEREST RATE: U.S.TREASURY BILLS, AUCTION	1959:1-1996:2	M
		AVG,3-MO.(% PER ANN,NSA)
IP		INDUSTRIAL PRODUCTION: TOTAL INDEX 		1959:1-1992:2	M
		(1987=100,SA) 
FM2 		MONEY STOCK:M2(M1+O'NITE RPS,EURO$,G/P&	1959:1-1996:2	M
		B/D MMMFS&SAV&SM TIME DEP)(BIL$,SA)
PW   		PRODUCER PRICE INDEX: ALL COMMODITIES 	1959:1-1996:2	M
		(82=100,NSA) 

**************************************************************************************
EXAMPLE 4.3	

SEE FILE 3.2

**************************************************************************************
EXAMPLE 4.5			FILENAME: EX45

RTDR 		RETAIL SALES: DURABLE GOODS STORES, 		1967:1-1995:8 	M
		TOTAL, S.A 
IVRDR 		RETAIL INVENTORIES: DURABLE GOODS 		1967:1-1995:7 	M
		(MIL$,EOM,SA) 
FYCP  		INTEREST RATE: COMMERCIAL PAPER, 6-MONTH 	1967:1-1995:8 	M
		(% PER ANNUM,NSA) 
LEH 		AVG HR EARNINGS OF PROD WKRS: TOTAL 		1967:1-1995:8 	M
		PRIVATE NONAGRIC ($,SA) 
PUCD 		CPI-U: DURABLES (82-84=100,SA) 			1967:1-1995:8 	M

**************************************************************************************
EXAMPLE 5.3			FILENAME: EX53

WAGE		WAGE							1-206		N
SEX		1 IF FEMALE						1-206		N
ED		EDUCATION						1-206		N
AGE		AGE							1-206		N
NONWH	1 IF NON-HISPANIC, NON-WHITE			1-206		N
HISP		1 IF HISPANIC						1-206		N

**************************************************************************************
EXAMPLE 6.1			FILENAME: EX61

HEXP		ANNUAL HOUSING EXPENDITURES,			1-20		N
		THOUSANDS OF DOLLARS
INC		ANNUAL FAMILY INCOME,				1-20		N
		THOUSANDS OF DOLLARS
		
**************************************************************************************
EXAMPLE 6.4			FILENAME: EX64

Q		QUANTITY OF DELIVERED ENERGY (QUADS)		1960-1985	A 
P		PRICE OF QUAD (1975 DOLLARS)			1960-1985	A
INC		TOTAL INCOME (INCOME PER HOUSEHOLDS 		1960-1985	A
		TIMES NUMBER OF HOUSEHOLDS) (1975 DOLLARS)

NOTE: Q, P, AND INC ARE **NOT** IN LOGARITHMS. YOU SHOULD TAKE LOG TO REPRODUCE THE EXAMPLE IN THE BOOK.

**************************************************************************************
EXAMPLE 6.6	

DATA USED IN EXAMPLE 4.2	

**************************************************************************************
EXAMPLE 6.7 			FILENAME: EX67
  	
GCQ  		PERSONAL CONSUMPTION 				1947:1-1995:3	Q
GYDQ		DISPOSABLE PERSONAL INCOME: TOTAL 		1947:1-1995:3 	Q
		(BIL.87$)(T.2.1)

**************************************************************************************
EXAMPLE 7.3			FILENAME: EX73

E		1 IF STATE IS IN EASTERN REGION			1-50 		N
N		1 IF STATE IS IN NORTHERN REGION			1-50 		N
S		1 IF STATE IS IN SOUTHERN REGION			1-50 		N
W		1 IS STATE IS IN WESTERN REGION			1-50 		N
PCEXP		PER CAPITA STATE AND LOCAL GOVERNMENT	1-50 		N
		EXPENDITURES, DOLLARS
EXP		EXPENDITURES OF U.S. STATE AND LOCAL 		1-50 		N
		GOVERNMENTS (50 STATES)
PCAID		PER CAPITA FEDERAL AIDE TO STATE AND		1-50 		N
		LOCAL GOVERNMENTS, DOLLARS
AID		FEDERAL GRANTS-IN-AID				1-50 		N
POP		POPULATION OF STATES				1-50 		N
DEN		POPULATION DENSITY, THOUSANDS PER		1-50 		N
		SQUARE MILE
DPOP		PERCENTAGE CHANGE IN POPULATION FROM	1-50 		N
		1960 TO 1970
URB		PERCENTAGE OF POPULATION LIVING IN 		1-50 		N
		METROPOLITAN AREAS (SAMSAS)
PCINC		PER CAPITA PERSONAL INCOME, DOLLARS		1-50 		N
INC		INCOME OF STATES					1-50 		N
PS		POPULATION OF PRIMARY AND SECONDARY 		1-50 		N
		SCHOOL CHILDREN

THE DATA ARE DISPLAYED ON TABLE 6.2

**************************************************************************************
EXAMPLE 8.2	

DATA USED IN EXAMPLE 4.2	

**************************************************************************************
EXAMPLE 8.3	

DATA USED IN EXAMPLE 4.2	

**************************************************************************************
EXAMPLE 9.1 (PART A)	

DATA USED IN EXAMPLE 3.2

**************************************************************************************
EXAMPLE 9.1 (PART B)		FILENAME: EX91B

FYGN3		INTEREST RATE: U.S.TREASURY BILLS,AUCTION	1950:1-1995:3	M
		AVG,3-MO.(% PER ANN,NSA)

**************************************************************************************
EXAMPLE 9.2			FILENAME: EX92

IVMD	   	MFG INVENTORIES: DURABLE GOODS 		1983:1-1987:5 	M
		INDUSTRIES, TOTAL (MIL$,SA) 
MDS      	MFG SHIPMENTS: DURABLE GOODS 			1983:1-1987:5 	M
		INDUSTRIES, TOTAL (MIL$,SA) 
MDU     	MFG UNFILLED ORDERS: DURABLE 			1983:1-1987:5 	M
		GOODS INDUSTRIES, TOTAL (MIL$,SA ) 
PWMD  	PRODUCER PRICE INDEX: TOTAL DURABLE 		1983:1-1987:5 	M
		GOODS (82=100,NSA) 

**************************************************************************************
EXAMPLE 9.5			

DATA USED IN EXAMPLE 7.3	

**************************************************************************************
EXAMPLE 9.6			FILENAME: EX96

CUSIP		FIRM ID (45 FIRMS OVER 7 YEARS)			1-315		N
P		PATENTS						1-315		N 
RND		LOG OF R&D EXPENDITURES	(LAGGED 5 PERIODS)	1-315		N 

**************************************************************************************
EXAMPLE 10.1	

DATA USED IN EXAMPLE 6.7

**************************************************************************************
EXAMPLE 10.3	

DATA USED IN EXAMPLE 6.7

**************************************************************************************
EXAMPLE 10.4			FILENAME: EX104	

RAAA		RAAA=.01*FYAAAC					1950:1-1996:2 	M
		FYAAAC= BOND YIELD: MOODY'S AAA CORPORATE 
		(% PER ANNUM)
R3		R3=.01*FYGM3						1950:1-1996:2 	M
		FYGM3= INTEREST RATE: U.S.TREASURY BILLS,
		SEC MKT,3-MO.(% PER ANN,NSA)
IP		INDUSTRIAL PRODUCTION: TOTAL INDEX		1950:1-1996:2 	M
 		(1987=100,SA)
GIP		GIP=(IP-IP(-1))/IP(-1)					1950:1-1996:2 	M
PW		PRODUCER PRICE INDEX: ALL COMMODITIES		1950:1-1996:2 	M
		 (82=100,NSA)
GPW		GPW=(PW-PW(-1))/PW(-1)				1950:1-1996:2 	M

**************************************************************************************
EXAMPLE 10.5			FILENAME: EX105	

RETURNSP	RETURNSP=(FSPCOM-FSPCOM(-1))/FSPCOM(-1) 	1960:1-1996:2 	M
				+ .01*FSDXP/12	
FSPCOM	S&P'S COMMON STOCK PRICE INDEX:			1960:1-1996:2 	M
		COMPOSITE (1941-43=10)
FSDXP		S&P'S COMPOSITE COMMON STOCK:			1960:1-1996:2 	M
		DIVIDEND YIELD (% PER ANNUM)
R3		R3=.01*FYGM3						1960:1-1996:2 	M
		FYGM3= INTEREST RATE: U.S.TREASURY BILLS,
		SEC MKT,3-MO.(% PER ANN,NSA)
PW		PRODUCER PRICE INDEX: ALL COMMODITIES		1960:1-1996:2 	M
		(82=100,NSA)
GPW		GPW=(PW-PW(-1))/PW(-1)				1960:1-1996:2 	M

**************************************************************************************
EXAMPLE 11.3			FILENAME: EX113

PUB12		DUMMY VARIABLE EQUAL TO 1 IF 1 OR 2 		1-95		N
		CHILDREN ARE IN PUBLIC SCHOOL
PUB34		DUMMY VARIABLE EQUAL TO 1 IF 3 OR 4 		1-95		N
		CHILDREN ARE IN PUBLIC SCHOOL	
PUB5		DUMMY VARIABLE EQUAL TO 1 IF 5 OR MORE 	1-95		N
		CHILDREN ARE IN PUBLIC SCHOOL	
PRIV		DUMMY VARIABLE EQUAL TO 1 IF THE FAMILY 	1-95		N
		HAS 1 OR MORE CHILDREN IN PRIVATE SCHOOL	
YEARS		NUMBER OF YEARS LIVING IN TROY COMMUNITY	1-95		N
SCHOOL	DUMMY VARIABLE EQUAL TO 1 IF INDIVIDUAL IS 	1-95		N
		EMPLOYED AS A TEACHER (PUBLIC OR PRIVATE)	
LOGINC	LOGARITHM OF ANNUAL HOUSEHOLD INCOME	1-95		N
PTCON		NATURAL LOGARITHM OF PROPERTY TAXES PAID 	1-95		N
		PER YEAR, DOLLARS	
YESVM		DUMMY VARIABLE EQUAL TO 1 IF INDIVIDUAL 	1-95		N
		VOTED YES IN ELECTION; 0 IF VOTED NO	
LOGEDUC	LOGARITHM OF EACH INDIVIDUAL'S DESIRED 	1-95		N
		LEVEL OF PER-PUPIL SCHOOL SPENDING	

THE DATA ARE DISPLAYED ON TABLE 11.8

**************************************************************************************
EXAMPLE 11.7	

DATA USED IN EXAMPLE 11.3

**************************************************************************************
EXAMPLE 12.2	

DATA USED IN EXAMPLE 7.3

**************************************************************************************
EXAMPLE 13.1 			FILENAME: EX131	

PHO   		PRICE OF HEATING OIL				1979:1-1988:6 	M
QHO		PRODUCTION OF HEATING OIL			1979:1-1988:6 	M
NHO		INVENTORY OF HEATING OIL				1979:1-1988:6 	M

THE DATA ARE DISPLAYED ON TABLE 13.6

**************************************************************************************
TABLE	13.5		FILENAME: TAB135

GC82   		REAL AGGREGATE PERSONAL CONSUMPTION (C)	1950:1-1988:1 	Q
GPI82		REAL GROSS DOMESTIC INVESTMENT (I)		1950:1-1988:1 	Q
FYGN3		INTEREST RATE ON 3-MONTH TREASURY BILLS (R)	1950:1-1988:1 	Q
GNP		REAL GNP (NET OF EXPORTS AND IMPORTS) (=C+I+G)1950:1-1988:1 	Q
GGE82		REAL GOVERNMENT SPENDING			1950:1-1988:1 	Q
M		REAL MONEY STOCK, NARROWLY DEFINED (M1)	1950:1-1988:1 	Q

**************************************************************************************
APPENDIX 14.1		FILENAME: A141

GC		PERSONAL CONSUMPTION EXPENDITURES 		1959:1-1995:4 	Q
		(SAAR, BIL.$)
GDP		GROSS DOMESTIC PRODUCT (SAAR, BIL.$)		1959:1-1995:4 	Q
PUNEW		CPI-U: ALL ITEMS (SA, 1982-84=100)			1959:1-1995:4 	Q
GINQF		PRIVATE NONRESIDENTIAL FIXED INVESTMENT	1959:1-1995:4 	Q
		(SAAR, BIL.FXD.1992$)
GVQF		REAL CHANGE IN BUSINESS INVENTORIES 		1959:1-1995:4 	Q
		(SAAR, BIL.FXD.1992$)
GIRQF		PRIVATE RESIDENTIAL FIXED INVESTMENT 		1959:1-1995:4 	Q
		(SAAR, BIL.FXD.1992$)
GIMQF		REAL IMPORTS OF GOODS AND SERVICES 		1959:1-1995:4 	Q
		(SAAR, BIL.FXD.1992$)
FYAAAC	MOODY'S SEASONED AAA CORPORATE BOND 	1959:1-1995:4 	Q
		YIELD (% P.A.)
FYGN3		3-MONTH TREASURY BILLS (% P.A.)			1959:1-1995:4 	Q
GTXL		INDIRECT BUSINESS TAX AND NONTAX LIABILITY 	1959:1-1995:4 	Q
		(SAAR, BIL. $)                       
LHUR		CIVILIAN UNEMPLOYMENT RATE (SA, %)		1959:1-1995:4 	Q
LBCPU		COMPENSATION PER HOUR, NONFARM BUSINESS 	1959:1-1995:4 	Q
		(1992=100)
GCQF		REAL PERSONAL CONSUMPTION EXPENDITURES 	1959:1-1995:4 	Q
		(SAAR, BIL.FXD.1992$)	
GMPTX		PERSONAL TAX AND NONTAX PAYMENTS 		1959:1-1995:4 	Q
		(SAAR, BIL.$)		
GGEQF		REAL GOVT CONSUMPTION EXPENDITURES		1959:1-1995:4 	Q
		& GROSS INVESTMENT (SAAR,BIL.FXD.92$)
GDPPOT	POTENTIAL GDP {CBO} (BILLION $)               		1960:1-1995:4 	Q
FM2		MONEY STOCK: M2 (SA, BIL.$)				1959:1-1995:4 	Q
NETWRTH	HOUSEHOLD NET WORTH (SAAR, BIL. FXD. 92$)	1959:1-1995:4 	Q
EEPRPC	REFINERS' ACQUISITION COST OF CRUDE OIL: 	1960:1-1995:4 	Q
		COMPOSITE: DOE ($/BBL)       
GPJVA		CORPORATE PROFITS WITH IVA AND CCADJ 		1959:1-1995:4 	Q
		(SAAR, BIL. $)                   
LBOUTU	NONFARM BUSINESS SECTOR: OUTPUT PER HOUR 	1959:1-1995:4 	Q
		OF ALL PERSONS (SA, 1992=100)
GPT		TRANSFER PAYMENTS TO PERSONS (SAAR, BIL.$)	1959:1-1995:4 	Q
GEXQF		REAL EXPORTS OF GOODS AND SERVICES 		1959:1-1995:4 	Q
		(SAAR, BIL.FXD.1992$)

**************************************************************************************
EXAMPLE 14.4	

DATA USED IN EXAMPLE 13.1

**************************************************************************************
EXAMPLE 15.1		FILENAME: EX151

RT531R		RETAIL SALES: DEPARTMENT STORES (MIL$,SA) 	1986:1-1995:12 	M

**************************************************************************************
EXAMPLE 15.2		FILENAME: EX152

HS6FR		HOUSING STARTS: TOTAL NEW PRIV HOUSING 	1986:1-1995:10 	M
		UNITS (THOUS.,NSA)

**************************************************************************************
EXAMPLE 15.3	

DATA USED IN EXAMPLE 15.2

**************************************************************************************
TABLE 15.1		FILENAME: TAB151

FSPCOM	S&P'S COMMON STOCK PRICE INDEX: 		1980:1-1996:2	M
		COMPOSITE (1941-43=10)

**************************************************************************************
TABLE 15.2 		FILENAME: TAB152
	
RCAR6T	RETAIL SALES:NEW PASSENGER CARS,TOTAL	1980:1-1996:2	M
 		DOMESTICS+IMPORTS(THOUS,NSA)

**************************************************************************************
EXAMPLE 16.1		FILENAME: EX161	

FYGN3   	INTEREST RATE: U.S.TREASURY BILLS,AUCTION 	1950:1-1996:3 	M
		AVG,3-MO.(% PER ANN,NSA)

**************************************************************************************
EXAMPLE 16.4		FILENAME: EX164

OIL   		PRICE OF CRUDE OIL IN 1967 DOLLARS 		1870-1987 	A
COPPER	PRICE OF COPPER IN 1967 DOLLARS 			1870-1987 	A
LUMBER	PRICE OF LUMBER IN 1967 DOLLARS 			1870-1987 	A

THE DATA ARE DISPLAYED ON TABLE 16.4

**************************************************************************************
EXAMPLE 16.5		FILENAME: EX165

GCQ  		PERSONAL CONSUMPTION EXPEND - TOTAL		1960:1-1995:4	Q
GYDQ		DISPOSABLE PERSONAL INCOME 			1960:1-1995:4	Q
		IN CHAINED (1992) DOLLARS

**************************************************************************************
SECTION 16.2	

DATA USED IN EXAMPLE 17.1

**************************************************************************************
EXAMPLE 17.1		FILENAME: EX171

GVUQ		CHANGE IN BUSINESS INVENTORIES - NONFARM	1960:1-1995:4	Q
		(IN 1987 CONSTANT DOLLARS)
	
THE DATA ARE DISPLAYED ON TABLE 19.1

**************************************************************************************
EXAMPLE 17.3	

DATA USED IN EXAMPLE 16.1

**************************************************************************************
EXAMPLE 18.1	

DATA USED IN EXAMPLE 16.1

**************************************************************************************
EXAMPLE 18.3	

DATA USED IN EXAMPLE 16.1

**************************************************************************************
TABLE 19.1 		

DATA USED IN EXAMPLE 17.1

**************************************************************************************
SECTION 19.2	

DATA USED IN EXAMPLE 17.1

**************************************************************************************
SECTION 19.6	

DATA USED IN EXAMPLE 4.2 AND IN EXAMPLE 10.4

**************************************************************************************






