# QueueMetrics templates

A collection of ready-made reports and wallboards for QueueMetrics https://www.queuemetrics.com and QueueMetrics Live https://www.queuemetrics-live.com

## How do you download a report/wallboard template and upload it to QueueMetrics?

You can find a quick guide [here.](https://github.com/Loway/Templates/blob/main/Download_Templates.md)

## Reports

### Default Reports:

Ever wondered how to restore a pristine report in QM? 

#### All reports: 
[Download](https://github.com/Loway/Templates/blob/main/reports/default_all_reports.json)

#### Quick agent reports: 
[Download](https://github.com/Loway/Templates/blob/main/reports/default_quick_agent_reports.json)

#### Quick reports: 
[Download](https://github.com/Loway/Templates/blob/main/reports/default_quick_reports.json)

# 

### Custom Reports:
The reports below, like all QueueMetrics reports, can be customized to best fit your use case and needs.

#### Overview:    
[Download](https://github.com/Loway/Templates/blob/main/reports/Overview.json)     
Overview of the last 7 days. 

The report is customizable and in the current form offers a compact overview of the:
- answered calls (summary and individual calls)
- unanswered calls (summary and individual calls)
- agent session and pause details
- individual agents and queues attempts (how many times the PBX tried to send a call to an agent or a queue)
- distribution of the calls per day of the week, calendar day, and hourly distribution

#### Recall details:   
[Download](https://github.com/Loway/Templates/blob/main/reports/Recall_details.json)     
A report that assists with identifying the numbers that need to be recalled.        
The report will automatically add or remove a number to the recall list. The list will be updated every time you run the report.      


#### Recap:
[Download](https://github.com/Loway/Templates/blob/main/reports/Recap.json)      
A report designed to be used as a scheduled job.       
It will send you via e-mail a summary of the offered, taken and lost calls, as well as the call distribution by hour, and the attempts each agent has received during the day.     
You can find more details on how to set up a scheduled job [here.](https://www.queuemetrics.com/blog/2022/10/03/First-custom-report-and-report-scheduling/)

#### Agents Weekly Performance:
[Download](https://github.com/Loway/Templates/blob/main/reports/Agents_Weekly_Performance.json)      
A report highlighting the weekly agent performance:
- an overview of the agent statistics
- statistics on the agent session and pause duration
- the agent productivity

#### Peak Hour Analysis: 
[Download](https://github.com/Loway/Templates/blob/main/reports/Peak_Hour_Analysis.json)       
Analysis of the call distribution per week, day and hour.       
The report highlights the distribution of the answered calls, and the wait time of the unanswered calls. 

#### SLA Overview:
[Download](https://github.com/Loway/Templates/blob/main/reports/SLA_Overview.json)      
A simple and useful SLA (service-level agreement) report, to keep an eye on how quickly the calls are being answered by your Agents. 



## Wallboards

### Recalls

A wallboard that displays recalls waiting to be made and already made during the current day.

Available at https://github.com/Loway/Templates/blob/main/wallboards/Recalls.json

<img width="300" alt="recalls_1" src="https://user-images.githubusercontent.com/1101849/197764787-08f8e358-f6c7-47c9-9201-80179d972000.png">
<img width="300" alt="recalls_2" src="https://user-images.githubusercontent.com/1101849/197764794-7c7ab995-17d7-4f80-a12c-75622bc970aa.png">


### MsTeams: Today's queue activity

A wallboard that show what happened on queues during the currect day. Built for Microsoft Teams reporting, but will work
as well on any contact centre.

Displays an hourly graph of all calls taken - and lost - today, as well as their waiting times, and on a second page,
the current SLA, the number of offered and lost calls, and all hourly wait times for unanswered calls.

Available at https://github.com/Loway/Templates/blob/main/wallboards/Teams_Todays_queues.json

<img width="300" alt="Screenshot 2022-12-06 at 13 56 27" src="https://user-images.githubusercontent.com/1101849/205928799-d353e948-2834-43a1-a111-f93547673c33.png">

<img width="300" alt="Screenshot 2022-12-06 at 13 56 42" src="https://user-images.githubusercontent.com/1101849/205928771-487dcc1f-4423-4d82-a838-9f6e67478444.png">

### Today's traffic

A very simple wallbord showing an hourly graph of all calls taken - and lost - today, as well as their waiting times.

Available at https://github.com/Loway/Templates/blob/main/wallboards/todays_traffic.json




## Contribuiting


If you have interesting wallboards or reports to share, feel free to send us a PR.


