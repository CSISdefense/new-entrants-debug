# new-entrants-debug

This is a public repository set up by the [Defense-Industrial Initiative Group (DIIG)](http://csis.org/program/national-security-program-industry-resources) at the [Center for Strategic and International Studies](http://csis.org/) as part of a larger project tracking the performance of new entrants in the defense market.  

Please feel free to refer to the data and scripts; please do not cite without contacting DIIG.  


## Notes

* Analysis based on data from the [Federal Procurement Data System (FPDS)](https://www.fpds.gov/fpdsng_cms/index.php/en/)  
    + Refer to [data dictionary](https://github.com/CSISdefense/Lookup-Tables/blob/master/dictionary/FPDSNG_DataDictionary_v1_5.pdf), updated November 2017  
    
* Navigate the FPDS dataset with our [look-up tables](https://github.com/CSISdefense/Lookup-Tables)


## Directory

* Raw data used can be downloaded from DIIG's [Vendor](https://github.com/CSISdefense/Vendor) repository: [Vendor.SP_DunsnumberNewEntrants_all.zip](https://github.com/CSISdefense/Vendor/blob/master/New%20Entrants/Data/Raw%20Data/FPDS/Vendor.SP_DunsnumberNewEntrants_all.zip)

* Processed data output  
    + FPDS data cleaned and grouped by `Dunsnumber`: [FPDS_datapull_all.Rda](https://github.com/CSISdefense/new-entrants-debug/blob/master/data/FPDS_datapull_all.Rda)  
    + FPDS data clearned, grouped by `Dunsnumber`, and included `navy_cust`: [FPDS_datapull_all.v3.Rda](https://github.com/CSISdefense/new-entrants-debug/blob/master/data/FPDS_datapull_all_v3.Rda)  

* Data processing code  
    + [New Entrants cleaning data in R SRC v3 for FPDS ONLY.R](https://github.com/CSISdefense/new-entrants-debug/blob/master/script/New%20Entrants%20cleaning%20data%20in%20R%20SRC%20v3%20for%20FPDS%20ONLY.R)  

* Code generating visualization   
    + [new-entrants_analysis_navy.R]()  
    
    
## References  

* Visualization code: [Analysis_SRC_v4.R](https://github.com/CSISdefense/Vendor/blob/master/New%20Entrants/Data/Analysis/Analysis_SRC_v4.R) or [Analysis_SRC_v4_withservices.R](https://github.com/CSISdefense/Vendor/blob/master/New%20Entrants/Data/Analysis/Analysis_SRC_v4_withservices.R)  