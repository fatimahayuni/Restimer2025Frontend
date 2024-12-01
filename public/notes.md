1st Dec 2024:
1. As a scheduler, I want to see the group's ATS, individual ATS, upload.
2. So the navbar will use Tailwind dashboardLayout.js. The links are: Group, Individual, Upload.
3. In the Group page, the scheduler will see charts. There will be 3 tabs: Daily, Weekly, Monthly. When she clicks on each tab, she will see the line charts of the group on daily, weekly, monthly basis against the intended metrics.
4. In the Individual page, the scheduler will see the list of each agent. We will use Tailwind list for this. Next to the name of each agent is the Daily, Weekly, and Monthly report for that agent. When the scheduler clicks on the either one of the links, it will show her the line chart of each agent for that period of time. 
5. We will use Tailwind and Chart.js.
6. We will use Bar Chart for individual agents: https://www.chartjs.org/docs/latest/samples/bar/border-radius.html
7. We will use Line Chart for group ATS. https://www.chartjs.org/docs/latest/samples/line/line.html

As the agent, I want to see:
1. The rounded timer. The timer itself will serve as button to press for Personal Timer.
2. The agent will only see one page for her daily 5x at the top and at the bottom, she will see the timer. 
3. The timer will be a countdown. 60 minutes or 15 minutes. 
4. The timer will start with green as it is counting down.
5. Once it reaches the warning state, it will turn orange and there will be a warning sound. 
6. Once it reaches the critical state, it will turn red and there will be a danger sound. 
7. I also want to see my performance that day, that week, and that month. 
8. So the agent will see 2 pages: break times of the day and the timer AND her performance. So two links in her navbar max. 
9. 