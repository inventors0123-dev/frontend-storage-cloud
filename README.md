# Frontend-Only Deployment (Vercel)

This folder is a standalone static frontend version of the project.

## Deploy Steps

1. Push code to GitHub.
2. In Vercel, import the repository.
3. Set **Root Directory** to `frontend`.
4. Deploy.

No Python/Flask environment variables are needed for this frontend-only version.

## Notes

- Data is saved in browser `localStorage`.
- Backend features (database, Google Drive API folder creation) are not included in this static deployment.
