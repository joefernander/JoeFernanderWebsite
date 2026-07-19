### Key Achievements

#### Learning Analytics Dashboards

Developed a series of dashboards and reports in Tableau/R Shiny connected to learning management system (LMS) data to provide instructional designers & faculty with actionable insights into course performance and areas for improvement. Dashboards include grades, learning outcomes, rubrics, quiz item analysis, and LMS system access.

#### Course Learning Analytics Reports

The course learning analytics reports represent a cornerstone of our learning analytics operations at USG eCampus, leveraging the standardized nature of eCore course offerings to deliver comprehensive insights into student outcomes, behaviors, and learning activities at scale. Built using Quarto and deployed to Posit Connect, each course offering in eCampus has an associated analytics report that provides a holistic view of course performance and student engagement. These reports begin with foundational course information including descriptions and learning outcomes, then progress through five-year enrollment and grade distribution trends, detailed learning outcomes analysis, and in-depth examination of gradebook patterns. The reports dive deeper into specific assessment types with dedicated analyses of course quizzes and assignments, while also tracking how students interact with course content including access patterns and engagement frequency. Finally, each report incorporates multiple layers of student feedback through course module surveys, end-of-course evaluation surveys (featuring LLM-generated summaries of qualitative responses), and course withdrawal surveys, creating a comprehensive feedback loop that informs continuous course improvement efforts.

#### Quiz Item Analysis Application

The quiz item analysis dashboard performs item analysis analytics based on methods in classical testing theory for better understanding student and quiz performance from quizzes in the D2L LMS. This application includes descriptive statistics on student performance, discrimination analysis, item-rest correlation, and quiz item analysis. Many of these features are developed using the `psych` and `ctt` R packages. Further, this application connects to the OpenAI API using the `ellmer` R package for an LLM review of quiz questions ensuring accuracy and question feedback.

#### Machine Learning Student Risk Model

Implemented a student risk model for detecting students who may be at risk for not passing their online, asynchronous courses using k-Means in R. To accompany this model, I designed a Tableau dashboard that integrates with the Salesforce CRM to provide Student Success Team members with data about student performance including course access trends, grades, missing assignments/quizzes, and participation in online discussions. Additionally, R scripts were generated to combine all this information using the Salesforce API to generate cases in Salesforce.

#### Faculty Course Evaluation Reports

Created comprehensive course evaluation reports for course faculty. Reports include metrics about student success and their results from their course evaluation surveys. These interactive HTML reports were developed in R Markdown and reduce the administrative burden of compiling report manually each semester saving hours of work.

#### Learning Outcomes Reports

In Fall 2021 eCore and eMajor learning outcomes reporting transitioned from faculty reporting to being generated through the learning management system data. This process reduced faculty workload and increased the reporting capabilities of this data for assessment and accreditation purposes.

#### ETL (Extract, Transform & Load) Processes for INGRESS & LMS Data

Designed and implemented ETL processes for receiving student and LMS data from INGRESS / D2L (via SFTP) and automated imports into the eCampus Analytics Database (SQL Server). This process significantly reduces staff time manually extracting these files and allows dashboards deployed into Tableau to have near-real-time data.
