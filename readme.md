# Fatima Ahmed Campaign Website

## Website Structure
```
EDUCATIONWEBSITE/
├── assets/
│   └── logo.jpg          # Campaign logo
├── css/
│   └── styles.css        # Main styles (Don't modify)
└── pages/
    ├── index.html        # Home page
    ├── about.html        # About page
    ├── voting.html       # Voting info
    └── more.html         # More links
```

## Page Assignments - need to decide
- Home Page (index.html): [Developer Name]
- About Page (about.html): [Developer Name]
- Voting Page (voting.html): [Developer Name]
- More Links (more.html): Celina Anwar

## Setting Up Your Work Environment

### First Time Setup
1. Clone the website:
```bash
git clone https://github.com/cia161/educationWebsite.git 
cd EDUCATIONWEBSITE
```

2. Create your branch based on your page:
```bash
git checkout -b about    # if working on about page
git checkout -b voting   # if working on voting page
git checkout -b index    # if working on home page
git checkout -b more     # if working on more links page
```

### Every Time You Work
1. Make sure you're on your branch:
```bash
# See what branch you're on
git branch

# Switch to your branch if needed
git checkout about     # for about page
git checkout voting    # for voting page
etc...
```

2. Get any updates from main:
```bash
git pull origin main
```

### Saving Your Work
After making changes:
```bash
# Add your changes
git add .

# Save your changes
git commit -m "Describe what you changed"

# Upload to GitHub
git push origin about    # if on about branch
git push origin voting   # if on voting branch
etc....
```

## Editing Your Page

### Where to Add Content
1. Open your page (like about.html)
2. Find the content section:
```html
<main>
    <div class="content">
        <!-- ADD YOUR CONTENT HERE -->
    </div>
</main>
```

### Where to Add Custom CSS
Add your page's custom styles in the head section:
```html
<head>
    <!-- Don't touch the first stylesheet link -->
    <link rel="stylesheet" href="../css/styles.css">

    <!-- Add your custom CSS here -->
    <style>
        /* Your custom CSS goes here */
    </style>
</head>
```

### What Not to Change
- Don't modify the navigation bar
- Don't change styles.css
- Don't touch the mobile menu script
- Don't edit pages you're not assigned to

## Colors
- Blue: RGB(0, 57, 98)
- Orange: RGB(241, 96, 43)
- font... need to decide on our pwn 

## Testing Your Work
1. Simply double-click your HTML file to open it in a browser
2. Test on different browser windows/sizes to check mobile view
3. Refresh the page to see any changes you make

## Need Help?
Contact Celina if you:
- Can't switch to your branch
- Are getting error messages
- Need help fixing something