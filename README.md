# erouska-firebase
Firebase serverless backend for eRouška

### Local execution
```bash
export GOOGLE_APPLICATION_CREDENTIALS=<path to service account JSON>
export GCP_PROJECT=<project name>
export FIREBASE_BUCKET=<Firebase Storage bucket>

cd functions
npm run build && node lib/index.js 
```
