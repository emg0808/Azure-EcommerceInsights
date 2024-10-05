| Date      | Wrk | Description                                                     |
|-----------|-----|-----------------------------------------------------------------|
| 2024-10-04|  3.0| Storage Account Created:                                        |
|           |  3.0| Diverted by setting up VS Code + GitHub integration with        |
|           |     | Azure Data Factory.                                             |
| 2024-10-05|  1.0| Good Info: https://youtu.be/fz4tax6nKZM?si=SgdAZh2VPa04SHN5     |
|           |     | The presenter discusses the following layers in the data processing journey:                                             |
|           |     | 1. **Landing Zone**: Raw data is stored here as flat files (e.g., JSON or Parquet), received from various sources.         |
|           |     | 2. **Raw Layer**: Data is schema validated but not yet cleansed;it is still untrusted.                                          |   
|           |     | 3. **Base Layer**: Clean and validated data, equivalent to anoperational data store.                                         |
|           |     | 4. **Enriched Layer**: Data is conformed across sources and standardized, ready for further use.                            |
|           |     | 5. **Curated Layer**: Analytical data models like star schemas, designed for business consumption.                              |
|           |     | 6. **Semantic Layer**: High-level metrics and calculations for BI tools.                                                       |    
||||
|           |     | Downloaded the Brazilian OList and Marketing Funnel data sets in .CSV format from Kagle |
||                | Data Factory CSV injestion                                                 |
