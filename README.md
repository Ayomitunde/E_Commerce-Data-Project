Steps  
  • Import libraries 
  • Load and read the dataset 
  • Quick Data Cleaning: 
      o Return_reason column was dropped (its percentage of missing values was 90%) 
      o Nan Values in coupon_code and customer_feedback was filled with no coupon 
        and no feedback respectively 
      o order_year data type int64 -> str 
      o order_date data type str -> datetime[ns]
