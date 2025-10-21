# 🧱 Project Requirements — Sign-Up Form Page

## Step 1: Setup and Planning

1. **Initialize Git Repository**

   - Create a new project folder.
   - Initialize a Git repository using `git init`.
   - Make your first commit once base files are ready.
   - (Refer to past projects if you need a refresher.)

2. **Set Up Base Files**

   - Create and link the following files:
     - `index.html`
     - `style.css`
   - Add some **dummy content** to verify that your CSS file is linked correctly.

3. **Understand the Layout**
   - Download the **full-resolution design file**.
   - Review the layout and plan how you’ll structure the HTML:
     - Which sections you’ll need
     - How to group content with `<div>` or semantic elements
     - Where to use Flexbox or Grid

---

## Step 2: Gather Assets

1. **Background Image**

   - The design includes a large **background image**.
   - You can find the original on [Unsplash](https://unsplash.com), or choose your own.
   - **Credit the photographer** in your project (e.g., footer comment or README).

2. **Font Selection**

   - The design uses **“Norse Bold”** for the logo.
   - You may choose any **external font** you like (Google Fonts is a great resource).

3. **Logo**
   - Use the **Odin logo** image in the sidebar (provided in the design).
   - Keep it visually balanced with the background and text overlay.

---

## Step 3: Development Tips

1. **Start with Structure**

   - Scaffold the page sections before adding styles:
     - Sidebar with logo
     - Main content area with form
     - Footer or small attribution section

2. **Logo Background Overlay**

   - The “ODIN” logo area uses a **dark, semi-transparent overlay** to improve text visibility.
   - Use a color like `rgba(0, 0, 0, 0.5)` for the background.

3. **Button and Color Palette**

   - The “Create Account” button color: `#596D48`.
   - Match accent colors to tones found in your chosen background image.

4. **Input Field Styles**

   - Default border: `#E5E7EB`
   - Invalid password border: **red**
     - Use `:invalid` pseudo-class.
   - Focused input border: **blue** with a subtle box-shadow
     - Use `:focus` pseudo-class.

5. **Form Validation**

   - **No need for JavaScript yet.**
   - Validate each field individually using built-in HTML attributes.
   - Matching password validation with JS will be covered in a future lesson.

6. **Responsiveness**
   - **Mobile styling is not required** for this project.
   - Focus on the desktop layout only.

---

## ✅ Submission Checklist

- [ ] Git repository initialized and pushed to GitHub
- [ ] Linked HTML and CSS verified
- [ ] Background image and font correctly loaded
- [ ] Form layout matches the design structure
- [ ] Focus and invalid states implemented
- [ ] Project organized and committed in logical stages

---

### 📸 Credits

- Background image: [Unsplash Photographer Name]
- Logo: [The Odin Project / Provided Image]
- Font: [Font name + source]
