# Disk Space alert for /var on linux instances.
# Alarm for /var file system utilization on Threshold Crossed: 2 datapoints greater than or equal to the threshold (90.0).

#Sample ticket created when Threshold is crossed
Alert Details: 
AlarmName: awsec2-i-01485e9fbfe70639e-/var-Disk-Pct-Used
AlarmDescription: Alarm for /var file system utilization
AWSAccountId: 405020847236
NewStateValue: ALARM
NewStateReason: Threshold Crossed: 2 datapoints [91.94745686356808 (08/05/23 00:02:00), 92.21127585871322 (07/05/23 23:47:00)] were greater than or equal to the threshold (90.0).
StateChangeTime: 05/08/2023 00:17:00
Region: US West (Oregon)
OldStateValue: INSUFFICIENT_DATA
Trigger_MetricName: disk_used_percent
Trigger_Namespace: CWAgent
Trigger_StatisticType: Statistic
Trigger_Statistic: AVERAGE
Trigger_Unit: 
Trigger_Dimensions: [
  {
    "value": "/var",
    "name": "path"
  },
  {
    "value": "i-01485e9fbfe70639e",
    "name": "InstanceId"
  },
  {
    "value": "mapper/vg00-var",
    "name": "device"
  },
  {
    "value": "ext4",
    "name": "fstype"
  }
]
Trigger_Period: 900
Trigger_EvaluationPeriods: 2
Trigger_ComparisonOperator: GreaterThanOrEqualToThreshold
Trigger_Threshold: 90
Trigger_TreatMissingData: 
Trigger_EvaluateLowSampleCountPercentile: 
Time_DB_Recorded: 5/8/2023 12:17:12 AM
ResourceID: 
Alarm_Type: /var-Disk-Pct-Used
CI: 
Assignment_Group: INC-HPI-LV3-INFRA-PUBLIC-CLOUD-DXC
rec_num: 36153
Provider_Name: AWS
Platform: Linux
Account_Name: eprid202168-records-advisor-tool-dev
Application_Name: Records Advisor Tool
Account_Type: Shared Managed
App_Owner_Email: 
App_Owner_Name: 
App_Name: Records Advisor Tool
PrivateIP: 
Environment: DEV
Resource_Type: EC2
Status_15_minutes_old: running
Monthly_Maintenance_Window: MP1AW1
Crisis_Maintenance_Window: CP2
Application_Contacts:  
Urgency: 3
Impact: 3

