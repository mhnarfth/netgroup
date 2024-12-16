# **NetGroup Website Maintenance Documentation**  
### Networks Research Group Website URL: 
- https://cse.unl.edu/~netgroup
- https://mhnarfth.github.io/netgroup/
  
**Repository Link**: https://github.com/mhnarfth/netgroup.git

---

## **1. Introduction**  
- **Purpose**:  
  This document serves as a guide for maintaining and updating the Networks Research Group website.  
- **Audience**:  
  Website administrators, lab members, or anyone responsible for website upkeep.

---

## **2. Website Overview**    
#### **This Website is hosted via ---**
  - UNL CSE Server and 
  - Github pages.  

- **Website Structure**:  
  - **Home Page**: Introduction, news, highlights.
  - **Tour**: Slide deck of pictures of the group.    
  - **People**: Team members, roles, and contact information.  
  - **Projects**: Ongoing and completed projects.  
  - **Publications**: List of research publications.
  - **News**: List of related News.    
  - **Events**: Upcoming and past events.  
  - **Contact**: Contact details and map of the lab.  

---

## **3. Pre-requisites**  
Before updating the website, ensure you have the following:  
1. Access to the **GitHub repository**.  
   - Permissions: Push/Pull rights.  
2. **Code Editor**: VSCode, Atom, or any text editor.  
3. **Hugo Setup**: Depending on your operating system (Windows, Mac, or Linux).  
4. Basic knowledge of:  
   - HTML/CSS.  
   - Git version control.  
   - Hugo static site structure.  

---

## **4. Setting Up Hugo and Development Environment**  
Follow these steps to install Hugo and set up the project:

### **Windows**  
1. Open **Windows Powershell 5** (install it if necessary).
2. Install **Scoop**, the package manager for Windows:
   ```powershell
   Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
   iwr -useb get.scoop.sh | iex
   ```
   Press **Y** and Enter if asked: *Do you want to change the execution policy?*.
3. Install Hugo and its dependencies:
   ```powershell
   scoop install git go hugo-extended nodejs
   ```

### **Mac**  
1. Open the **Terminal** app.
2. Install **Homebrew**, the Mac package manager: 
```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
   ```
3. Apply any Homebrew updates:
   ```bash
   brew update && brew upgrade
   ```
4. Install Hugo and its dependencies:
   ```bash
   brew install git golang hugo node
   ```
5. Open the hidden `~/.zshrc` (or `~/.bashrc`) file in a text editor, add the following line, and restart your Terminal app:
   ```bash
   export PATH=$PATH:/usr/local/go/bin
   ```

### **Linux**  
1. Install Hugo’s Go dependency using Snap:
   ```bash
   sudo snap install --classic go node
   ```
2. For **Ubuntu-based distributions**:
   - Download the Hugo Extended installer for Debian (`hugo_extended_<VERSION>_Linux-64bit.deb`) and double-click the file to install with Ubuntu Software Center.
3. For **other Linux distributions**:
   - Download the Hugo Extended binary (`hugo_extended_<VERSION>_Linux-64bit.tar.gz`).
   - Extract the download and move the `hugo` app to your website folder.
   - Alternatively, move the `hugo` app to your system's app folder and add Hugo to the system path.

---

### **Cloning the Website Repository**  
Once Hugo is set up, clone the GitHub repository or download it as a ZIP file:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/mhnarfth/netgroup.git
   cd repo-name
   ```
2. If downloaded as a ZIP file, extract it and navigate to the folder:
   ```bash
   cd /path/to/website-folder
   ```

---

## **5. Running the Website Locally**  
1. Open a terminal and navigate to the project folder:
   ```bash
   cd /path/to/website-folder
   ```
2. Run the Hugo development server:
   ```bash
   hugo server -D
   ```
   - Visit `http://localhost:1313` to preview the website locally.
   - The `-D` flag ensures draft pages are displayed.
3. Make changes to the content or templates (explained in sections below). Hugo will automatically reload the site in your browser.

---

## **6. Updating Website Content**  


### **Adding an Author**  
1. Go to the `content/authors` folder.
2. Create a new folder and name it as the author's name (make sure it matches the 'Username').
3. Inside the folder, create a file named `_index.md`:
   ```markdown
   ---
  # Display name
  title: M A U Shariff (Mahin)

  # Full name (for SEO)
  first_name: Mohammad Arafath Uddin
  last_name: Shariff

  # Username (this should match the folder name)
  authors:
    - M A U Shariff
   ---
   ```
4. Add the author's image to the same folder, named `avatar.jpg` or `avatar.png`.

---

### **Adding a Project, Event, or News**  
1. Navigate to the **content** folder and locate the relevant section (e.g., `project`, `event`, or `news`).
2. Right-click to **Create a New Folder**.
   - Name the folder with a descriptive URL (lowercase, hyphenated words).  
3. Inside the new folder, create a file named `index.md` and add the following content:
   ```markdown
   ---
   title: "New Title Here"
   date: YYYY-MM-DD
   description: "Brief description of the project or news."
   ---
   Markdown-formatted content here.
   ```
4. Save the file. If adding a featured image, drag an image named "`featured`" into the folder.

---

### **Editing the Tour Page**  
1. Go to the `content/tour` folder and open `index.md`.
2. Copy one existing block (from `title` to the end) and paste it below.
3. Modify the block as needed.
4. Upload any new images to `assets/media/`.
5. Update the image path in the `index.md` file.

---

### **Adding Publications**  
1. Open the `publication.bib` file in the root directory.
2. Add the new publication in **BibTeX format**:
   ```bibtex
   @article{key2024,
     title={New Publication Title},
     author={Author Name},
     year={2024},
     journal={Journal Name},
     volume={X},
     number={Y},
     pages={123--456},
   }
   ```
3. Save the file and **push changes** to GitHub. The publication page will update automatically. You must have to push in order to see the changes (takes couple of minutes) in the publication page. 

4. **If you want to add manually,** goto the `content/publications`,
create a new folder, create `cite.bib` and `index.md` file and fill them accordingly (Check other folders for reference)

---

### **Updating Contact Information**  
1. Go to the `content/contact` folder.
2. Open the `index.md` file and modify the information as needed:
   ```markdown
   email: example@domain.com
   phone: +1-123-456-7890
   address: "Your Address Here"
   ```
3. Save and push the changes to GitHub.

---

## **7. Publishing the Website**

### **Publishing to GitHub Pages**  
1. Once all changes are complete, **push the updates to GitHub**:
   ```bash
   git add .
   git commit -m "Updated website content"
   git push origin main
   ```
2. After a minute or two, the live website will reflect the changes at these URL. You can check any one of these,

- #### https://mhnarfth.github.io/netgroup/ (this will be updated first)
- #### https://netgroup.netlify.app/ 


### **Publishing to UNL CSE Server**  
1. First, build the Hugo website by running:
   ```bash
   hugo
   ```
   - This will generate a folder named `public` in your current directory.
2. Copy the `public` folder to the UNL CSE server:
   - Connect to the server and paste the `public` folder.
3. Rename the folder to **`public_html`**:
   - Ensure the folder is named `public_html` for the updates to display.
4. Your website should now be updated on the UNL CSE server.

---

## **8. Troubleshooting**  
| **Issue**                       | **Solution**                                          |
|---------------------------------|-------------------------------------------------------|
| Changes not showing on live site | Clear browser cache or wait a few minutes.           |
| Local server not starting        | Ensure Hugo is installed correctly; recheck paths.   |
| Broken images or links           | Check file paths and ensure the images are uploaded. |
| GitHub push errors               | Verify your credentials and permissions.             |

---

## **9. Best Practices**  
- Always **test locally** before pushing updates.  
- Use meaningful commit messages.  
- Keep images optimized for faster loading times.  
- Regularly check for broken links or outdated content.  
- Maintain consistency in formatting (use the same structure for all pages).  

---

## **10. Contact Information**  
For further assistance, contact:  
- **Administrator**: M A U Shariff  
- **Email**: `mshariff2@unl.edu`  
- **GitHub Username**: https://github.com/mhnarfth  

---

This documentation ensures smooth maintenance and publishing of the website to both GitHub Pages and the UNL CSE server.
