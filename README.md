# portfolio-wall
Trainee Projects Showcase

## How to Add Your Project

Follow these steps to add your existing GitHub project to the showcase:

### Step 1: Prepare Your Project Repository
- Ensure your project is in a **public GitHub repository**
- Make sure it has a clear **README.md** with:
  - Project description
  - Setup/installation instructions
  - Screenshots or demo
  - Technologies used

### Step 2: Fork the Portfolio-Wall Repository
- Go to the portfolio-wall repository on GitHub
- Click the **"Fork"** button in the top right
- This creates a copy in your GitHub account

### Step 3: Clone Your Fork
```bash
git clone https://github.com/[your-username]/portfolio-wall.git
cd portfolio-wall
```

### Step 4: Add Your Project as a Submodule
Use the following naming format: **`isc-sef_cohort_firstname_lastname`**

```bash
git submodule add https://github.com/[your-username]/[your-project] projects/isc-sef_cohort_firstname_lastname
```

**Example:**
```bash
git submodule add https://github.com/jane-doe/weather-app projects/isc-sef_c2_jane_doe
```

Replace:
- `cohort` with your cohort number/name
- `firstname` with your first name
- `lastname` with your last name

### Step 5: Commit and Push to Your Fork
```bash
git add .
git commit -m "Add [your-project-name] to showcase"
git push origin main
```

### Step 6: Create a Pull Request
- Go to your forked repository on GitHub
- Click **"Contribute"** → **"Open pull request"**
- Add a clear title: "Add [your-project-name] to showcase"
- Describe your project briefly in the PR description
- Click **"Create pull request"**

### Step 7: Wait for Review
- A maintainer will review your submission
- Once approved, your project will be merged into the showcase!

### Important Notes:
- Your project remains in your own repository with full control
- The portfolio-wall only stores a reference link to your project
- Keep your project repository public so others can view it
- Clicking your project in the showcase will take visitors directly to your repository

### Need Help?
If you encounter any issues, reach out to the repository maintainer or create an issue.