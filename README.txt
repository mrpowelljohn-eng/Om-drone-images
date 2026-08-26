OM Drone Images V7.1 — Mobile-Safe Founder Image Fix

Why this version exists:
GitHub mobile can flatten folders during upload. V7 expected the founder image at:
assets/drone-founder-v7.png

This mobile-safe version keeps the image in the repository root:
drone-founder-v7.png

Upload/replace in the existing om-drone-images repository:
- index.html
- drone-founder-v7.png
- README.txt

Commit to main. Vercel should redeploy automatically.
