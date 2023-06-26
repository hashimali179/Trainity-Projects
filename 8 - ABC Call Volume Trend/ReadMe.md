**ABC Call Volume Trend Analysis**

**Project Description :**

For you final project we are providing you with a dataset of a Customer Experience (CX) Inbound calling team for 23 days. Data includes Agent\_Name, Agent\_ID, Queue\_Time [duration for which customer have to wait before they get connected to an agent], Time [time at which call was made by customer in a day], Time\_Bucket [for easiness we have also provided you with the time bucket], Duration [duration for which a customer and executives are on call, Call\_Seconds [for simplicity we have also converted those time into seconds], call status (Abandon, answered, transferred).

A customer experience (CX) team consists of professionals who analyze customer feedback and data, and share insights with the rest of the organization. Typically, these teams fulfil various roles and responsibilities such as: Customer experience programs (CX programs), Digital customer experience, Design and processes, Internal communications, Voice of the customer (VoC), User experiences, Customer experience management, Journey mapping, Nurturing customer interactions, Customer success, Customer support, Handling customer data, Learning about the customer journey.

**Approach :**

- Start with a clear and concise summary of your insights
- Use clear and concise language
- Use visual aids
- Provide context
- Highlight key findings
- Consider the audience

**Tech Stack Used :**

1. MS Excel

Link to excel File :

[Click Here](https://github.com/hashimali179/Trainity-Projects/blob/main/8%20-%20ABC%20Call%20Volume%20Trend/Call_Volume_Trend_Analysis_Project_9.xlsx)

1. Calculate the average call time duration for all incoming calls received by agents (in each Time\_Bucket).

| **Time Bucket** | **Average call duration (in secs)** |
| --- | --- |
| **9\_10** | 199.01 |
| **10\_11** | 209.15 |
| **11\_12** | 203.35 |
| **12\_13** | 190.76 |
| **13\_14** | 193.60 |
| **14\_15** | 193.20 |
| **15\_16** | 195.49 |
| **16\_17** | 196.54 |
| **17\_18** | 198.71 |
| **18\_19** | 201.09 |
| **19\_20** | 203.94 |
| **20\_21** | 202.55 |

![](https://github.com/hashimali179/Trainity-Projects/blob/main/8%20-%20ABC%20Call%20Volume%20Trend/Picture1.png)

Insights:

- Time\_Bucket is measured in the Rows and average of Call\_Seconds is measured in the Values section. And we put Call\_Status in the Filters section.
- The total average of call time duration which are answered by the agents is 198.6 seconds.
- The average call time duration for all incoming calls received by agents is the highest in between 10 am to 11 am and from 7 pm to 8 pm
- The average call time duration for all incoming calls received by agents is the least in between 12 noon to 1 pm.

2. Show the total volume/ number of calls coming in via charts/ graphs [Number of calls v/s Time]. You can select time in a bucket form (i.e. 1-2, 2-3, …..)

| **Time Bucket** | **No. of calls** |
| --- | --- |
| **9\_10** | 9588 |
| **10\_11** | 13313 |
| **11\_12** | 14626 |
| **12\_13** | 12652 |
| **13\_14** | 11561 |
| **14\_15** | 10561 |
| **15\_16** | 9159 |
| **16\_17** | 8788 |
| **17\_18** | 8534 |
| **18\_19** | 7238 |
| **19\_20** | 6463 |
| **20\_21** | 5505 |

![](https://github.com/hashimali179/Trainity-Projects/blob/main/8%20-%20ABC%20Call%20Volume%20Trend/Picture2.png)

Insights:

- We plotted Time\_Bucket in the rows and took Count of Customer\_Phone\_No and Count of Time in the Values section.
- We measured Count of Time as the percentage of Column Total.
- The customers call the most in between 11 am to 12 noon.
- The customers call the least in between 8 pm to 9 pm.

3. As you can see current abandon rate is approximately 30%. Propose a manpower plan required during each time bucket [between 9am to 9pm] to reduce the abandon rate to 10%. (i.e. You have to calculate minimum number of agents required in each time bucket so that at least 90 calls should be answered out of 100.)

| Time Bucket | Number of calls | % of calls inbound | Required Agents |
| --- | --- | --- | --- |
| 9\_10 | 9588 | 8% | 5 |
| 10\_11 | 13313 | 11% | 6 |
| 11\_12 | 14626 | 12% | 7 |
| 12\_13 | 12652 | 11% | 6 |
| 13\_14 | 11561 | 10% | 6 |
| 14\_15 | 10561 | 9% | 5 |
| 15\_16 | 9159 | 8% | 4 |
| 16\_17 | 8788 | 7% | 4 |
| 17\_18 | 8534 | 7% | 4 |
| 18\_19 | 7238 | 6% | 3 |
| 19\_20 | 6463 | 5% | 3 |
| 20\_21 | 5505 | 5% | 3 |
| **Grand Total** | **117988** | **100%** | **57** |

| **Date** | **abandon** | **answered** | **transfer** | **Grand Total** |
| --- | --- | --- | --- | --- |
| 01-Jan | 684 | 3883 | 77 | 4644 |
| --- | --- | --- | --- | --- |
| 02-Jan | 356 | 2935 | 60 | 3351 |
| 03-Jan | 599 | 4079 | 111 | 4789 |
| 04-Jan | 595 | 4404 | 114 | 5113 |
| 05-Jan | 536 | 4140 | 114 | 4790 |
| 06-Jan | 991 | 3875 | 85 | 4951 |
| 07-Jan | 1319 | 3587 | 42 | 4948 |
| 08-Jan | 1103 | 3519 | 50 | 4672 |
| 09-Jan | 962 | 2628 | 62 | 3652 |
| 10-Jan | 1212 | 3699 | 72 | 4983 |
| 11-Jan | 856 | 3695 | 86 | 4637 |
| 12-Jan | 1299 | 3297 | 47 | 4643 |
| 13-Jan | 738 | 3326 | 59 | 4123 |
| 14-Jan | 291 | 2832 | 32 | 3155 |
| 15-Jan | 304 | 2730 | 24 | 3058 |
| 16-Jan | 1191 | 3910 | 41 | 5142 |
| 17-Jan | 16636 | 5706 | 5 | 22347 |
| 18-Jan | 1738 | 4024 | 12 | 5774 |
| 19-Jan | 974 | 3717 | 12 | 4703 |
| 20-Jan | 833 | 3485 | 4 | 4322 |
| 21-Jan | 566 | 3104 | 5 | 3675 |
| 22-Jan | 239 | 3045 | 7 | 3291 |
| 23-Jan | 381 | 2832 | 12 | 3225 |
| **Grand Total** | **34403** | **82452** | **1133** | **117988** |
| **Average** | **1496** | **3585** | **49** | **5130** |
| **% of calls** | **29%** | **70%** | **1%** |   |

| **Assumptions:** |
| --- |
| Agents working Hrs | 9 | Hrs |
| Break | 1.5 | Hrs |
| Agents working Hrs on Floor | 7.5 | Hrs |
| **Agents Time spent on calls** | **4.5** | **Hrs** |
|
 |
 |
 |
| Avg Call Volume per day(9:00 AM to 9:00 PM) | 5130 | Nos |
| Average call duration (9:00 AM to 9:00 PM) | 199 | Seconds |
| Total call duration for 90% Calls | 255 | Hrs |
| **Agents required per day** | **57** | **Nos** |

![](https://github.com/hashimali179/Trainity-Projects/blob/main/8%20-%20ABC%20Call%20Volume%20Trend/Picture3.png)

Insights

  - Total agents working can be calculated by average calls on a single day divided by total time spend by one man in a single day.

total agent = 187.96/5 = 37.59

  - If agents are working for 5 hrs a day and 60% calls are getting answered. If we want 90% of the calls to get connected, we apply unitary method to find how many more employee we want.
  - total agent = 90\*37.59/60 = ~57 agents

1. First, we created pivot table. Date & Time is dragged down to Rows, Call Status to Columns, while taking count Call Duration in the Values section.
2. Then, we calculated the average of abandon, answered and transfer by using the average excel formula.
3. 29% of the calls are abandoned, 1% is transferred, while 70% of the calls are answered in the daytime.
4. Total agents required to answer the 90% of the calls per day is 56.
5. The minimum number of agents required for each time bucket is calculated by 56 \* count of time (calculated in the 2nd question).

4. Let's say customers also call this ABC insurance company in night but didn't get answer as there are no agents to answer, this creates a bad customer experience for this Insurance company. Suppose every 100 calls that customer made during 9 Am to 9 Pm, customer also made 30 calls in night between interval [9 Pm to 9 Am] and distribution of those 30 calls are as follows:

Now propose a manpower plan required during each time bucket in a day. Maximum Abandon rate assumption would be same 10%.

| **Assumptions:** |
| --- |
| Agents working Hrs | 9 | Hrs |
| Break | 1.5 | Hrs |
| Agents working Hrs on Floor | 7.5 | Hrs |
| **Agents Time spent on calls** | **4.5** | **Hrs** |
|
 |
 |
 |
| Avg Call Volume per day(9:00 AM to 9:00 PM) | 5130 | Nos |
| Average call duration (9:00 AM to 9:00 PM) | 199 | Seconds |
| Total call duration for 90% Calls | 255 | Hrs |
| **Agents required per day** | **57** | **Nos** |
|
 |
 |
 |
| **If support is provided from 9:00 PM to 9:00 AM)** |
| Avg Call Volume (9:00 PM to 9:00 AM) | 1539 | Nos |
| Total Call duration (9:00 PM to 9:00AM) | 77 | Hours |
| **Agents required (9:00 PM to 9:00AM)** | **17** | **Nos** |

| **Time\_Bucket** | **Calls\_inbound** | **% of calls inbound** | **Required agents** |
| --- | --- | --- | --- |
| 21\_22 | 3 | 10% | 2 |
| 22\_23 | 3 | 10% | 2 |
| 23\_24 | 2 | 7% | 1 |
| 00\_01 | 2 | 7% | 1 |
| 01\_02 | 1 | 3% | 1 |
| 02\_03 | 1 | 3% | 1 |
| 03\_04 | 1 | 3% | 1 |
| 04\_05 | 1 | 3% | 1 |
| 05\_06 | 3 | 10% | 2 |
| 06\_07 | 4 | 13% | 2 |
| 07\_08 | 4 | 13% | 2 |
| 08\_09 | 5 | 17% | 3 |
| **Total** | **30** | 100% | 17 |

| **Time\_Bucket** | **Required Agents** |
| --- | --- |
| 21\_22 | 2 |
| 22\_23 | 2 |
| 23\_24 | 1 |
| 00\_01 | 1 |
| 01\_02 | 1 |
| 02\_03 | 1 |
| 03\_04 | 1 |
| 04\_05 | 1 |
| 05\_06 | 2 |
| 06\_07 | 2 |
| 07\_08 | 2 |
| 08\_09 | 3 |
| 9\_10 | 5 |
| 10\_11 | 6 |
| 11\_12 | 7 |
| 12\_13 | 6 |
| 13\_14 | 6 |
| 14\_15 | 5 |
| 15\_16 | 4 |
| 16\_17 | 4 |
| 17\_18 | 4 |
| 18\_19 | 3 |
| 19\_20 | 3 |
| 20\_21 | 3 |

![](https://github.com/hashimali179/Trainity-Projects/blob/main/8%20-%20ABC%20Call%20Volume%20Trend/Picture4.png)

1. We first calculated the Time Distribution by dividing each calls distribution by total calls i.e., 30.
2. The number of agents required for each time bucket is calculated by 15 \* Time Distribution
3. 15 is calculated above by dividing the additional hours required to answer the night calls by 5 (actual working hours of agents).
4. Also, while calculating, the round figure is taken into consideration as there cannot be 1.5 men working.

Insights:

1. The customers call the least in the evening. So, the company can reduce the number of agents at that time for answering the calls.
2. The company can hire 15 customer support agents for the night shift work.
3. The company can shift some of the day workers for the night shift.
4. The employees who are working 9 am to 9 pm. The manager can change some of the workers shift from 5 am to 2 pm and some workers from 2 pm to 11 pm to get the most calls answered.
5. The company can make the employers divide into 3 parts too, so that the agents are always available 24/7.
6. We found there were few outliers in the data. And if we have removed that outliers, then the answers would have been different.

Results:

1. I learned how an analyst can make an impact in customer service department.
2. I learned how a company deals with the customers to give them the most satisfaction.
3. I got to know about the IVR Duration, which is an AI tool, who answer the calls to get to know the customer exact question and then transfer it to the right agent to get the customer's queries get answered.
4. This project was easy to get the answers as the data provided by the team have already calculated the time bucket and converted the calls duration into seconds, so we do not have to spend time on it to calculate.
5. I learned about the behavioral analytics
