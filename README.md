# <img src="https://github.com/user-attachments/assets/ce00e7ba-290c-4000-96d8-79a3aba2bf85" alt="STOCKPL Icon" height="50" /> STOCKPL

STOCKPL is a full-stack, responsive inventory management web app built with Next.js, designed for efficient shoe stock tracking. It provides real-time insights on inventory, sales, and automated profit/loss calculations. The application leverages AWS services including EC2 for hosting, S3 for storage, RDS for database management, API Gateway for API integration, and Amplify for deployment. STOCKPL demonstrates effective use of cloud infrastructure, offering a scalable and user-friendly solution for streamlined inventory control.

🔗 [Website-Link](https://master.dl709113y1ftq.amplifyapp.com/)

# Features 
- **📦 Real-time Inventory Tracking:** Monitor stock levels and get instant updates on available shoe inventory.
- **📊 Sales Analytics:** View detailed insights on sales performance with visualized data.
- **💰 Profit and Loss Calculation:** Automatically calculates profit and loss based on sales data.
- **🗄️ Cloud Storage with AWS S3:** Securely stores images and documents using AWS S3.
- **🗃️ Robust Database Management:** Utilizes AWS RDS for efficient and scalable database operations.
- **🌐 API Integration via AWS Gateway:** Enables seamless communication with external APIs.
- **🚀 Scalable Deployment:** Hosted on AWS EC2 and deployed using AWS Amplify for a reliable, scalable experience.
- **📱 Fully Responsive Design:** Optimized for desktop and mobile devices for enhanced user experience.

# System Architecture
  ![image](https://github.com/user-attachments/assets/3d2667db-ba0a-41d3-a716-380f8f616425)


# How to use Amazon Services

## 1. Join AWS
To create an AWS account
1. Open https://aws.amazon.com and select [Create an AWS Account].
2. Follow the online instructions.


## 2. Create IAM user
To create an administrator user and log in to the console
1. Create an admin user named adminuser in your AWS account. For instructions, See [Creating Users and Administrators Groups for the First Time](https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started_create-admin-group.html).
2. Users can log in to the AWS Management console using specific URLs. For more information, See [How to log in to your account in the User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started_how-users-sign-in.html).

## 3. You're All Set! 🚀

## Getting Started
## 1. Clone the repository:
```
git clone https://github.com/varunsainadh-116/STOCKPL.git
cd client
```
```
.env NEXT_PUBLIC_API_BASE_URL=http://localhost:8000
```
```
cd server

.env  PORT=8000
DATABASE_URL="postgresql://username:password@localhost:5432/database_name?schema=public"

```
## 2. Install dependencies:
```
npm install

```
## 3. First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
## 4. 🖥️ EC2 Setup Instructions (Inside Main Server Folder)
