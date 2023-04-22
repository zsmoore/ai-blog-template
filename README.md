## AI Blog Template

### What? A template for a next js site that hooks into notion db for pulling blog posts

Use in partnership with [ai-blog-ingestion-template](https://github.com/zsmoore/ai-blog-ingestion-template) to populate posts.
  
### How to setup?

Create .env.local and add the following values
- `NOTION_TOKEN` - Notion API Key
- `DATABASE_ID` - Notion Database ID to pull from
- `NEXT_PUBLIC_WEBSITE_TITLE` - Title for your site enclosed in `"`
- `NEXT_PUBLIC_WEBSITE_SUBTITLE` - Subtitle for your site to be displayed on homepage enclosed in `"`
  
Change name in package.json and package-lock.json from ai-blog-template to your project name.  
Change share url in components/share.tsx to your website's url.
  
Deploy to vercel and make sure to include the same environment variables.
  
*PreReq* Sign up for notion.  Get an API Key.  Create a page which is a basic DB. Grab your key and DB id.
