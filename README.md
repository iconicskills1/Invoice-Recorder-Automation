# Invoice Recorder Automation (n8n workflow)
This n8n workflow automates the end-to-end processing of invoice emails, including attachment extraction, AI-powered invoice data parsing, structured record storage, and automatic finance notification emails. Focused on business automation, AI-powered document processing, and finance workflow optimisation.
It is designed to eliminate manual invoice handling by converting raw supplier emails and PDF attachments into structured financial records stored directly in Google Sheets — while simultaneously generating clean, formatted summary emails for finance teams.


## A.	Key Features

**1. Automated Invoice Email Intake**
* Reads incoming Gmail messages
* Filters invoice-related emails
* Detects PDF attachments automatically

**2.	PDF Invoice Text Extraction**
* Extracts raw text from invoice attachments
* Captures invoice metadata such as creation date

**3.	AI-Based Invoice Data Parsing**
* Extracts:
    * Invoice number
    * Supplier name
    * Invoice date & due dates
    * Line items
    * Currency and total amount
•	Uses structured JSON extraction for high accuracy

**4.	Line Item Normalization**
* Converts invoice items into readable structured formats
* Generates cost breakdown tables automatically

**5.	Automated Finance Email Generation**
* Builds professional HTML invoice summary emails
*	Sends formatted breakdown directly to finance team
*	Generates plain-text copy for logging and storage

**6.	Centralized Invoice Database**
*	Automatically stores invoice records in Google Sheets
*	Maintains searchable invoice history
*	Prevents duplicate entries using email ID matching

## B.	System Architecture Overview

This automation connects multiple business tools into one streamlined workflow:
*	n8n Automation Engine — Process orchestration
*	Gmail API — Invoice email ingestion and notifications
*	PDF Extraction Engine — Attachment text processing
*	OpenRouter LLM — AI invoice data extraction
*	Google Sheets — Financial record storage
*	HTML Email Builder — Finance-ready invoice summaries


## C.	Typical Use Cases

*	Accounts payable automation
*	Finance inbox processing
*	Vendor invoice management
*	Expense tracking workflows
*	Small business accounting automation
*	Paperless finance operations


## D.	Requirements

To deploy this workflow successfully:
*	n8n instance (self-hosted or cloud)
*	Gmail OAuth credentials
*	Google Sheets OAuth credentials
*	OpenRouter API key
*	Google Spreadsheet template for invoice storage


## E.	Keywords

 
* #InvoiceAutomation
* #AccountsPayable
* #FinanceAutomation
#ExpenseManagement
#AccountingAutomation
#PaperlessFinance
 


## F.	Author

Developed by **Engr. Adnan Aslam** 
  * (92) 300 7972999
  * as.associates.ryk@gmail.com
