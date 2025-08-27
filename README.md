📊 n8n + Gemini Spreadsheet Summary Automation

This project demonstrates how to build an AI-powered spreadsheet automation using n8n and Google Gemini. The workflow automatically analyzes data from a spreadsheet and generates a concise summary column based on previous column values.

🔹 Features

🔄 Automated Data Processing – Fetches data from Google Sheets in real-time.

🤖 AI-Powered Summaries – Uses Google Gemini to generate context-aware summaries.

📝 Dynamic Updates – Automatically fills the summary column for each row.

⚡ No Code / Low Code – Entire pipeline built using n8n workflows.

🔑 Customizable – Easily adjust prompts, data columns, and summary style.

🔹 Tech Stack

n8n
 – Workflow automation platform

Google Sheets
 – Data source

Google Gemini API
 – Text analysis & summarization

🔹 How It Works

Trigger Node (Google Sheets) – Fetches new or updated rows.

Gemini Node (HTTP Request) – Sends row data to Gemini API for analysis.

Summary Generation – Gemini returns a text summary of the given row.

Update Node (Google Sheets) – Writes the summary back into the spreadsheet.

🔹 Example Use Cases

Summarizing customer feedback automatically.

Generating task overviews from project management data.

Creating quick insights from large datasets.

Auto-filling "Notes" or "Summary" columns in spreadsheets.

🔹 Getting Started

Clone this repository.

Import the provided n8n workflow JSON into your n8n instance.

Set up your Google Sheets credentials in n8n.

Add your Google Gemini API key in the HTTP Request node.

Run the workflow and watch summaries auto-populate 🚀.

🔹 Future Improvements

Support for multiple spreadsheet formats (Excel, CSV).

Adding filters to summarize only specific rows.

Multi-language summary generation.

⚡ With this project, you can make your spreadsheets smarter, faster, and AI-driven, saving hours of manual summarization work.
