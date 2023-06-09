# Course Upload Procedures

This document provides the necessary steps for uploading course material to our platform. Please ensure to follow all the steps outlined here for the successful and organized uploading of the course.

## Steps for Course Upload

### Step 1: Prepare the Course Materials
Ensure the course materials are ready and organized based on the course outline. All related documents, slides, and resources should be grouped together.

### Step 2: Navigate to the Right Directory
Using your command-line interface or preferred file explorer, navigate to the `src/course-materials` directory in your project's root directory.

### Step 3: Choose the Correct Category
Each course belongs to a specific category. Find the directory that corresponds to your course category inside the `src/course-materials` directory. If it doesn't exist, create a new directory with the name of the correct category.

### Step 4: Upload the Course Material
Upload all the course material files to the directory corresponding to the category. Make sure to use a clear and consistent naming scheme for your files to help with organization.

### Step 5: Process Files with Gatsby
We use Gatsby, a powerful static site generator, to process our course files. Specifically, we use a plugin that creates File nodes from files. These nodes can then be transformed into different types of data, depending on their original file type.

For instance, if your course materials are written in Markdown, the `gatsby-transformer-remark` plugin will transform them into `MarkdownRemark` nodes, which Gatsby can further process and display.

## Things to Remember:

- Always ensure your course materials are in the correct category. This makes it easier for others to find and use your materials.
- Our Gatsby plugins automatically handle the transformation of file types. If you are uploading a type of file not currently supported, please contact the development team.
- Ensure to follow proper naming conventions for your files. This aids in organization and resource retrieval.

Product Engineering will help you if you encounter any issues do not hesitate to reach out.
