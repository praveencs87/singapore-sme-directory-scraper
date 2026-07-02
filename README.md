# Singapore SME Directory Scraper

**Extract verified Small and Medium Enterprises (SMEs), startups, and local businesses across Singapore.**

The Singapore SME Directory Scraper is an advanced data extraction tool tailored for Southeast Asia's primary financial and technology hub. It seamlessly extracts premium B2B supplier and business data from top Singaporean local business directories.

## What can Singapore SME Scraper do?

- ✅ **Extract SG Business Leads** - Get company names, physical addresses, and direct contact numbers for Singapore businesses.
- ✅ **Target specific Industries** - Focus your search on IT services, Accounting firms, Logistics companies, and more.
- ✅ **Identify Local Footprint** - Target specific areas like the CBD, Jurong, or Changi (or search all of SG).
- ✅ **Export formats** - Download data in JSON, CSV, Excel, or HTML formats.
- ✅ **Integrations** - Connect seamlessly with API, webhooks, Make, or Zapier.
- ✅ **No coding required** - Use our simple interface to start scraping immediately.

## Why scrape Singapore SME Data?

Singapore's business landscape is dense, high-tech, and incredibly lucrative for B2B services:

- 🎯 **B2B Service Sales** - Sell SaaS, marketing services, or financial consulting to Singaporean startups and SMEs.
- 📊 **Supply Chain Sourcing** - Find reliable logistics partners, wholesale distributors, and manufacturers in the region.
- 📍 **Market Research** - Analyze the density of specific industries (like Fintech or Retail) across different districts in SG.

## What data can you extract?

| Data Field | Description | Example |
|------------|-------------|---------|
| **companyName** | The name of the business | "Tech Solutions Pte Ltd" |
| **category** | Business Industry | "IT Services & Consulting" |
| **address** | The full SG address | "10 Anson Road, International Plaza, Singapore 079903" |
| **phone** | Direct contact number | "+65 6123 4567" |
| **website** | Company website | "https://www.example.sg" |
| **listingUrl** | Link to the directory listing | "https://www.yellowpages.com.sg/..." |

## How to scrape Singapore SME data

1. **Click "Try for free"** to start using the actor.
2. **Enter your input** - Provide a keyword (e.g., "IT services") and an optional location (e.g., "CBD").
3. **Configure options** - Set the maximum number of leads you want to extract.
4. **Start the scraper** - Click Start and let the actor do the work.
5. **Download results** - Export your leads as JSON, CSV, or Excel.

## Input

Configure the scraper with these key settings:
- **Keyword** - The specific industry or service (e.g., 'IT services', 'logistics', 'accounting').
- **Location** - (Optional) Singapore Region (e.g., 'CBD', 'Jurong'). Leave blank to search all of SG.
- **Maximum Leads** - The total number of records to extract.
- **Proxy Configuration** - Apify Residential Proxy (Singapore targeted) is highly required to bypass blocks.

## Output

You can download data in multiple formats:
- **JSON** - For developers and programmatic access
- **CSV** - For easy import into Excel or CRM systems
- **Excel** - Ready-to-use spreadsheet

### Output example

```json
{
    "companyName": "Tech Solutions Pte Ltd",
    "category": "IT Services",
    "address": "10 Anson Road, International Plaza, Singapore 079903",
    "phone": "+6561234567",
    "website": "https://www.example.sg",
    "listingUrl": "https://www.yellowpages.com.sg/...",
    "scrapedAt": "2026-07-02T15:00:00Z"
}
```

## How much does it cost?

This actor uses a Pay-Per-Event (PPE) pricing model tailored for high-quality Singapore B2B leads:
- **Base Fee**: $0.25 per start
- **Lead Fee**: $3.00 per 1,000 SME leads extracted ($0.003 per lead)

**Free tier**: Apify provides $5 in free monthly credits, allowing you to extract over 1,500 premium Singapore leads for free!

## Is it legal to scrape?

Yes, scraping publicly available data is generally legal. This Actor only extracts public information.

**Best practices**:
- Use the data ethically for B2B outreach in compliance with Singapore's PDPA.
- Respect the target site's Terms of Service.
- Ensure compliance with data privacy regulations when handling contact information.

## Integrations

Connect with 1000+ apps:
- **Google Sheets** - Auto-update spreadsheets with new leads.
- **Slack** - Get notifications when scraping finishes.
- **Webhooks** - Send data directly to your CRM.
- **API** - Programmatic access for developers.

---

**License**: Apache-2.0 | **Version**: 1.0.0
