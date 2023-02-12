# MLOps-NLP-case-study

MLOps-NLP-case-study
Let’s take a look at the problem statement below.

You are working as a data scientist for a healthtech company called BeHealthy. It is a late-stage startup. Be Healthy provides a web-based platform for doctors to list their services and manage patient interactions. It provides various services for patients, such as booking interactions with doctors and ordering medicines online. (Similar to 1mg, PharmEasy) Here, doctors can easily manage appointments, track past medical records and reports and give e-prescriptions. We can assume that BeHealthy has enrolled thousands of doctors across the major cities in India. You can also assume that millions of patients are using BeHealthy’s services; hence, a lot of free-text clinical notes would be present in the e-prescriptions. BeHealthy would want to convert these free-text clinical notes to structured information for analytics purposes. You have seen such a problem in your previous courses on NLP. You had created a CRF model to recognise the Named Entity in the medical data set.

Please find the notebook and dataset attached here.

For example: Clinical Note: “The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy.” Disease: Lung Cancer Treatment: Radiation Therapy and Chemotherapy

Before solving any business problem, we must always keep in mind why a business needs to resolve the problem. In many cases, data scientists directly jump to the solution, using data sets like Kaggle competitions. But in the real world, you should be able to justify the business need, define KPIs and then design an optimal solution.

Now, let’s take a look at a business goal:

Currently, if you need to extract diseases and treatments from free text, a trained person with clinical knowledge must manually look at the clinical notes and then pull this information. A data entry team would manually look at the clinical text and extract information about diseases and their treatment data. A data validation team would validate the extracted information. This process is prone to errors, and as the data increases, the data-entry team’s size would need to be scaled up.

Automating this process would result in reduced man-hours. The data-entry team would not be required. The data validation team would still need to perform validation on extracted data. It would also significantly reduce manual errors.

Q1. System design: Based on the above information, describe the KPI that the business should track.

Q2. System Design: Your company has decided to build an MLOps system. What advantages would you get by opting to build an MLOps system?

Q3. System design: You must create an ML system that has the features of a complete production stack, from experiment tracking to automated model deployment and monitoring. For the given problem, create an ML system design (diagram).

The MLOps tools that you want to use are up to your judgement. You can use open-source tools, managed service tools or a hybrid. You can use draw.io or any other convenient tool to create the architecture. You can refer to the module on “Designing Machine Learning Systems” for understanding how to create an MLOps Architecture. You can upload the design/diagram as an image in the PDF.

Q4. System design: After creating the architecture, please specify your reasons for choosing the specific tools you chose for the use case.

Q5. Workflow of the solution: You must specify the steps to be taken to build such a system end to end. The steps should mention the tools used in each component and how they are connected with one another to solve the problem. Broadly, the workflow should include the following. Be more comprehensive of each step that is involved here.

Data and model experimentation Automation of data pipeline Automation of the training pipeline Automation of inference pipeline Continuous monitoring pipeline

The workflow should ALSO explain the actions to be taken under the following conditions. After you deployed the model, you noticed that there was a sudden increase in the drift due to a shift in data.

What component/pipeline will be triggered if there is any drift detected? What if the drift detected is beyond an acceptable threshold? What component/pipeline will be triggered if you have additional annotated data? How will you ensure the new data you are getting is in the correct format that the inference pipeline takes?
