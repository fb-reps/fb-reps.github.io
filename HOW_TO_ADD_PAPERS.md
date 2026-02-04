# How to Add Your Paper Information

## Step 1: Add Paper Figures

1. **Go to the folder**: `images/papers/`
2. **Add your paper figures** with these exact names:
   - `paper1.png` - First publication
   - `paper2.png` - Second publication
   - `paper3.png` - Third publication
   - `paper4.png` - Fourth publication
   - `paper5.png` - Fifth publication
   - `paper6.png` - Sixth publication
   - `paper7.png` - Seventh publication

**Tips:**
- Use PNG or JPG format
- Recommended width: 200-300 pixels
- Keep file size under 500KB for fast loading
- Use clear, representative figures from your papers

## Step 2: Update Paper Links

Open `index.html` and find each publication section. Update these parts:

### For each paper, update:

1. **Paper link** (the "paper" link):
   ```html
   <a href="YOUR_PAPER_PDF_URL" class="paper-link">paper</a>
   ```
   Replace `YOUR_PAPER_PDF_URL` with:
   - Link to arXiv (e.g., `https://arxiv.org/abs/2025.12345`)
   - Link to conference/journal page
   - Link to your hosted PDF

2. **Code link** (the "code" link):
   ```html
   <a href="YOUR_CODE_REPO_URL" class="code-link">code</a>
   ```
   Replace `YOUR_CODE_REPO_URL` with:
   - GitHub repository link (e.g., `https://github.com/username/repo`)
   - Or remove this line if no code is available

### Example:

**Before:**
```html
<p class="publication-links">
  <a href="#" class="paper-link">paper</a>
  <a href="#" class="code-link">code</a>
</p>
```

**After:**
```html
<p class="publication-links">
  <a href="https://arxiv.org/abs/2025.12345" class="paper-link">paper</a>
  <a href="https://github.com/yourusername/yourrepo" class="code-link">code</a>
</p>
```

## Step 3: Verify

1. Refresh your browser at `http://10.120.61.18:8000`
2. Check that:
   - All figures display correctly
   - Paper links work
   - Code links work (or are removed if not available)

## Current Publication Order

1. **paper1.png** → Robust Ego-Exo Correspondence with Long-Term Memory
2. **paper2.png** → Breaking Latent Prior Bias in Detectors for Generalizable AIGC Image Detection
3. **paper3.png** → VLForgery Face Triad: Detection, Localization and Attribution via Multimodal Large Language Models
4. **paper4.png** → PRVQL: Progressive Knowledge-Guided Refinement for Robust Egocentric Visual Query Localization
5. **paper5.png** → Generating Higher-Quality Anti-Forensics DeepFakes with Adversarial Sharpening Mask
6. **paper6.png** → Synthesizing Black-Box Anti-Forensics DeepFakes with High Visual Quality
7. **paper7.png** → Securing Facial Bioinformation by Eliminating Adversarial Perturbations

## Need Help?

- Check `images/papers/README.md` for more details about figures
- All paper information is already filled in from your CV
- You just need to add the figures and update the links!
