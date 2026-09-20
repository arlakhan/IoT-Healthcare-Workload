We have added the dataset detail here into the following way.

======================================================================
HEALTHCARE IoT WORKLOAD DATASET
======================================================================

Number of records: 10000
Number of devices: 100

Workload distribution:
Workload_Type
Normal       8038
Emergency    1962
Name: count, dtype: int64

Workload percentages:
Workload_Type
Normal       80.38
Emergency    19.62
Name: proportion, dtype: float64

Application distribution:
Application
ECG monitoring                 1525
Activity recognition           1027
Blood-pressure monitoring      1006
Heart-rate monitoring          1003
Blood-glucose monitoring       1002
SpO2 monitoring                 988
Body-temperature monitoring     955
EEG monitoring                  530
Patient anomaly detection       508
Fall detection                  499
EMG monitoring                  483
Emergency alert detection       474
Name: count, dtype: int64

======================================================================
RANGE VALIDATION
======================================================================

Input size: 1.009 to 199.991 KB
CPU: 200.353 to 3000.0 Mcycles
Memory: 32.006 to 511.997 MB
Deadline: 50.131 to 499.929 ms
QoS: 1 to 5
Arrival rate: 1 to 5 tasks/slot

======================================================================
DATASET CREATED SUCCESSFULLY
======================================================================

File:
healthcare_iot_workload_10000.xlsx

Dataset shape:
(10000, 13)

First 10 records:
 Record_ID  Device_ID                 Application Workload_Type  Input_Size_KB  CPU_Requirement_Mcycles  Memory_Requirement_MB  Deadline_ms  QoS_Priority  Arrival_Rate_tasks_per_slot  Battery_Level_%  Temperature_C  Lifecycle_Factor
         1         74             SpO2 monitoring        Normal          9.058                  482.096                107.654      280.621             4                            5           66.663         31.220            0.9334
         2         15              EMG monitoring        Normal         55.032                 1259.984                481.347      413.499             1                            3           44.165         33.671            0.8317
         3         37        Activity recognition        Normal         50.109                 1785.295                488.573      409.683             4                            3           99.466         40.700            0.8994
         4         12             SpO2 monitoring        Normal         14.556                  360.961                 37.905      368.243             1                            4           48.611         41.630            0.9115
         5         10        Activity recognition        Normal         43.629                 1204.403                176.925      321.541             2                            3           55.327         31.052            0.6472
         6         92              ECG monitoring        Normal         14.424                 1497.035                433.710      461.344             3                            2           86.062         37.124            0.9130
         7          5             SpO2 monitoring        Normal         14.985                  625.063                462.576      208.941             1                            5           58.447         39.768            0.6668
         8          3 Body-temperature monitoring        Normal          3.144                  433.030                347.009      243.425             1                            5           49.697         33.523            0.8648
         9         91    Blood-glucose monitoring     Emergency          5.775                  893.529                439.716       81.012             4                            2           95.516         31.649            0.9836
        10          6   Blood-pressure monitoring        Normal         23.556                  786.054                 51.273      403.399             4                            5           31.590         31.081            0.8889

The Excel workbook contains:
1. Workload_Dataset       -> 10,000 records
2. Dataset_Summary        -> overall statistics
3. Application_Summary    -> application statistics
4. Device_Summary         -> 100-device statistics
