# AI-Driven Trailer Management System

## Project Title
AI-Driven Trailer Management System for Optimized Inventory Delivery with QR-Based Tracking

## Problem Statement
The current process of delivering inventory from distribution centers to stores faces significant challenges due to unreliable manual decision-making and inconsistent communication between managers and administrators. This results in inefficiencies, delays, and errors in deliveries, adversely affecting the overall supply chain. To overcome these issues, an optimized trailer management system is needed to automate these tasks, ensuring timely deliveries, reducing human error, and improving coordination across all levels of the supply chain.

## Solution
We've developed an automated system that optimizes Walmart's delivery management by leveraging advanced AI models. The system operates as follows:

1. **Data Collection**: Real-time data on inventory, sales, trailer availability, and driver details is gathered.
  
2. **AI Decision-Making**: 
   - An AI model determines the urgency of deliveries and decides which inventory to dispatch.
   - Generative AI plans the most efficient delivery routes, taking into account specific requirements, such as those for cold chain products.
   - Another AI model assigns the best trailer for each delivery, considering trailer availability and driver reliability.

3. **QR-Based Tracking**: 
   - Each delivery is linked to a QR code containing relevant details, including the associated bill.
   - Drivers receive these QR codes and route instructions on their dashboards, following the planned routes while verifying their locations with GPS.
   - Store managers scan the QR code to confirm delivery, view product lists, and access billing details. They also can reject deliveries before dispatch.

4. **Automation and Communication**: 
   - The system ensures accurate delivery planning and enhances communication among drivers, store managers, and administrators, making the delivery process more reliable and efficient.

## Technology Stack
- **Frontend**:
  - React.js: For building the user interface.
  - Tailwind CSS: For styling the application.
  - Chart.js: For data visualizations and dashboard components.

- **Backend**:
  - Express.js: For handling server-side logic and API requests.
  - MongoDB: For managing and storing data.
  - Cloudinary: For image storage and management.

- **AI Models**:
  - **Mistral MoE** (Mixture of Experts): Ensures accurate delivery planning by leveraging AI-driven decision-making processes.
  - **Generative AI**: Optimizes route planning and trailer assignment.

## Key Features
- **Real-Time Data Integration**: Continuous data gathering on inventory, sales, trailer availability, and driver details.
- **AI-Powered Decision Making**: Automated decisions for inventory dispatch, route planning, and trailer assignment.
- **QR-Based Tracking**: Streamlined tracking and verification process using QR codes.
- **Driver Dashboard**: Provides drivers with delivery details, route instructions, and GPS verification.
- **Store Manager Interface**: Allows store managers to confirm or reject deliveries, view product lists, and access billing details.

## Architect Diagram 

![WhatsApp Image 2024-08-15 at 1 24 36 PM](https://github.com/user-attachments/assets/14d3805c-2709-4aeb-b5d3-2156ce2c4089)

## AI model Diagram

![image](https://github.com/user-attachments/assets/1ce2d189-63bd-442d-bcd2-048078dce898)

## YT Video Link 

[![Watch the video](https://img.youtube.com/vi/p0HcXKrnb-I/hqdefault.jpg)](https://youtu.be/p0HcXKrnb-I?si=m8KiYJlKyjxoXwVp)


## Usage
1. **Admin Panel**: Admins can manage inventory, monitor deliveries, and oversee the entire system.
2. **Driver Mobile App**: Drivers can view their assigned deliveries, scan QR codes, and follow optimized routes.
3. **Store Interface**: Store managers can scan QR codes, confirm or reject deliveries, and access detailed billing information.

