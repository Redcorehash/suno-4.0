# Update Suno 4.0

```bash
git checkout main
git pull origin main
git fetch --tags
git checkout tags/v4.0 -b update-suno-4.0
# Make your changes here
git add .
git commit -m "Update to Suno 4.0"
git push origin update-suno-4.0
