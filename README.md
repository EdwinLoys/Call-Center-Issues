
# 📞 Call Tagging System

A web-based application built with **ASP.NET Core MVC** for tracking and managing customer service calls.  
This system allows agents to log call details, categorize issues, and generate reports.

---

## 🚀 Features

### 🔐 Secure Login System
- Agent authentication with 6-digit agent numbers  
- Password encryption using **BCrypt**  
- Session management for logged-in users  

### 📋 Call Logging
- Record call details including:
  - Agent phone number
  - Connection type
  - Category (e.g., Broadband)
  - Problem types (multiple selections allowed)
  - Issue type
  - Timestamp
- Automatic validation of required fields  
- Support for multiple problem tags per call  

### 🔎 Search and Reporting
- Advanced search functionality with multiple filters:
  - Date range
  - Category
  - Connection type
- Export search results to **Excel**  
- View and manage call records  

---

## 🛠️ Technical Stack
- **Backend:** ASP.NET Core MVC  
- **Database:** MySQL  
- **ORM:** Entity Framework Core  
- **Authentication:** BCrypt.NET  
- **Excel Export:** ClosedXML  
- **Session Management:** ASP.NET Core Session  

---

## 📂 Project Structure


