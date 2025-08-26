# Demo Roof Website

Simple test website for testing the roof-scanner-plugin embed functionality.

## Quick Start

### 1. Start the Widget Dev Server
```bash
cd roof-scanner-plugin
npm run dev  # Runs on http://localhost:3333
```

### 2. Start the Demo Website
```bash
cd demo-roof-website
npm run dev  # Runs on http://localhost:8080
```

### 3. Test the Embed
Open browser to: **http://localhost:8080**

## What to Test

1. **Blue circular button** appears in bottom-right corner (overlay mode)
2. **"Open Roof Scanner" button** also triggers the modal 
3. **Modal opens** with placeholder content
4. **ESC key** or clicking backdrop closes modal

## Files

- `index.html` - Main test page with embed script
- `package.json` - Simple server script
- `README.md` - This file