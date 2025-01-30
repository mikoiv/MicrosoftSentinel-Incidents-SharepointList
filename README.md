# MicrosoftSentinel-Incidents-SharepointList

Feed Sentinel incidents to a Sharepoint List and Teams Channel.

Read more here: https://secopslab.substack.com

## Logic App deployment

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmikoiv%2FMicrosoftSentinel-Incidents-SharepointList%2Fmain%2Fazuredeploy.json)

## Automation Rule deployment

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmikoiv%2FMicrosoftSentinel-Incidents-SharepointList%2Fmain%2FSentinel_automation_rules.json)

## Incident list schema

[List_column_template.csv](https://github.com/mikoiv/MicrosoftSentinel-Incidents-SharepointList/blob/main/List_column_template.csv)

| Column | Explanation |
| --- | --- |
| CreatedTime |Incident created time |
| Title |Incident title |
| Severity |Incident severity |
| Status |Incident status |
| Owner |Current owner, if set |
| ProviderName |Set to either Defender or Sentinel |
| FirstActivityTime |First activity time |
| LastActivityTime |Last activity time |
| SentinelUrl |Direct link to Sentinel | 
| UnifiedUrl |Direct link to Unified portal |
| AlertCount |Count of alerts in the incident | 
| ProviderIncidentId |XDR incident number | 
| IncidentNumber |Sentinel incident number | 
| Alerts |List of individual alerts in the incident | 
