# **Cloudsine AI: VirusScan Take-Home Assignment**

Welcome to the Cloudsine AI take-home assignment! This task is designed to evaluate your coding skills, problem-solving abilities, and approach to designing a functional and secure application.

---

## **Objective**
The goal of this assignment is to set up a web application hosted on AWS, integrating with the VirusTotal API to securely upload and scan files for malware or viruses.

---

## **Features**
1. **File Upload**: A straightforward and user-friendly interface to upload files.
2. **Real-Time Scanning**: Integration with the [VirusTotal API](https://support.virustotal.com/hc/en-us/articles/115002100149-API4) for real-time malware detection.
3. **Result Display**: Display scan results on the webpage in a clear and organized format.
4. **Optional Enhancements**:
   - Database integration to store uploaded files and scan results.
   - Secure deployment using HTTPS.

---

## **Assignment Steps**

### **Step 1: Set Up the Web Server**
1. Set up a web server (Server X) on AWS.
   - Refer to [this guide](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/install-LAMP.html) for a sample LAMP setup.
   - You can also use other web servers like **NGINX** or **Flask**, depending on your preference.
2. Ensure the server is properly configured and accessible for hosting the web application.

---

### **Step 2: Develop the Web Application**
1. **Build a Webpage**:
   - Create a file upload feature.
   - Integrate the VirusTotal API to scan uploaded files.
   - Display the scan results in a user-friendly manner.
2. **Choose Your Technology**:
   - Use any programming language or framework (e.g., Python, PHP, JavaScript).
   - Follow web security best practices.

---

### **Step 3: Upload Files and Display Results**
1. Use the webpage to upload the sample files provided in this repository.
2. Scan the files using the VirusTotal API.
3. Display the results on the webpage in a clear and readable format.

---

## **Example Workflow**
1. A file is uploaded via the webpage hosted on the AWS server.
2. The application sends the file to the VirusTotal API for scanning.
3. The API response is processed, and the results are optionally stored in a database.
4. The results are displayed on the webpage.

---

## **Bonus Section: Optional Challenges**
To stand out, consider implementing one or more of the following optional features:
1. **Database Integration**:
   - Use a database like PostgreSQL to store uploaded files and scan results.
   - Enable users to view a history of their scans.
3. **CI/CD Pipeline**:
   - Automate deployments using a CI/CD pipeline (e.g., GitHub Actions).
4. **Integration Testing**:
   - Implement integration tests for file uploads and API calls.
5. **Advanced UI/UX**:
   - Design a responsive and professional user interface.
6. **AWS Services**:
   - Utilize AWS services such as RDS for database hosting or S3 for file storage.

---

## **Evaluation Criteria**
We will evaluate your submission based on:
1. **Functionality**: Does the application meet the assignment requirements?
2. **Code Quality**: Is the code modular, maintainable, and well-documented?
3. **Problem-Solving**: How effectively did you address challenges during development?
4. **Innovation**: Did you implement any optional features or enhancements?
5. **Presentation**: Is the solution clear, structured, and well-executed?

---

## **Resources**
- [AWS LAMP Server Setup Guide](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/install-LAMP.html)  
- [VirusTotal API Documentation](https://support.virustotal.com/hc/en-us/articles/115002100149-API4)  
- [PostgreSQL Quick Start Guide](https://www.postgresql.org/docs/current/tutorial.html)  

---

## **Submission Requirements**
1. **Server Setup**:
   - Provide an overview of how you set up the server, including challenges faced and solutions.
2. **Source Code**:
   - Share your codebase with clear documentation and comments.
3. **Results**:
   - Present the VirusTotal scan results as displayed on the webpage.

Be prepared to discuss:
- Your design and development process.
- How you addressed any technical challenges.
- Optional features implemented and their impact.

---

## **Getting Started**
1. Clone this repository and review the provided sample files.
2. Set up your AWS server and deploy the web application.
3. Test the file upload and VirusTotal integration locally before deploying to the cloud.

---

We look forward to seeing your submission and learning about your approach to solving this challenge!  
**Cloudsine AI Team**  
