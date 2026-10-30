# team4_emc_project
# Wanderly - Travel Agency Website

A 5-page travel agency website built by Team 4 for the Week 3 DevOps group activity. The goal of the project is to practise Git, GitHub, branching strategies, and team collaboration while building a real website together.

## About the website

Wanderly is a travel agency site where visitors can explore destinations, view travel packages, learn about the agency, and get in touch to plan a trip.

## Pages and contributors

| Page | File | Owner |
|------|------|-------|
| Home | `index.html` | Vinayak |
| Destinations | `destinations.html` | Dhanush |
| Packages | `packages.html` | Foushia |
| About Us | `about.html` | Rajalakshmi |
| Contact | `contact.html` | Guna |

All pages share one stylesheet (`style.css`) and the same header and footer.

## Tech used

- HTML5
- CSS3
- Git and GitHub for version control and collaboration

## Project structure

```
wanderly/
├── index.html
├── destinations.html
├── packages.html
├── about.html
├── contact.html
├── style.css
└── README.md
```

## How to run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the project folder.
3. Open `index.html` in any web browser. Use the navbar to move between pages.

No installation or build step is needed.

## Git workflow

We followed a branch-per-feature strategy:

- `main`: the final, working website

**Steps each member followed:**

1. Pull the latest code from `main`.
2. Create a feature branch for their page.
3. Build the page and commit changes with clear messages.
4. Push the branch to GitHub and open a pull request into `main`.
5. After review, merge the pull request into `main`.

## Common Git commands used

```bash
git clone <url>                  # copy the repo to your computer
git checkout -b feature/<page>   # create and switch to a new branch
git status                       # see changed files
git add .                        # stage changes
git commit -m "message"          # save changes with a message
git push origin <branch>         # upload your branch to GitHub
git pull                         # get the latest changes
git merge <branch>               # combine branches
```

## Team guidelines

- Each member edits only their own page.
- Use the shared header and footer exactly as in `index.html`.
- Use the existing classes in `style.css`. Put page-only styles in that page's own `<style>` block.
- Tell the team before changing shared files such as `style.css` or the navbar.
- Use the agreed file names so navbar links work: `index`, `destinations`, `packages`, `about`, `contact`.
- Pull the latest changes before starting work, and write clear commit messages.

```