# How to Update Paper Links - Simple Guide

## Option 1: Edit the Simple Text File (Easiest)

Open `paper_links_simple.txt` and fill in your links like this:

```
# Paper 1
https://arxiv.org/abs/2025.12345 | https://github.com/yourusername/repo1

# Paper 2
https://arxiv.org/abs/2025.67890 | 

# Paper 3
https://openreview.net/forum?id=xxxxx | https://github.com/yourusername/repo3
```

**Format:** `paper_url | code_url`
- If no code, just leave it empty: `https://paper-url | `

## Option 2: Edit the Detailed File

Open `paper_links.txt` and fill in each `paper_url:` and `code_url:` line.

## Option 3: Edit CSV File

Open `paper_links.csv` and fill in the `paper_url` and `code_url` columns.

## After Filling In:

Once you've filled in your links, tell me and I'll update the HTML file automatically for you!

Or if you prefer, you can manually edit `index.html` and replace the `#` in each `<a href="#">` with your actual URLs.

## Example Links:

- **arXiv paper**: `https://arxiv.org/abs/2025.12345`
- **Conference page**: `https://openreview.net/forum?id=xxxxx`
- **GitHub code**: `https://github.com/yourusername/reponame`
- **Project page**: `https://yourprojectpage.com`
