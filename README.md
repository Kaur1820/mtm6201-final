# Best Paws Rescue – Final Project (MTM6201)

This project is my final assignment for **Web Development II**. It is a fully responsive, accessible three-page website built using the Bootstrap framework. The design follows the mockups, wireframes, and branding I created in my User Experience Design course.

The goal of this project was to create a polished, functional website for a fictional dog rescue, while demonstrating skills in responsive design, accessibility, Bootstrap customization, and GitHub deployment.

---

## 🔧 Process & How I Built the Website

### **1. UX to Development**
I began by reviewing my high-fidelity wireframes and layout decisions created in Figma. These guided the spacing, visual hierarchy, navigation, and styles of each page.

### **2. Project Setup**
- Created a GitHub repository named `mtm6201-final`
- Followed naming rules (lowercase, hyphens, no spaces)
- Organized all files clearly (HTML, CSS, images)

### **3. Coding the Website**
I used:
- Bootstrap Grid for layout  
- Bootstrap utilities for spacing, alignment, and responsive breakpoints  
- CSS variables to override the default Bootstrap theme  

This helped keep styles consistent and easy to update.

### **4. Responsive Images**
I exported two sizes of each image (small + large) and used the `<picture>` element and `srcset` to load the best size depending on the device.  
This improves loading speed and follows proper responsive media guidelines.

### **5. Accessibility**
I added:
- Semantic HTML (`main`, `nav`, `footer`)  
- Skip-to-main-content link  
- Keyboard-friendly navigation  
- Meaningful alt text for all images  
- Clear contrast and readable typography  
- ARIA roles where appropriate  

### **6. Deployment**
The website is published using **GitHub Pages**, making it accessible at:

`https://kaur1820.github.io/mtm6201-final/

---

##  Challenges & How I Overcame Them

### **• Making the layout fully responsive**
Some sections collapsed incorrectly on tablet sizes.  
**Solution:** Adjusted Bootstrap breakpoints and added custom CSS media queries.

### **• Implementing `<picture>` and `srcset`**
It took testing to make sure the correct image loaded on the correct screen.  
**Solution:** Used Chrome DevTools to test multiple screen widths.

### **• Keeping Bootstrap from looking too generic**
Bootstrap defaults looked plain.  
**Solution:** Customized theme colors using CSS variables and added shadows, rounded corners, and a consistent visual style.

### **• Ensuring accessibility**
Keyboard navigation and skip links required extra attention.  
**Solution:** Manually tested with keyboard-only navigation and improved alt text and structure.

---

##  What I Learned

Through this project, I learned:

- How to customize Bootstrap using CSS variables  
- How to translate Figma designs into real coded layouts  
- How to make images responsive with `<picture>` and `srcset`  
- How accessibility affects design and coding  
- How to deploy a project using GitHub Pages  
- How to structure a multi-page responsive website  

This project strengthened both my development and design decision-making skills.

---

##  Assets, Frameworks & Resources Used

### **Frameworks & Libraries**
- Bootstrap 5.3.2  
- Google Fonts (Poppins)  
- Custom CSS  

### **JavaScript**
- Bootstrap JS Bundle (for navbar functionality)


### **AI-Generated Images**
- Dog images (Brandon, Buddy, Max, Daisy) generated through ChatGPT — copyright-free  

### **Fonts**
- Google Fonts – Poppins (free to use)

---
figma link 
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/design/FxheivE1DqzpZc7UKgQWjx/Untitled?embed-host=share" allowfullscreen></iframe>

#

