cd ~/capstone-repo

cat > README.md << 'EOF'
# Capstone Project

## Overview
One-line description of what this project does and who it's for.

## Tech Stack
- Frontend:
- Backend:
- AI/Tooling: Claude Code

## Getting Started

    npm install
    npm run dev

## Status
🚧 In progress — Week 1: environment setup

This is the capstone project for FlyRank's Frontend AI Engineering track.

## License
MIT
EOF

git add README.md
git commit -m "fix: restore missing getting-started commands in README"
git push
