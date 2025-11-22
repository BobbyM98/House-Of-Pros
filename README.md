# House of Pros Entertainment

The official website for House of Pros Entertainment, featuring exclusive streetwear collections and the latest music releases from ZedEye.

## 🚀 How to Run Locally

1.  **Download** all files into a folder.
2.  **Install Node.js** (if you haven't already).
3.  Open your terminal/command prompt in the project folder.
4.  Run the following commands:

```bash
# Install dependencies
npm install

# Start the development server
npm run dev
```

5.  Open the link shown in the terminal (usually `http://localhost:5173`).

## 📦 How to Build for Production

To create the final files for deployment:

```bash
npm run build
```

This will create a `dist` folder containing your optimized website.

## 🌐 Deployment (Netlify)

1.  **Verify Domain**: Ensure you have clicked the verification link sent to your email by Namecheap for `houseofprosentertainment.space`.
2.  **Deploy**:
    *   Upload this project to GitHub.
    *   Connect GitHub to Netlify.
    *   **Build Command**: `npm run build`
    *   **Publish Directory**: `dist`
3.  **DNS**: Point your Namecheap Custom DNS to Netlify's nameservers.

## 📝 Project Structure

*   `src/App.tsx`: Main application component.
*   `src/constants.ts`: **EDIT THIS FILE** to update links, images, and text.
*   `src/components/`: Contains all UI sections (Hero, ProductGrid, Discography, etc.).
