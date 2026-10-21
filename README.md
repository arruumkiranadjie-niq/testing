<img width="408" height="25" alt="image" src="https://github.com/user-attachments/assets/ff3b65ba-7c2d-4f96-a236-d6cfafaf1c8c" /><img width="408" height="25" alt="image" src="https://github.com/user-attachments/assets/0b7f5f77-8b43-498d-9749-a3ff3cf027c9" /># testing

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
│                ├── 1_Import_Data.anatella
│                ├── 2_Transform_CSV.anatella
│                ├── 3_Import_Fact_Data_categorical.anatella
│                ├── 3_Import_Fact_Data_categorical_array.anatella
│                ├── 3_Import_Fact_Data_numeric.anatella
│                ├── 3_Import_Fact_Data_numeric_array.anatella
│                ├── 4_Build_Dimension_Respondent-Base.anatella
│                ├── 5_Build_Cube_Numeric.anatella
│                ├── 5_Build_Cube_SA_MA.anatella
│                ├── 6_Preset_Brand_Funnel.anatella
│                ├── 6_Preset_SOA.anatella
│                ├── 6_Preset_Brand_Imagery.anatella
│                ├── 6_Preset_PSM.anatella
│                ├── 6_Preset_Band_Rating.anatella
│   ├── _source                                                ← Source Reference to Create Anatella Files
│       ├── 1_fact_data                                            ← Raw Data (Data Only Included Value & Weight)
│            ├── BUMO.gel_anatella
│            └── ...
│       ├── 2_variable_data                                        ← Processed Data (Data Included Base, Numerator & Denominator)
│            ├── BUMO.gel_anatella
│            └── ...
│       ├── 3_all_data                                              ← All Raw Data Compiled in One gel_anatella file
│            └── all_data.gel_anatella
│       ├── 4_dimension                                             ← Mapping Dimension to Support anatella Working Files
│            ├── dim_period.cgel_anatella
│            ├── dim_location.cgel_anatella
│            ├── dim_brand.cgel_anatella
│            ├── dim_category.cgel_anatella
│       ├── 5_respondent_base                                      ← Respondent Base to Support anatella Working Files
│            └── respondent_base.gel_anatella
│       ├── 6_support
│            ├── 1_Config                                       ← Configuration Settings for Global Parameters
│                └── config.cfg
│            ├── 2_Source Data CSV & JSON                       ← Source Data CSV & JSON
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
│            ├── 3_Mapping                                       ← Mapping Files to Create Dimension
│                ├── Mapping_Brand.xlsx
│                ├── Mapping_Location.xlsx
│                └── Mapping_Period.xlsx
│            ├── 4_Rules and Variable Tree                       ← Rules and Variable Tree Specifications
│                ├── Rules_TIMi.xlsx
│                ├── 2026-09 Variable Tree TIMi - SEP'26.xlsx
│   ├── User1                                                     ← User Directory and Workspace (Only Related User Can Access)
│   ├── ...                                                       ←                                 ""
│   └── UserN                                                     ←                                 ""
```

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
│       ├── NIQ                                                   ← NIQ User Support Folder
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
