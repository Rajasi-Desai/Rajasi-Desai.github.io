---
title: "PaperPal"
excerpt: "PaperPal is a research paper recommendation tool which recommends you research papers based on saved papers.<br/><img src='/images/projects/PaperPal/PaperPal.png'>"
collection: projects
---

<!-- TODO Challenges, scope contribution, pictures/screenshots-->

![PaperPal Logo](/images/projects/PaperPal/PaperPal.png)

An easy way to find research papers using references, authors, or topic via a recommendation and filtering system.

## App info

We built a chrome extension which can add research papers to folders, delete papers, view some limited details about the paper (like Author name, title, and publication year). If we click on the PaperPal icon from the extension, it opens a new window to the website. The website is an expanded view which has a similar look as the extension but with many more features like: 

1. Generating recommendations based on saved papers
2. Expand each paper to view things like Title, Authors, Keywords, Abstract, No. of references, and No. of citations
3. Multiple filtering capabilities like Search, hide / show certain columns, change column width, and shift columns
4. Sorting papers based on ascending order, and descending order
5. Insights button which gives us more information on why a particular paper was recommended

### Why is this a problem

- Difficult to visit all references
- Difficult to keep track of read papers
- Difficult to find papers on similar expertise level
- Time consuming
- A LOT of researchers face this problem

## Frontend

The frontend was built using React - JSX, JavaScript, HTML, CSS

## Backend

The backend was built in Python. We used BERT and OpenAI embeddings to generate recommendations

## Youtube Video

This project was made as part of CS 625: Advance HCI. You can checkout the YouTube video with a demo here: [Youtube Link](https://www.youtube.com/watch?v=o-lv_oNOpko)

## User Interface: 

The following are the UI views of our application and a brief decription of them:

### Chrome Extension
Chrome Extension for ease of access.

![Chrome Extension](/images/projects/PaperPal/PaperPal_chrome_ext.png "Chrome Extension")

### Add paper
Used to add papers directly to the app. 

![Add paper](/images/projects/PaperPal/PaperPal_add_paper.png "Add paper in the chrome extension")

### Remove paper
Detailed information of the paper in the chrome extension and deleting paper

![Detailed info and Trash](/images/projects/PaperPal/PaperPal_details_trash.png "Detailed info and Trash")

### Website
Cleaner display of the papers and more information

![Website](/images/projects/PaperPal/PaperPal_website.png "Website")

### Generate Recommendations 
Generate recommedations based on existing papers in the folder

![Generate recommendations](/images/projects/PaperPal/PaperPal_generate_rec.png "Generate recommendations")