# Data-visualization
This project dashboard is a data visualization tool designed to provide an overview of various projects within an organization. The dashboard is divided into several sections, each providing insights into different aspects of project management.

Sections of the Dashboard1. Project EPS: This section displays the status of projects, categorized into "On Track," "On Watch," and "Troubled." It gives a quick overview of the health of ongoing projects.

2. Active Risks and Issues: The dashboard highlights the number of active risks (35) and active issues (28), indicating areas that require immediate attention.

3. Project Work and Cost: It shows the total project work (372.71K) and the total project cost ($17.53M), providing a financial and workload overview.

4. Projects by Phase: A bar chart illustrates the distribution of projects across different phases (e.g., Planning, Execution, Monitor & Control). This helps in understanding the pipeline and where most projects are concentrated.

5. Projects by Program: A pie chart breaks down projects by program, offering insights into how projects are distributed across different programs.

6. Project List: A detailed table lists various projects with their names, project IDs, schedule status, cost status, start and finish dates, project costs, and completion percentages. This section allows for a granular view of each project's status.

How It Was DoneData Collection- Data Sources: Data was likely collected from project management tools, financial reports, and project tracking databases.
- Data Cleaning: Ensuring data accuracy and consistency by removing duplicates, handling missing values, and standardizing formats.

Design and Visualization1. Choosing the Right Tools: The dashboard was created using a data visualization tool (e.g., Tableau, Power BI) that can connect to various data sources and provide interactive visualizations.

2. Designing the Layout: The dashboard is structured to provide a clear and concise overview. Key metrics are prominently displayed on the left, with more detailed visualizations and tables on the right.

3. Visualizations:
    - Bar Chart for Projects by Phase: Chosen to effectively compare the number of projects across different phases.
    - Pie Chart for Projects by Program: Selected to show the proportion of projects within each program.
    - Table for Project Details: Provides a comprehensive view of individual projects, including their status and financials.

4. Interactivity: The dashboard likely includes interactive elements such as filters (e.g., by program, department, project phase) that allow users to drill down into specific areas of interest.

Implementation- Connecting Data Sources: The visualization tool was connected to the relevant data sources to fetch real-time or near-real-time data.
- Customizing Visualizations: Each visualization was customized to best represent the data. For example, color coding was used to indicate status (e.g., green for on track, red for troubled).
- Testing and Iteration: The dashboard was tested with sample data and iterated upon based on feedback to ensure it met the needs of its users.

UsageThis dashboard is intended for project managers, stakeholders, and decision-makers within the organization. It provides a quick and comprehensive overview of project statuses, helping to identify areas that require attention and facilitating informed decision-making.

Future Enhancements- Real-time Updates: Integrating real-time data feeds to ensure the dashboard always reflects the latest project statuses.
- Drill-down Capabilities: Enhancing the dashboard to allow users to click on visualizations to view more detailed information.
- Custom Alerts: Implementing a feature to send alerts when projects move into a "Troubled" status or when certain thresholds are met
