# Overview
This is the Round 1 submission web app for TDS Project 1 (LLMPages). It generates and links all required artifacts directly in the browser so they can be downloaded and inspected:
- uid.txt (matches the provided UID)
- LICENSE (MIT License text)
- about.md (exactly three words)
- ashravan.txt (narrative meeting content requirements)
- dilemma.json (assigned pelican-crossing scenario)
- pelican.svg (valid SVG, with embedded LLM rating metadata)
- restaurant.json (internally consistent data and order totals)
- prediction.json (reasonable 7-day forecast with prediction intervals)

The page also runs lightweight automated checks to validate structure and content.

# Setup
No build is required.
- Save the provided index.html as-is.
- Open it in any modern browser (offline is fine).

# Usage
- Open index.html in your browser.
- Scroll to “Required Files” to preview content and download each artifact via the Download buttons.
- See “Auto Checks” for quick validation results.
- Inline previews are provided for pelican.svg (rendered) and dilemma.json (raw JSON).