# Fenton Tax & Bookkeeping Services – WordPress Deployment

This WordPress site is designed to support and showcase digital marketing efforts—specifically **PPC advertising**, **SEO**, and **Email Marketing**—for Fenton Tax & Bookkeeping Services.

## 📌 Project Purpose

The goal of this site is to act as a digital hub for running campaigns, capturing leads, and tracking performance through customized tools and integrations.

## 📁 Directory Structure

Only two core components are maintained in version control:

```
/wp-content/your-theme  
/wp-content/your-site-specific-plugin
```

### `/your-theme`

A custom WordPress theme used to control layout, user experience, and visual branding. This may include:

- SEO-friendly markup  
- Schema integration  
- Responsive design  
- Lead capture templates (e.g., landing pages)

### `/your-site-specific-plugin`

A bespoke plugin built for this site. Typical features may include:

- Custom post types or taxonomies  
- Campaign tracking tools (e.g., UTM logger, analytics hooks)  
- Newsletter opt-ins and form handlers  
- Email marketing automation hooks (e.g., Mailchimp or SMTP tools)

## ⚙️ Getting Started

1. Install WordPress on your local or staging environment.  
2. Copy the theme into:  
   ```
   /wp-content/themes/your-theme
   ```
3. Copy the plugin into:  
   ```
   /wp-content/plugins/your-site-specific-plugin
   ```
4. Activate the theme and plugin from the WordPress Admin Panel.  
5. Install any required dependencies via the theme or plugin README (if present).

## 🔐 Notes

- Ensure proper permission management if handling sensitive tax information.  
- Consider GDPR/CAN-SPAM compliance for email-related features.  
- Backup before every update.

## 🧑‍💻 Contributions

All custom code lives in the theme and plugin directories. Please avoid modifying WordPress core or uploading site-specific logic elsewhere.
