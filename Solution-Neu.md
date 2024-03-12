# Was man so alles in einer Solution so anlegen kann

WARNUNG: Inhalte wurden mit ChatGpt erstellt und müssen noch überarbeitet/geprüft werden, ob es reine Phantasie ist oder wirkliches Wissen :)

## unter APP

| ITEM           | SHORT DESCRIPTION                                        | PRACTICAL USE CASE                                                                                             |
|----------------|----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| **Canvas app** | A flexible, design-first app                             | Create a custom front-end interface for a field service app that allows technicians to update work orders on their mobile devices. |
| **Model-driven app** | An app based on the data model of Dataverse       | Develop a complex CRM system that utilizes the relationships and data structure defined in Dataverse.          |
| **Page**       | Individual pages for model-driven apps                   | Design a dedicated customer details page within a model-driven app that provides a comprehensive view of customer interactions. |

## unter Automation

Based on the options listed in the screenshot provided for creating new components within a Power Platform solution, here is the markdown table with short descriptions and practical use cases:

| ITEM              | SHORT DESCRIPTION                                          | PRACTICAL USE CASE                                                                                        |
|-------------------|------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| **Cloud flow**    | Automated workflows hosted in the cloud                    | Automate document approval processes so that submissions are reviewed and approved by the necessary parties in sequence. |
|  ├─**Automated**     | A cloud flow that triggers automatically based on events    | Create a flow that starts whenever a new item is added to a SharePoint list, automatically processing the item. |
|  ├─**Instant**       | A cloud flow triggered by manual user action               | Set up an instant flow to quickly onboard new team members in Microsoft Teams with a click of a button.   |
|  └─**Scheduled**     | A cloud flow that runs at predefined times                 | Configure a scheduled flow to generate weekly reports every Monday at 8 AM and email them to stakeholders. |
| **Custom connector** | Connector to integrate with external APIs and services  | Create a connector to integrate a third-party API for SMS notifications into Power Automate workflows.   |
| **Dataflow**      | Data preparation and transformation pipeline               | Set up a dataflow to import, clean, and transform sales data from various sources for Power BI reporting. |
| **Desktop flow**  | Automate tasks on a local desktop environment              | Develop a desktop flow to automate data entry from scanned forms into a database system.                 |
| **Process**             | Framework for defining automated business processes | Define a multi-step approval process for expense reporting, ensuring compliance with company policies.      |
|   ├─ **Action**         | Custom process action for reuse across workflows    | Create a reusable action to check inventory levels and reorder stock when it falls below a certain threshold.|
|   ├─ **Business process flow** | Guide users through a business process          | Design a business process flow to standardize the stages every sales opportunity must go through from qualification to closure. |
|   └─ **Workflow**       | Sequence of automated steps within a process        | Automate a sequence of tasks for data entry verification, followed by record updating and notification sending. |
| **Card**                      | A modular unit of information in Teams or Power Automate              | Display summary information, like total sales, that can be quickly glanced in a Teams chat.                   |
| **Chatbot**                   | An interactive AI chat interface                          | Implement a customer service chatbot to help users navigate support questions and submit tickets.            |
| **Dashboard**                 | A collection of reports, cards, and other items           | Create a centralized overview of key performance indicators to be reviewed by the management team.          |
|   ├─ **2-Column overview**    | Dashboard layout with two columns                         | Organize a dashboard to display sales and marketing data side by side for easy comparison.                   |
|   ├─ **3-Column overview**    | Dashboard layout with three columns                       | Segment a dashboard into three sections for financial, operational, and customer service metrics.            |
|   ├─ **3-Column overview (varied width)** | Dashboard with columns of varied width | Customize a dashboard to feature a main report, with smaller widgets on the side for alerts and updates.     |
|   ├─ **4-Column overview**    | Dashboard layout with four columns                        | Design a dashboard to show detailed metrics across different business units, each in its own column.         |
|   └─ **Power BI embedded**    | Embed Power BI reports directly into the dashboard        | Integrate interactive Power BI reports into the dashboard for in-depth data analysis and visualization.      |
| **Report**                    | A detailed analysis or summary of data                    | Develop comprehensive sales reports that can be generated weekly for performance tracking.                   |
| **Security**                  | Settings and configurations for securing the solution     | Configure user access controls and permissions to safeguard sensitive data within the app.                    |
| **Table**                     | Structured data presented in rows and columns             | Create a table to organize and display customer contacts in a systematic, searchable format.                 |
| **Security**               | Configuration of security measures within the solution| Set up security protocols to protect sensitive data and ensure compliance with data protection regulations.  |
|   ├─ **Attribute masking rule** | Rule to mask attributes to protect sensitive data  | Mask personal identifiers in a customer service app to ensure that customer service reps see only the information necessary to assist the customer. |
|   ├─ **Column security profile**| Security profile for column-level access          | Restrict access to salary information in a HR app, allowing only certain roles to view or edit this data.    |
|   └─ **Secured masking rule**   | Rule to secure and mask specific data              | Apply rules to a financial app to mask account numbers, showing only the last four digits to unauthorized users. |
|   └─ **Security role**          | Role defining permissions for users                 | Create a 'Manager' security role that grants permissions to approve budget requests and access sensitive reports. |
| **Table**                 | Structure for organizing and storing data            | Create a custom table to track inventory levels, including columns for item names, quantities, and reorder thresholds. |
| **Table from external data** | Structure for storing external data within Power Apps | Integrate external customer data from a third-party CRM system into Power Apps for unified data management. |


## unter NEU-Sonstiges


| ITEM                              | SHORT DESCRIPTION                                      | PRACTICAL USE CASE                                                                                     |
|-----------------------------------|--------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| **AIPlugin**                      | Component for AI model integration                     | Integrate a custom machine learning model to predict customer churn based on usage data in a CRM app. |
| **AIPluginExternalSchema**        | Schema definition for an external AI plugin            | Define the input/output schema for a text analysis AI model to categorize customer feedback.          |
| **AIPluginExternalSchemaProperty**| Properties for the AI plugin's schema                  | Specify the `sentimentScore` property for a feedback analysis AI model, allowing sentiment analysis of customer reviews. |
| **AIPluginInstance**              | Instance of an AI plugin                               | Deploy an AI model that forecasts sales based on historical data within a sales app.                  |
| **AIPluginOperation**             | An operation within an AI plugin                       | Use an image recognition operation in an AI plugin to automatically tag product photos in an inventory app. |
| **App Insights Metadata**         | Metadata for application insights integration          | Collect and analyze user interaction data in a Power App to improve user experience based on usage patterns. |
| **Catalog**                       | Set of items or services for Power Apps                | Organize a catalog of internal tools and services in Power Apps, allowing employees to easily find and use them in their projects. |
| **Catalog Assignment**            | Assigning catalog items for specific use               | Assign specific APIs and connectors from the catalog to a marketing campaign management app to enhance its functionality. |
| **CopilotExampleQuestion**        | Template for AI-assisted features                      | Use AI to generate example customer support queries to train support staff within an app.             |
| **Credential**                    | Secure storage for credentials                         | Securely store API keys and database credentials in a Power App, ensuring safe access to external services. |
| **Custom API**                       | Defines a custom API                                 | A business needs to integrate their custom inventory management system with Power Apps to update stock levels in real-time. |
| **Custom API Request Parameter**     | Parameters for a custom API                          | For an order processing API, define parameters such as `orderId`, `customerName`, and `shippingAddress` to retrieve or update order details. |
| **Custom API Response Property**     | Expected properties in a custom API response         | Specify `status` and `trackingNumber` as response properties for a shipping API to provide shipment updates to customers. |
| **Data Movement Service Request**    | Request for data movement                            | Migrate historical sales data from an old CRM system to a new Power Platform solution for analysis and reporting. |
| **Data Movement Service Request Status** | Status of a data movement request                   | Monitor the progress of large-scale data migration tasks between different environments or databases to ensure successful completion. |
| **Data Processing Configuration**    | Data processing settings                             | Set up data validation rules for customer input forms in Power Apps to ensure data quality and consistency. |
| **Dataflow Connection Reference**    | Connection reference in a dataflow                   | Connect a Power BI dataflow to a cloud-based SQL database to automate the ingestion and transformation of sales data for reporting. |
| **Dataflow DatalakeFolder**          | Data lake folder for a dataflow                      | Organize and store processed customer feedback data in specific folders within a data lake for sentiment analysis. |
| **Dataflow Template**                | Template for creating dataflows                      | Use a template to quickly set up a dataflow that aggregates data from multiple sources, transforms it, and loads it into a dashboard for monthly performance tracking. |
| **Desktop Flow Binary**              | Binary file for desktop flows                        | Automate the process of extracting data from PDF invoices using a desktop flow, converting them into a binary format for integration into a financial system. |
| **Desktop Flow Module**      | A module used within desktop flow                         | Automate repetitive tasks in a desktop application for processing invoices, using a specific automation module. |
| **Duplicate Detection Rule** | Rules to detect and handle duplicate records              | Prevent duplicate customer records in a CRM system by applying rules that identify and merge duplicates.      |
| **DVFileSearch**             | Feature for searching files, specific to Power Apps       | Enable users to quickly find and access specific documents stored in Dataverse by keywords or metadata.       |
| **DVFileSearchAttribute**    | Attributes for searching within files in Dataverse        | Improve file search accuracy by focusing on specific attributes like `fileName` or `fileType`.                |
| **DVFileSearchEntity**       | An entity for file search capabilities in Dataverse       | Facilitate advanced file search operations in applications by utilizing a file search entity with custom criteria. |
| **DVTableSearch**            | Search functionality for Dataverse tables                 | Allow users to perform detailed searches across Dataverse tables for comprehensive data analysis.             |
| **DVTableSearchAttribute**   | Attributes related to Dataverse table search functionalities | Enhance table search functionality by defining searchable attributes, such as `status` or `creationDate`.     |
| **DVTableSearchEntity**      | An entity for table search within Dataverse               | Utilize a search entity to streamline access to table data, improving user experience in data-driven apps.    |
| **EntityRecordFilter**       | A filter to apply to entity records                       | Apply filters to sales records to display only those that meet specific criteria, like a date range or sales threshold. |
| **FeatureControlSetting**    | Settings to enable or disable features within the solution | Enable or disable experimental features in a Power App, such as a new user interface component, for A/B testing. |
| **Flow Machine Group**               | Grouping for VMs used in Power Automate flows                  | Organize VMs used for different departments' workflows, optimizing resource usage and management.              |
| **Flow Machine Image**               | The VM image used for running Power Automate flows             | Deploy a pre-configured VM image to ensure consistency and reliability across automated processes.             |
| **Flow Machine Image Version**       | Specific version of the VM image for Power Automate flows      | Use a specific version of a VM image to maintain compatibility with certain automated workflows.                |
| **Flow Machine Network**             | Networking components for VMs in Power Automate                | Configure networking settings for VMs to ensure secure and efficient communication between automated tasks.    |
| **FxExpression**                     | Expression in Power Fx for Power Platform                      | Use Power Fx to calculate the total sales for the month dynamically in a Power Apps canvas app.                |
| **Help Page**                        | Help documentation page                                        | Provide users with a help page that includes FAQs and troubleshooting tips for common issues in the app.        |
| **Insights Store Virtual Entity**    | Virtual entity for storing insights in Dataverse               | Store and retrieve analytics insights about app usage patterns without needing physical storage.                |
| **Key Vault Reference**              | Reference to Azure Key Vault for secure storage                | Store sensitive information like API keys securely in Azure Key Vault, referenced directly from the app.       |
| **Knowledge Management Setting**     | Settings for knowledge management                              | Configure the app to use a centralized repository for storing and accessing organizational knowledge.          |
| **Knowledge Search Filter**          | Filters for knowledge search                                   | Apply filters to search through a knowledge base, helping users find relevant articles based on their queries.  |
| **MainFewShot**                             | AI capability for training with few examples                              | Quickly develop a custom AI model to classify customer inquiries with only a handful of training samples. |
| **Managed Identity**                        | Identity for authentication managed by Azure                              | Automate secure access to Azure resources for an app without storing sensitive credentials in code.       |
| **Mobile App**                              | Mobile application component within the solution                          | Develop a mobile version of a Power App to enable users to access the app functionalities on the go.      |
| **Module Run Detail**                       | Details of a specific run of a module                                     | Analyze the performance and outcome of a specific automation module run within a workflow.                |
| **Plugin Package**                          | Package with plugins to extend functionality                              | Extend a Power App with a plugin package for advanced image processing capabilities.                      |
| **PM Business Rule Automation Config**      | Configuration for process mining business rules automation                | Configure automation rules in process mining to streamline workflow approvals based on data patterns.     |
| **PM Calendar**                            | Calendar for tracking events in process mining                            | Use a calendar to schedule and track process mining analysis cycles and related activities.               |
| **PM Calendar Version**                     | Version of the process mining calendar                                    | Manage and deploy updates to the process mining calendar to reflect changes in business schedules.        |
| **PM Inferred Task**                        | Task inferred from data patterns in process mining                        | Identify and model new process steps in process mining that are suggested by data patterns.               |
| **PM Process Extended Metadata Version**    | Extended metadata for versions of process mining processes                | Utilize extended metadata to enhance the detail and accuracy of process mining analyses over different versions. |
| **PM Process Template**          | Template for creating process mining processes               | Streamline the setup of new process mining projects by using templates with predefined process models.      |
| **PM Process Version**           | A version of a process mining process                        | Track and manage iterations of process mining analyses as processes evolve over time.                       |
| **PM Recording**                 | Recording of process execution in process mining             | Capture and replay process execution to identify bottlenecks and improvement opportunities.                  |
| **PM Template**                  | Template for activities in process mining                    | Use standardized templates for recurring process mining tasks to ensure consistency and efficiency.         |
| **PM View**                      | Visualization within process mining                          | Create customized views to highlight key aspects of the process, facilitating in-depth analysis.            |
| **Privileges Removal Setting**   | Settings for removing user privileges                        | Configure the conditions under which user privileges are revoked, enhancing security and compliance.        |
| **Record Filter**                | Filter for records display and actions                       | Apply filters to database queries in apps to display or process only records that meet specific criteria.   |
| **RetentionConfig**              | Data retention policy settings                               | Set up data retention policies to automatically delete old data, complying with privacy regulations.        |
| **RoleEditorLayout**             | Layout for role editor interface                             | Customize the layout of the role editor to streamline the management of user roles and permissions.         |
| **Schedule**                     | Scheduling tasks or workflows                                | Configure schedules for automated workflows, ensuring timely execution of tasks like data backups or reports. |
| **Shared Link Setting**                      | Settings for managing shared links within the app                     | Control access and permissions for shared links to app resources, enhancing security and collaboration.             |
| **Site Component**                           | Components part of a site within Power Apps                           | Use specific site components, like custom forms or navigation elements, to enhance the functionality of a Power Apps portal. |
| **Site Language**                            | Language settings for a site within Power Apps                        | Configure multilingual support for a Power Apps portal, allowing users to interact in their preferred language.     |
| **Solution Component Attribute Configuration**| Configuration for attributes of components within a solution          | Define and customize the properties of components within a solution, such as fields in a custom entity.             |
| **Solution Component Batch Configuration**   | Configuration for batch processing of solution components             | Set up batch operations for deploying or updating multiple components within a solution efficiently.                |
| **Solution Component Configuration**         | General configuration settings for solution components                | Specify general settings for solution components, affecting how they behave or interact with other components.       |
| **Solution Component Relationship Configuration**| Configuration for relationships between solution components       | Define how different components of a solution relate to each other, such as entity relationships in Dataverse.      |
| **Synapse Link Profile**                     | Configuration profile for Azure Synapse Link                          | Set up integration between Power Platform and Azure Synapse to seamlessly analyze and act on business data.         |
| **Synapse Link Profile Entity**              | Entity within a Synapse Link profile                                  | Define the data structure and management rules for synchronizing data between Power Platform and Azure Synapse.     |
| **Synapse Link Schedule**                    | Schedule for data synchronization between Power Platform and Azure Synapse| Configure the frequency of data synchronization to ensure up-to-date data availability for analysis.             |
| **Team Template**                | Templates for creating teams in Power Platform                  | Quickly set up new teams with predefined roles and permissions for a project, ensuring efficient collaboration and access control. |
| **Tour**                         | Guided tour or instructional sequence in Power Platform         | Provide new users with a guided tour of a Power App, helping them understand the app's features and navigation. |
| **Virtual Entity Metadata**      | Metadata configurations for virtual entities                    | Integrate external data sources as virtual entities in Power Apps, making external data appear as if it is part of the Dataverse. |
| **Work Queue**                   | Queue for work items in Power Automate or Power Virtual Agents  | Manage a queue of customer service requests in Power Virtual Agents, prioritizing and assigning them to agents. |
| **Work Queue Item**              | Individual items in a work queue                                | Track and process individual tasks in a Power Automate workflow, such as approval requests or data validation jobs. |
| **Workflow Action Status**       | Status indicators for workflow actions                          | Monitor the status of various actions within a Power Automate workflow, identifying any issues needing attention. |
