# Setup Instructions

The main visualization file (refcocos_visual_comparison.html) is too large to be uploaded directly through GitHub's web interface or API (approximately 15MB).

## Manual Upload Instructions

1. Clone this repository:
   ```
   git clone https://github.com/dddraxxx/refcocos-visual-comparison.git
   cd refcocos-visual-comparison
   ```

2. Replace the placeholder index.html with your actual HTML file:
   ```
   cp /path/to/your/refcocos_visual_comparison.html index.html
   ```

3. Commit and push the changes:
   ```
   git add index.html
   git commit -m "Upload full visualization file"
   git push
   ```

4. After pushing, GitHub Pages will automatically update with your visualization.

## Accessing the GitHub Pages Site

Once deployed, your visualization will be available at:
https://dddraxxx.github.io/refcocos-visual-comparison/

## Alternative Hosting Methods

If the file is too large for GitHub Pages, consider:
1. Splitting the visualization into smaller chunks
2. Using a file hosting service and embedding the link
3. Setting up a dedicated web server for the visualization