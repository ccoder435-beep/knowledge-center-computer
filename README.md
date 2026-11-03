# Knowledge Centre Computer Education - Patna Website

A modern, high-converting, fully responsive multi-page simulated Single Page Application (SPA) website for **Knowledge Centre Computer Education**, Patna, Bihar.

## 🚀 Live Preview & Deployment
The website is built entirely inside `index.html` with zero build steps or server dependencies. It is 100% ready for:
- Direct local browsing (open `index.html` in any browser or double-click)
- Free deployment on **GitHub Pages**
- Fast hosting on Vercel, Netlify, or Firebase Hosting

## 🌟 Key Features
1. **Corporate Education Theme**:
   - Royal Blue (`#1a56db`) corporate palette with clean white/light gray background.
   - Plus Jakarta Sans typography and Font Awesome 6 icons.
   - 100% responsive on all mobile, tablet, and desktop screens with an interactive hamburger navigation drawer.

2. **Internal Tab / SPA Hash Routing**:
   - Seamless client-side navigation between:
     - `#home` - Hero banner, trust markers, highlights, featured courses, testimonials.
     - `#courses` - Multi-course grid with category filters, checklists, and syllabus modal.
     - `#verify` - Real-time Certificate Verification portal with instant search and printable credential slips.
     - `#about` - Mission, values, 1:1 computer lab facility breakdown.
     - `#gallery` - High-resolution lab and classroom photo gallery with lightbox modal.
     - `#contact` - Operating hours, Patna location, and WhatsApp admission inquiry form.

3. **Multi-Course Grid with Direct WhatsApp Inquiries**:
   - **ADCA (Advance Diploma in Computer Application)** - 12 Months
   - **DCA (Diploma in Computer Application)** - 6 Months
   - **Tally Prime with GST & Accounting** - 3-4 Months
   - **Web Development & Programming (C, Python, HTML/CSS)** - 6 Months
   - **Graphic Design & Video Editing** - 4-6 Months
   - **Advanced Excel with MIS & Data Analysis** - 2 Months
   - *Every course card features a pre-filled WhatsApp link to `+91 78700 76269`.*

4. **Interactive Certificate Verification System**:
   - Search by Roll Number or Registration ID.
   - Sample test roll numbers provided: `KC-2024-101`, `KC-2024-102`, `KC-2023-884`, `KC-PAT-552`.
   - Displays official verified credential card: *"Verified: Student Name, Course Completed Successfully"* with QR hash simulation and print functionality.

5. **Operating Hours & Live Status**:
   - Monday to Saturday (Morning): 6:30 AM – 2:00 PM
   - Monday to Saturday (Evening): 3:00 PM – 9:00 PM
   - Sunday: Closed
   - Real-time JavaScript engine that computes Indian Standard Time (IST) and dynamically highlights whether the lab is currently Open or Closed.

6. **Admission Inquiry Form & WhatsApp Automation**:
   - Fields: Student Name, Mobile Number, Preferred Course, Preferred Shift, and Message.
   - Automatically formats submission into structured WhatsApp message and opens `https://wa.me/917870076269`.

7. **Floating WhatsApp Chat Button**:
   - Fixed at bottom-right corner with pulse ring animation and counselor tooltip.

## 📁 File Structure
```text
knowledge-centre-patna/
├── index.html   (Single-file production website)
└── README.md    (Documentation & GitHub Pages Guide)
```

## 🌐 Deploy to GitHub Pages (2 Minutes)
1. Initialize git in this directory:
   ```bash
   git init
   git add .
   git commit -m "Initial commit for Knowledge Centre Patna website"
   ```
2. Create a new repository on GitHub (e.g. `knowledge-centre-patna`).
3. Link and push:
   ```bash
   git remote add origin https://github.com/<your-username>/knowledge-centre-patna.git
   git branch -M main
   git push -u origin main
   ```
4. On GitHub, go to **Settings > Pages > Branch: `main` > `/ (root)` > Save**.
5. Your website is live worldwide at `https://<your-username>.github.io/knowledge-centre-patna/`!
