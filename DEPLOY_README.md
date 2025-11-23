# JSONHero Web — Vercel Deployment Pack

This zip contains the necessary configuration files to deploy jsonhero-web on Vercel.

## Files
- `vercel.json` — Vercel project configuration.
- `.env.example` — Environment variables template.
- `DEPLOY_README.md` — Instructions.

## Steps
1. Clone the original repo:  
   git clone https://github.com/triggerdotdev/jsonhero-web

2. Copy the contents of this ZIP into the root of the project.

3. On Vercel:
   - Create a new project from the GitHub repo.
   - Add environment variable:
     - SESSION_SECRET = your value  
   - Deploy.

4. Vercel will run:
   npm install  
   npm run build

5. Your app will deploy successfully.
