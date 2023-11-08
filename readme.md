# Setting Up a Tailwind CSS Environment

## Description:

In this exercise, you will explore what Tailwind CSS is and set up a development environment for using Tailwind CSS in your web projects.

## Instructions:

Ok, we're going to work with TailwindCSS but... what is exactly TailwindCSS? Let's see what the official website says about it:

> Tailwind CSS is a highly customizable, low-level CSS framework that gives you all of the building blocks you need to build bespoke designs without any annoying opinionated styles you have to fight to override. Tailwind CSS is a utility-first CSS framework for rapidly building custom user interfaces.

Utility-first means that TailwindCSS is a CSS framework that provides you with a set of ready-to-use classes that you can use to style your HTML elements. It's a great tool to use when you want to quickly prototype a web page or application. It's also a great tool to use when you want to build a custom design without having to write a lot of CSS code.

Let's do some steps so that we understand the importance of the TailwindCSS website and understanding how to create the environment:

1.  **Introduction to Tailwind CSS:**

    - Start by visiting the official Tailwind CSS website: [Tailwind CSS](https://tailwindcss.com/).
    - Explore the website and try to understand the benefits of using Tailwind CSS.
    - Lastly, run your html file in the browser to see the results.

2.  **Installation Guide:**

    - Navigate to the "Installation" section on the official Tailwind CSS website. You can find it here: [Installation](https://tailwindcss.com/docs/installation).
    - How many ways are there to install Tailwind CSS? What does the page say about the pros and cons of each method?
    - Use the CDN method to see if you can get Tailwind CSS working in your HTML file. You can use the CDN link provided in the installation guide.
    - Once you get it, delete the CDN link and follow the instructions to install Tailwind CSS with the "Using PostCSS" guide. If you don't have it already, you'll need to install Node.js and npm to complete this step.

3.  **HTML Page:**

    - You already have a sample HTML page in this folder. This has certain TailwindCSS classes already applied to it. What are these classes doing?
    - Have a look at the documentation to see what these classes are doing. You can find it here: [Tailwind CSS Documentation](https://tailwindcss.com/docs).

4.  **Using Tailwind Classes:**

    - Create a new `div` for example, and try to apply the following classes: `bg-blue-500`, `text-white`, `p-4`... can you see any differences?

5.  **Publish to Netlify**

        - Github offers us ghpages to deploy our projects, but we are going to use Netlify, which is a platform that allows us to deploy our projects in a very simple way and allows dynamic pages. To do this, we must follow the following steps:
        - If your previous setup is correct, you should get a /dist folder in your project. This folder contains the index.html file and the css file that we have generated with TailwindCSS. Parcel is responsible for generating this folder and its content. It's all what we need to deploy our project.
        - Check out the Netlify website: [Netlify](https://www.netlify.com/).
        - Create an account on Netlify.
        - Have a look at the following guide to learn how to deploy your site to Netlify: [Netlify Guide](https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/).

6.  **Share your Netlify Link in Moodle**

    - Once you have published your page, share the link with your peers and ask them to review it.
