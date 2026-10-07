## Google Chronicle Sync Job
This job will synchronize information about Chronicle SOAR Cases and Chronicle SOAR Alerts with Chronicle SIEM.
 Note: This job is only supported from Chronicle SOAR version 6.1.44 and higher.


**Run Interval In Seconds:** 600

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment|String|True|Default Environment|
|API Root|String|True|https://eu-chronicle.googleapis.com/v1alpha/projects/251657645427/locations/eu/instances/ab6f2f36-8b9d-4f06-9429-e4eeb73b0c7b|
|User's Service Account|Password|False|*****|
|Workload Identity Email|Password|False|*****|
|Max Hours Backwards|String|False|100|
|Verify SSL|Boolean|False|true|


readme addon test text