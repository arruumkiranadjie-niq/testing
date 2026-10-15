# testing

```
TIMi Server Dekstop
│
├── Local Disk (C:)                                               ← Personal Storage (Only Related User Can Access)
│   ├── Users
│       ├── UserN                                                 ← User Profile Directory and Workspace
│           ├── Desktop
│               ├── GitHub Desktop                                ← Access GitHub Desktop for Data
│           ├── Documents                                         ← Stores Personal Work Files
│           ├── Downloads                                         ← Stores Downloads Items                            
│           └── ...
│
├── Data1 (D:)                                                    ← Shared Storage (All User Can Access)                                         
│   ├── _common
│       ├── Gudang Garam                                          ← Gudang Garam User Support Folder
│            ├── anatella_files                                   ← All anatella Working Files
│                ├── main_funnel.anatella
│                ├── main_source_of_awareness.anatella
│                ├── main_brand_imagery.anatella
│                ├── main_brand_rating.anatella
│                ├── main_PSM.anatella
│                ├── variable_SA_MA.anatella
│                ├── variable_NUMERIC.anatella
│   ├── source_ref                                                ← Source Reference to Create Anatella Files
│       ├── _fact_data                                            ← Raw Data (Data Only Included Value & Weight)
│            ├── BUMO.gel_anatella
│            └── ...
│       ├── _variable_data                                        ← Processed Data (Data Included Base, Numerator & Denominator)
│            ├── BUMO.gel_anatella
│            └── ...
│       ├── all_data                                              ← All Raw Data Compiled in One gel_anatella file
│            └── all_data.gel_anatella
│       ├── dimension                                             ← Mapping Dimension to Support anatella Working Files
│            ├── dim_period.cgel_anatella
│            ├── dim_location.cgel_anatella
│            ├── dim_brand.cgel_anatella
│            ├── dim_category.cgel_anatella
│       ├── respondent_base                                      ← Respondent Base to Support anatella Working Files
│            └── respondent_base.gel_anatella
│       ├── support
│            ├── 1. Config                                       ← Configuration Settings for Global Parameters
│                └── config.cfg
│            ├── 2. Source Data CSV & JSON                       ← Source Data CSV & JSON
│                ├── Data Regular CSV (Jun'18 - {latest_month})
│                    ├── 0. Jan-Apr 2026.csv
│                    └── ...
│                ├── Data Tambahan CSV (Jan'25-{latest_month})
│                    ├── Data QA_Q43bcd Apr-Jun 2025.csv
│                    └── ...
│                ├── JSON Regular Data (Jun'18 - {latest_month}) 
│                    └── Data Regular Jun18-Aug 26.Json
│                └── JSON Tambahan Data (Jan'25-{latest_month})
│                    └── Data Tambahan Jan25-Aug26.Json
│            ├── 3. Mapping                                       ← Mapping Files to Create Dimension
│                ├── Mapping_Brand.xlsx
│                ├── Mapping_Location.xlsx
│                └── Mapping_Period.xlsx
│            ├── 4. Rules and Variable Tree                       ← Rules and Variable Tree Specifications
│                ├── Rules_TIMi.xlsx
│                ├── 2026-09 Variable Tree TIMi - SEP'26.xlsx
│   ├── User1                                                     ← User Directory and Workspace (Only Related User Can Access)
│   ├── ...                                                       ←                                 ""
│   └── UserN                                                     ←                                 ""
```
