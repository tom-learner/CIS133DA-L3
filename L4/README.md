# Lesson 4 Project
For this project, you will expand upon a template using what you learned in this lesson to apply structural elements. You will then create your first web page based upon that template. 

>**TIP:** You may need to nest elements to complete the objectives of the assignment. Learn more about Nested HTML Elements at [W3Schools.com](https://www.w3schools.com/html/html_elements.asp)

<br>

## Project Prep
1. Clone the repo to your computer within your course folder.
2. Open the repo within VS Code. You can open this `readme.md` file within VS Code to view the project directions there. 

   >**TIP:** Right click on the file and choose the `Open Preview` option.
3. If there are files and folders present other than this `readme.md` file, take some time to familiarize yourself with the files within the repo so you know where they are located. This will help you when asked to use them within the project directions.
   >**TIP:** Before beginning any work on the project, read through all the steps to understand what you will be doing.

<br>

## Part 1: Improve the Template
1. Open the **template.html** file.
0. **Update the multi-lined comment** with your **Course Name** and **Section Number**.
0. **Update the title element** with the following information:
   {YourMEID} - Template 
   > Replace the {YourMEID} with your actual MEID, like the following example: **ABC1234567 - Template**
0. **Add metadata** elements to define the following elements: 
    - Define the `character encoding` as `UTF-8`. 
    - Define the `author` using your `first` and `last` names.
    - Add `metadata` elements for `keywords` and `descriptions`. Leave the `content` attribute empty for each element. You will be adding content in Part 2 of this project.
0.  **Create a header element**, then complete the following within it:
    - **Add a first level heading** after the opening tag that reads: `Basic Template`.
    - **Add a single paragraph** after the first level heading. 
        - Within the paragraph, write a simple quote that you find inspirational/educational to keep you motivated (*e.g., "A mind once stretched by a new idea never regains its original dimensions"*).
        - **Apply an appropriate text-level semantic element** to the quote to change its appearance to italic. The text should appear in italics, but should not have emphasized importance.
    - **Create a navigation menu** using the NAV element after the slogan paragraph.
      - **Create a hyperlink** within the navigation menu using the following:
        - For the display text: `Placeholder Link`
        - For the target page: use a `hashtag (i.e., #)`. This will make the link clickable, but not navigate away from the current page.
    - **Save** the file. **Sync** your file to GitHub and apply a **Commit** that says, `Header element created`.

0. **Create a main element,** following the HEADER element. Enter the following within the MAIN element:
    - **Add a second level heading** after the opening tag that reads: `Content Heading`
    - **Create a paragraph** filled with dummy text following the heading. 
         > **TIP:** Use an Emmet abbreviation to generate lorem ipsum. Simply type `lorem#` to generate # words of dummy text (Replace # with the number of words you want to generate.)
    - **Save** the file. **Sync** your file to GitHub and apply a **Commit** that says, `Main element created`.


0. **Create a footer element**, following the MAIN element. Enter the following within the FOOTER element:
    - **Add a paragraph element** to display the following copyright info: `Copyright by {FirstName} {LastInitial} {CurrentYear}`
        > **TIP:** Replace {FirstName}, {LastInitial}, {CurrentYear} with your actual information and current year.
        - **Add a copyright symbol** between your last name initial and the year. If you have trouble remembering how to create a copyright symbol, review [Character Entity References](https://riosalado.coursearc.com/content/cis133da-in-v12/lesson-3-introduction-html/hypertext-markup-language#Character-Entity-References) from Lesson 3.
        - **Apply an appropriate text-level semantic element** so the copyright information displays as small print.
     - **Save** the file. **Sync** your file to GitHub and apply a **Commit** that says, `Footer element created`.

0. Within VS Code, correct any validation errors that may appear in your code using the [Web Development Student Extension Pack](https://marketplace.visualstudio.com/items?itemName=RioSaladoCollegeMedia.web-development-student-pack) you installed in Lesson 0: Course Introduction.
    - You may ignore any warnings that may appear with your files. However, you are required to correct any and ***all*** validation **errors**.
0. Make any necessary changes, then **Save** the file. **Sync** your file to GitHub and apply a **Commit** that says, `Final edits done. Part 1 completed`

<br>

## Example Project
This is an example of what the project should look like before you move on to Part 2.

![Screenshot of template.html page](https://i.imgur.com/B3AVWYP.png)

<br>

## Part 2: Create a Poetry Page
For this part of your assignment, you will use the template you created in Part 1 to demonstrate when to properly use text-level semantic tags.

## Project Prep

1. Use your Internet researching skills to find a poem that has multiple stanzas. A stanza is a group of lines that forms a pattern of meter and rhyme - like a verse in a song.
2. Save the following information in a separate document, you may use this to reference later (you do not need to save this document or submit for grading):
    - The link to the webpage
    - The title of the web page
    - The title of the poem
    - The author's name
    - All text in the poem


## Create the Poetry Page

1. Open the **template.html** file.
2. Copy the template.html file and rename the copied file as `poetry.html`. The file should be in the same folder as the template.html folder.
0. **Update the metadata** on the page:
    - Update the page **title** to follow this format: `{FirstName}'s Poetry Page`.
        > **TIP:** Replace {FirstName} with your actual first name.
    - **Add a minimum of five (5) keywords** that would be appropriate for the page.
    - **Add a brief description** that appropriately describes the content on the poetry page that you will add below.
    - **Add a comment** after your metadata to explain which SEO best practice(/s) you applied when creating your keywords and description and how the metadata may help your page appear higher within search results.

0. **Update the header** element.
    - **Change the first-level heading** to read `Poetry Page`.
    - **Modify the navigation link** to point to the `template.html` page and change the **display text** to read: `Template`.

0. **Modify the main content**.
    - **Change the second-level heading** to the title of the poem.
    - **Change the paragraph text** to the author's name.
    - **Paste the text of the poem** you found in the Project Prep steps and use separate `paragraphs` for each stanza in the poem.
    - **Add a final paragraph** with the text: `Source - {Title of the web page}`
        > **TIP:** Use the actual title of the web page where you found the poem.
    - **Make the text small**.    
    - **Add a comment** after the final paragraph with the URL to the poem.

0. **Demonstrate text-level semantics** by making the following changes to your poem:
    - **Identify a sentence** (or two) in the poem that you find is important.
    - **Utilize an appropriate text-level semantic tag** around the text to change the significance of the sentence.
    - **Add a comment** next to the line that explains why you found the text important.
    - **Add a comment** near the slogan paragraph within the header. Compare the text-level semantic tag you added to the slogan paragraph with the poetry line you highlighted as important and explain why each tag is the most appropriate tag to use.

0. Within VS Code, correct any validation errors that may appear in your code. In the Course Introduction, you should have installed several extensions for VS Code that can be used to validate your code.  
    - You may ignore any warnings that may appear with your files. However, you are required to correct any and ***all*** validation **errors**.
0. **Save** the file. **Sync** the file to GitHub and apply a **Commit** that says, `Poetry page created`.


## Example Project
This is an example of what the project should look like before you submit it for grading.
![Screenshot of Template.html page](https://i.imgur.com/LFupMIC.png)

<br>

## Submit the Project
Once you have completed your project, you need to let your instructor know that it is ready to be graded. This is done by submitting the Repo URL to the assignment in RioLearn.

   > **TIP:** If you need a refresher on how to submit your work, view: [Submitting Assignments & Viewing Feedback](https://riosalado.coursearc.com/content/cis-public/git-github-and-vs-code/submitting-assignments-and-viewing-feedback).
1. Review your work and make any necessary updates. Save the file. You can either select **FILE>SAVE** or use the keyboard shortcut **CTRL+S**.
2. **Sync** the changes and apply a final **Commit** that says: `Completed final review and updates before submission.`
3. Verify that all files appear on GitHub.

   > **TIP:** You can view any of your repos by going to the GitHub organization for the course - [RSC-CIS133DA-IN-V12 Organization](https://github.com/rsc-cis133DA-in-v12). Once you are viewing the class organization, you should see all of the Repos that you have accepted assignment invitations for. It is recommended that you bookmark this page for future reference. Push (i.e., sync) the files on your computer with GitHub to ensure all files are uploaded to GitHub for your instructor to view.
4. Right-click the link to your repository and select **Copy Link Address**.
5. Go to the Assessing Your Learning page in your RioLearn lesson, and click the link to submit the assignment. Paste the link to your repo in the assignment submission box.
