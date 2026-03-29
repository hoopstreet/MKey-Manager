MKey Manager: Internal Business Automation & API Management
MKey Manager is a proprietary middleware and configuration handler designed exclusively for Hoopstreet Sports Apparel Accessories Shop (DTI Business Name No. 7918311). This repository serves as the central hub for managing API integrations, OAuth2 redirect flows, and internal commerce logic for the TikTok Shop Philippines marketplace.  
🚀 Overview
This tool is built to streamline the operations of Hoopstreet by automating high-frequency tasks within the TikTok Shop Affiliate ecosystem. It acts as the "brain" connecting our data sources to our content production engine.
Core Functionalities:
• Product Synchronization: Automates the fetching of live product data, including titles, descriptions, and high-resolution images from the TikTok Shop Affiliate Marketplace.  
• Content Automation: Orchestrates the generation of video metadata and upload drafts for automated affiliate marketing campaigns targeting the Philippine market.  
• Link Management: Programmatically generates "Yellow Basket" selection links to ensure accurate commission attribution for promoted sports apparel.  
• OAuth2 & Token Management: Securely handles access_token and refresh_token exchanges for our internal n8n automation workflows.
🛠 Technical Stack
• Primary Logic: Node.js / n8n (Workflow Orchestration)
• Database: Supabase (PostgreSQL for product metadata storage)
• Infrastructure: Oracle Cloud Free Tier / Proxmox (High-availability self-hosting)
• Security: YubiKey MFA for admin access and AES-256 encryption for API secrets.
• Integrations: TikTok Shop Open API (Custom Partner App)
🛡 Security & Compliance
• Internal Use Only: This application is a Custom App intended solely for the internal business operations of Hoopstreet. It is not a public-facing service or a multi-tenant SaaS.  
• Data Privacy: We strictly adhere to the Philippines Data Privacy Act of 2012. No customer personal identifiable information (PII) is processed or stored; our logic is strictly limited to product and affiliate metadata.  
• OAuth Security: All Redirect URLs and Webhooks are secured via HTTPS and strictly validated against our TikTok Shop Partner Center credentials.
• Identity Management: Access to this manager is restricted via hardware-based 2FA (YubiKey) to prevent unauthorized API calls.
🏢 Organization Information
• Legal Entity: HOOPSTREET SPORTS APPAREL ACCESSORIES SHOP  
• DTI Registration: 7918311  
• Registered Owner: Charles Tanauan  
• Location: Barangay 49, Young Field, Tacloban City, 6500, Philippines  
📧 Contact & Support
For technical inquiries, compliance audits, or API partnership discussions, please reach out to the development lead:
• Lead Developer: Charles Tanauan (Alextzy)
• Email: charlestanauan35@gmail.com  
• Official Website: hoopstreet.space
Copyright © 2026 Hoopstreet Sports Apparel Accessories Shop. All rights reserved.
