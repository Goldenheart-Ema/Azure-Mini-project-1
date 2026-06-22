# Azure-Mini-project-1

# How to Create a Microsoft Azure Account

This guide provides a comprehensive step-by-step process for setting up a **Microsoft Azure Free Account** or an **Azure for Students** account. It includes essential preparation checklists, registration paths and post-signup billing configuration instructions to ensure zero accidental spend.

# Prerequisites Checklist
Before beginning the sign-up process, ensure you have the following requirements ready:

* Microsoft or GitHub Account: An active Outlook, Hotmail or GitHub login. (Can be created during the process).
* Active Phone Number: Required for instant mobile identity verification.
* Payment Card: A valid, non-prepaid **Credit or Debit card** (Visa, Mastercard or American Express).

* *Note: Virtual or prepaid cards will be rejected.*

# Step-by-Step Sign-Up Process

# Step 1: Access the Registration Portal
1. Open your web browser and navigate to the official [Microsoft Azure Free Account Page](https://microsoft.com).
2. Click the **Start free** button.

# Step 2: Authenticate or Create an Account
1. You will be redirected to the secure Microsoft login portal.
2. Enter your existing Microsoft email address and password.
3. If you do not have one, click **Create one!** to provision a free `@outlook.com` address.

# Step 3: Fill Out Profile Information
1. On the **About you** form, select your exact country/region.
2. Provide your legal first name, last name and contact email address.
3. Input your physical address and postal code. 
* Crucial: The physical address must exactly match the billing address on file with your bank card.*

# Step 4: Verify Identity via Phone
1. Select your specific country code and enter your active mobile phone number.
2. Select either **Text me** or **Call me**.
3. Type the 6-digit verification code received on your phone into the portal prompt and hit **Verify**.

# Step 5: Verify Identity by Card
1. Enter your cardholder name, card number, expiration date and CVV security code.
2. Double-check that the displayed billing address matches your bank record.
3. Submit the form to authorize the identity validation check.

* Troubleshooting: If the submission hangs, clear your browser cookies or enable third-party cookies.*

# Step 6: Finalize Agreement and Sign Up
1. Check the box to accept the **Microsoft Azure Agreement** and Privacy Statement.
2. Click the **Sign up** button.
3. Once configured, click **Go to Azure Portal** or navigate directly to `https://azure.com` to launch your dashboard.

# Alternative: Azure for Students (No Card Required)
If you are an active student at an accredited high school, college or university, you can bypass the payment card requirement completely.

1. Go to the [Azure for Students Portal](https://microsoft.com).
2. Click **Activate now**.
3. Log in using your institutional school email address (e.g., ending in `.edu`).
4. **Benefit**: Grants **$100 in free credit** renewed annually and access to key services without a credit card.

# Crucial Post-Signup: Setting Up a Budget Alert
To guarantee you never overshoot your free trial credits, set up a hard budget threshold inside the portal immediately after creating your account:

1. Log into the [Azure Portal](https://azure.com).
2. Search for **Cost Management + Billing** in the top global search bar and click it.
3. Click **Budgets** from the left-hand navigation pane.
4. Click **+ Add** at the top of the interface.
5. Define your target configuration:
    *   **Name**: `Free-Trial-Guard`
    *   **Reset Period**: `Monthly`
    *   **Amount**: Set this to `$50` or `$100` (well below your $200 free trial cap).
6. Click **Next** to configure specific alert conditions:
    *   **Trigger 1**: Set Type to `Actual`, % of budget to `50` (Sends an early notification).
    *   **Trigger 2**: Set Type to `Actual`, % of budget to `90` (Signals extreme proximity to cap).
    *   **Trigger 3**: Set Type to `Forecasted`, % of budget to `100` (Triggers immediately if predictive algorithms indicate you will exceed your cap by month's end).
7. Input your email address in the **Alert recipients** box and click **Create**.

# Azure Portal Navigation and key services

# Portal Navigation Quick Start
1.  **Home / Dashboard**: Your customizable landing page for quick access to resources and activity logs.
2.  **All Services (Burger Menu)**: The full directory of Azures offerings, filterable by category.
3.  **Global search (Top Bar)**: The fastest way to find services, resources and documentation.
4.  **Copilot**: An AI assistant to help you write scripts, optimize costs and troubleshoot infrastructure.
5.  **Azure Cloud Shell (>_)**: A browser based terminal for managing resources via CLI or Powershell.
6.  **Notification (Bell Icon)**: Real time status tracking for active deployments, resource updates and credit alerts.
7.  **Settings (Gear Icon)**: Customize your portal layout, default directories, color themes and timeout periods.
8.  **Support+Troubleshooting (? Icon)**: Access officila documentation, check azure service health or summit formal support tickets.
9.  **Feedback**: Direct pipeline to send feature suggestions or bugs directly to Microsoft's product team.

# Key Services
1.  # Virtual Machine (VM)
2.  # App Services
3.  # Storage Accounts
4.  # Azure SQL Database
5.  # Virtual Network (VNet)
6.  # Load Balancer

# Azure Free Tier Limits & Scope
The Azure Free Account provides access to specific resources divided into three strict boundaries. Keeping deployments within these bounds ensures you avoid unexpected charges.  

1. # The 30-Day Setup Period
**$200 Free Credit**: Automatically applied upon signup. Expires exactly 30 days after registration.  
**Full Catalog Access**: Can be spent on almost any Azure product (except third-party Marketplace items).  

2. # The 12-Month Popular Service Caps
After your 30 days expire, you retain monthly allowances for over 20 popular services for 12 months, capped strictly at:  
**Compute**: 750 hours/month of B1S, B2pts v2 (ARM), or B2ats v2 (AMD) Burstable VMs (Linux and Windows combined).  
**Storage**: 5 GB of standard Blob storage + 5 GB of File storage.
**Databases**: 250 GB of Azure SQL database storage per month + 750 hours of Flexible PostgreSQL/MySQL.

3. # Always-Free Services
Over 55+ services remain free permanently, provided you do not exceed their monthly capacity triggers:  
**Azure Functions**: 1 million serverless requests per month.  
**App Services**: Up to 10 web, mobile, or API apps (F1 Free tier, sharing 1 GB storage).  
**Azure Cosmos DB**: 1,000 RU/s throughput with 25 GB of storage.  

*Important*: To prevent active services from being paused or deleted after day 30, you must manually upgrade your subscription to Pay-As-You-Go. You will only be billed if your active services surpass the monthly caps outlined above.



