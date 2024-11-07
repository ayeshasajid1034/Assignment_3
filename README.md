# DevOps Course 2024 - Assignment 3

This repository contains the work completed for the DevOps Course 2024 assignment, which includes:

- Guide to Learning and Contribution
- A sample landing page with my CV.
- View Blog Summaries
- Sample repo from the internet and applying DevOps tooling.Pick and choose (your existing) knowledge and expand it to guide.

## Documentation:
- [CV](https://ayeshasajid1034.github.io/DevOps_Assignment_3/)
- [View Blog Summaries](blog_summaries.md)
- [View Learning and Contribution](https://github.com/ayeshasajid1034/DevOps_Assignment_3/blob/main/Guide_to_Learning_and_Contribution.md)


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Doctor Appointment System:

A test app to show doctors, patient & appointments system to just show microservices & their responses
This is a sample application, which consists of

frontend: a simple frontend application which shows Doctors & Appointments in UI form
doctors: a backend app written in python, which shows list of doctors
appointments: a backend app written in python, which shows list of appointments




---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Blog Summaries

## Blog 1 Summary:
GitOps: The Future of Kubernetes and Cloud-Native Deployments GitOps has revolutionized the way we handle cloud-native and Kubernetes deployments by making infrastructure management scalable, automated, and more secure. At the core of GitOps is the principle that Git serves as the single source of truth for both application code and infrastructure configurations. This approach uses a continuous synchronization loop that ensures the system’s actual state matches the desired state defined in Git.

## Key Points:

Declarative Infrastructure: GitOps relies on defining infrastructure in a declarative manner, ensuring consistency across environments. Auditability: Every change is recorded in Git, providing a complete history and making rollbacks seamless. Automation and Consistency: Automation tools, like Argo CD and Flux, continuously monitor and synchronize with Git to prevent configuration drift. GitOps Workflow: Involves pushing changes to Git, running through CI pipelines for validation, and using tools like Argo CD to sync with Kubernetes. Benefits: GitOps provides scalability, enhanced security, easy rollbacks, and reduced human error by automating processes. Challenges and Best Practices: Address complexities in large teams, manage permissions securely, and ensure environments are properly monitored to detect drift. GitOps has become a gold standard for deploying applications in modern cloud-native environments, offering benefits like rapid deployments and reliability. As this paradigm evolves, teams must follow best practices to fully leverage its potential.


## Blog 2 Summary: 
Kubernetes Autoscaling: Optimizing Resource Utilization Kubernetes autoscaling is crucial for optimizing resources and handling fluctuating workloads. Autoscaling ensures that applications have just the right amount of resources, dynamically adjusting as the demand changes, thereby maximizing performance while minimizing costs.

Types of Kubernetes Autoscalers:

Horizontal Pod Autoscaler (HPA): Automatically adjusts the number of Pods based on CPU, memory, or custom metrics. HPA increases the number of Pods when traffic spikes and decreases them during low activity periods. Vertical Pod Autoscaler (VPA): Adjusts the resource requests and limits of Pods based on historical and real-time data, optimizing resource allocation. Cluster Autoscaler: Scales the entire cluster by adding or removing nodes based on unscheduled Pods. It integrates with cloud providers like AWS, GCP, and Azure for efficient resource management. Setting Up HPA:

Deploy your application and create an HPA to monitor CPU usage. Use kubectl commands to apply configurations and verify that autoscaling is working correctly. Best Practices:

Reasonable Limits: Set min and max replicas to avoid over- or under-provisioning. Performance Monitoring: Use tools like Prometheus and Grafana for data-driven scaling decisions. Combining HPA and VPA: Use both to optimize resource usage and the number of Pods. Testing in Staging: Ensure autoscaling configurations are validated in a non-production environment. Custom Metrics: Sometimes, custom metrics provide better scaling criteria than default CPU/memory metrics. Kubernetes autoscaling provides flexibility and efficiency in managing resources, ensuring that applications can handle variable traffic with minimal resource wastage.

## Link to Blogs:  
             https://medium.com/@i200862/gitops-the-future-of-kubernetes-and-cloud-native-deployments-32f741537bd5
             https://medium.com/@i200862/kubernetes-autoscaling-a-guide-to-efficient-resource-management-e4cd792cf937


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Guide to Learning and Contribution:

1. 🎓 Learning Plan
A. Foundational Knowledge
Programming Languages: Continue strengthening skills in Python and JavaScript. Focus on writing clean, efficient code and understanding data structures and algorithms.
Operating Systems & Networking: Learn the fundamentals of Linux, shell scripting, and how networking works (e.g., DNS, HTTP, TCP/IP) as these are crucial in the DevOps world.
Version Control Systems: Master Git and GitHub for efficient collaboration and version control..
B. DevOps & Cloud Technologies
Containers & Orchestration: Gain proficiency in Docker and Kubernetes. Understand how to build, manage, and deploy applications in a containerized environment.
Cloud Platforms: Learn about AWS, Azure, or Google Cloud Platform. Start with services like EC2, S3, and Lambda, and understand concepts like cloud storage, networking, and load balancing.
Infrastructure as Code (IaC): Study Terraform or AWS CloudFormation to automate infrastructure provisioning.
Continuous Integration/Continuous Deployment (CI/CD): Set up a CI/CD pipeline using tools like Jenkins, GitHub Actions, or GitLab CI/CD.

2. 🌐 Contribution Goals
   Content Creation
Write Blog Posts: Written blogs on medium related to Devops tools which helped me to explore and learn more.


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## CV

# Hi 👋, I'm Ayesha Sajid
Enthusiastic and driven Computer Science graduate with a strong foundation in Artificial Intelligence, Machine Learning, Deep Learning, and Natural Language Processing, along with a passion for website development. Looking to leverage my skills in a professional setting to contribute to innovative projects and continuous learning.

---

### 📫 Connect with me:
- **Email**: (ayeshaas299@gmail.com)
- **LinkedIn**: [linkedin.com/in/ayesha-sajid-5a761b220](https://www.linkedin.com/in/ayesha-sajid-5a761b220)
- **GitHub**: (https://github.com/ayeshasajid1034)

---

### 🎯 Objective
Enthusiastic and driven Computer Science graduate with a strong foundation in Artificial Intelligence, Machine Learning, Deep Learning, and Natural Language Processing. Passionate about website development and seeking opportunities to contribute to innovative projects and continue learning.

---

### 🎓 Education
- **BS in Computer Science**  
  *FAST NUCES*  
  *Graduation Year: 2025*

---

### 💡 Skills
- **Programming Languages**: Python, JavaScript, C++
- **AI & Machine Learning**: TensorFlow, PyTorch, Scikit-Learn
- **Deep Learning**: CNNs, RNNs
- **Natural Language Processing**: Text Preprocessing, Sentiment Analysis, Language Models
- **Web Development**: HTML, CSS, JavaScript, React, Node.js
- **Data Analysis**: Pandas, NumPy, Matplotlib
- **Version Control**: Git, GitHub

---

### 🛠️ Tools & Technologies
<p align="left">
  <a href="https://aws.amazon.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" width="40" height="40"/></a>
  <a href="https://www.python.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/></a>
  <a href="https://reactjs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="40" height="40"/></a>
  <a href="https://www.tensorflow.org" target="_blank"><img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="TensorFlow" width="40" height="40"/></a>
  <a href="https://pytorch.org/" target="_blank"><img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="PyTorch" width="40" height="40"/></a>
  <a href="https://nodejs.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" width="40" height="40"/></a>
  <!-- Add more icons as needed -->
</p>

---

### 📁 Projects

- **AI-Driven Investment Bot for Stock Prediction**  
  *Description*: Creating a bot that predicts stock performance using financial indicators, focusing on the tech sector in Pakistan.

---

### 💼 Experience
- **Intern, AI and Machine Learning**  
  *Funavry Technologies, Islamabad*  
  *Duration: June 2023 - Aug 2023*  
  - Worked on data pre processing.

---



