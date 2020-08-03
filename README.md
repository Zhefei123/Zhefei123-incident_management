# Zhefei123-TDI-data_challenge_Section1
ITSM Incident Management 

Incident management is a process which the main objective is to restore the operation of the IT service affected by corrupted Configuration Item (CI) as fast as possible so that ensuring the lowest impact on the business and customers. Currently, the process is mostly manual rule-based and time-consuming, which can cause delays. Therefore, there is a need for tools assisting in the particular process activities in order to establish more effective process execution, and Machine learning looks prospective to improve the processes through prediction and automation.

The main idea of this project is to leverage the publicly available Incident event log data from UCI ML repository  and to build the predictive models based on the extracted information for assisting the operators during the incident management process. Specific aims are: 

1. Predict the priority of incidents, so that the operators can take preventive measures for High Priority incidents and reassigning can be reduced.
2. Predict the close code, then as soon ticket comes, the operators can know what it will take to close this incident and which automation process or team will be best to solve this in minimum required time ensuring best customer experience.
3. Predict if the CI which was initially assigned to the incident by a Service Desk is actually the one really responsible for the incident occurrence. With the prediction, the Service Desk is expected to be more Effective.
4. Predict the completion time for incident resolution (i.e., ‘ticket completion time’), so that the operators can be better prepared with resources and technology planning.

Additional information about the data: The event log was obtained from data gathered from the audit system of an instance of the ServiceNow platform used by an IT company. The data is composed by 24,918 cases (incidents) and 141,712 events extracted from Mar-2016 to Feb-2017 and it has 36 different features related to an incident. 
