# Project Name: Browse4Pets

## Project Description:
Browse4Pets is a responsive pet shop landing page built using HTML and  Tailwind CSS, with a focus on positioning classes like absolute, relative, z-index, and layout techniques. This project helped me become confident with Tailwind positioning utilities and responsive design challenges.

## Project Demo Video: 
https://github.com/user-attachments/assets/af5859bd-72f1-46ef-bc3e-f1942ee9efc7

## Live Site Link:
https://muhammad-tamim.github.io/web_project_9/

## What I newly learned while building this project:

### 1. Pomodoro Technique for Productive Study
- I initially set my Pomodoro timer to 1 hour of study and a 10-minute break. I thought the traditional 25 minutes of focus with a 5-minute break was a waste of time. However, after reflecting on my experience, I realized that the traditional 25-minute focus and 5-minute break (with a 15-minute break after 4 sessions) is actually the most effective. It keeps my brain refreshed and helps me stay stress-free during study sessions.

### 2. Troubleshooting and Avoiding the "Rebuild Everything" Approach
- When I encountered issues, I used to spend 10-15 minutes trying to figure out what went wrong. If I couldn't find the issue, I would often delete everything I built in that section and start from scratch. I’ve learned that this is not the best approach. In the future, I will focus on finding and fixing the error without rewriting the entire section, no matter how long it takes.

### 3. Staying Focused on One Task at a Time
- While working on the project, I noticed that if I wrote all the code at once in a section, like styling the HTML structure and switching between them, it caused confusion and wasted time. I realized that it’s more efficient to complete a task fully before moving to the next. In the future, I will focus on coding one task at a time. For example, if I’m coding the navbar heading, I will finish everything related to that heading (HTML and styling) before moving on to the next part of the project.

### 4. Customizing Chrome DevTools for Tailwind Breakpoints
- I encountered issues with responsive design because the default breakpoints in Chrome DevTools didn’t match Tailwind’s breakpoints. To solve this, I customized the DevTools by adding Tailwind’s breakpoints, which saved me a lot of time and made working with responsiveness much easier and less stressful.
![Screenshot 2025-05-03 201538](https://github.com/user-attachments/assets/25034232-2f1a-48dd-831b-ccdf9b5a5eed)

### 4. **Trending Products Section**
![image](https://github.com/user-attachments/assets/a7f69dec-f104-4926-b086-ea16b6941a99)

- In the "Trending Products" section, I spent a lot of time trying to achieve full-width cards in the parent container using Flexbox. The parent container was set to flex, and the left side had only one large card, which was fine. However, on the right side, there were 9 cards, and because I used `justify-between`, the left and right side cards were pushed to the edges of the page.
I tried increasing the padding to make the right-side cards full-width, but it was a temporary solution and didn’t work well across different breakpoints. After a lot of trial and error, I finally tried adding `w-full` to the parent container of the right-side cards when using `grid`, and it worked.

- so I learn if code doesn’t work, don’t quit. Keep trying to maintain a pixel-perfect design according to Figma or your design file. The struggles I faced during this process taught me valuable lessons on troubleshooting and finding better solutions.

# Project Tracking Report (Which Took a Bit More Time)

## 1. **Initial Project Setup**

### Why:
- Collecting the Figma file, images, and other resources.
- Setting up the favicon, Tailwind CSS, Google Fonts, Font Awesome, custom Tailwind settings, and the basic HTML structure.

### Solution:
- I customized my VS Code HTML default Emmet abbreviations by editing the `html.json` file.
- Example of my custom Emmet abbreviation:

```html
<!-- Write "tw" to get Emmet -->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
    <!-- Favicon -->
    <link rel="shortcut icon" href="" type="image/x-icon">
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <!-- Google Fonts -->
    <!-- Font Awesome -->
    <script src="https://kit.fontawesome.com/2188e87f2e.js" crossorigin="anonymous"></script>
    <!-- Custom Tailwind CSS -->
    <style type="text/tailwindcss">
        @theme {
            /* Add any custom theme overrides here */
        }
    </style>
</head>

<body class="font-sora">
    <header>
        <nav></nav>
        <!-- Section -->
        <section></section>
        <!-- End Section -->
    </header>
    <main>
        <!-- Section -->
        <section></section>
        <!-- End Section -->
        <!-- Section -->
        <section></section>
        <!-- End Section -->
        <!-- Section -->
        <section></section>
        <!-- End Section -->
        <!-- Section -->
        <section></section>
        <!-- End Section -->
        <!-- Section -->
        <section></section>
        <!-- End Section -->
        <!-- Section -->
        <section></section>
        <!-- End Section -->
    </main>
    <footer>
    </footer>
</body>
</html>
```
---

### 2. **Navbar Section**

#### Why:
- I took more time thinking about the design while coding.

#### Solution:
- For future sections, I will first visualize the section properly using the Lightshot app before starting to code. This will help me better plan the design and avoid unnecessary delays.
![Screenshot_1](https://github.com/user-attachments/assets/96fab810-7892-42ae-8587-a9eea1ec8b9e)

---

### 3. **Hero Section**

#### Why:
- Initially, I thought using a background image would help me achieve the design, but after spending half an hour coding, I realized it would be easier to use position and z-index classes. This approach would have saved me time if I had thought about it earlier.

#### Solution:
- I need to focus more time on planning and thinking before jumping into coding. This will save time and effort by preventing unnecessary coding mistakes.

## Final Thoughts
Thank you so much for checking out my project!
If you have any suggestions or feedback, feel free to share them.
