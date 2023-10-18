# How to Write Projects on GitHub Using Markdown: A Beginner's Guide

## Introduction

For beginners looking to showcase their skills, GitHub serves as an invaluable platform to host a project portfolio. When I first started building my own Project Portfolio on GitHub, I faced many challenges and struggles. Now, I'm sharing what I've learned to help those who are also finding it difficult to get started with their portfolios on GitHub. Not only does GitHub allow for seamless collaboration on software development tasks, but it also offers an excellent way to document your projects comprehensively. One of the simplest tools to achieve this is Markdown. This lightweight markup language enables you to create well-formatted text documents without the need for specialized software. Its ease of use and straightforward syntax make it ideal for crafting READMEs, wikis, and other essential documentation that adds a professional touch to your GitHub projects.

## How I Learned Markdown and Found StackEdit

I initially got acquainted with Markdown through Logseq, a note-taking application that supports Markdown formatting. Logseq made it convenient to jot down thoughts, make lists, and even create headers—all in Markdown.
  - Logseq: Think of Logseq as a digital notebook where you can write down anything, from to-do lists to complex notes. The best part? It allows you to format these notes nicely using Markdown, which is a straightforward way to add headers, lists, or even links in your text.

Later, I came across another useful tool, StackEdit, while taking a course called "Data with Danny - Serious SQL" by Danny Ma. StackEdit is an in-browser Markdown editor that offers a range of features, making it easy to write and organize Markdown files. 
  - StackEdit: Imagine you're writing in Word, but this is specifically designed for Markdown. It's a website you can visit where you can write, format, and even see in real-time how your Markdown text will look. Plus, you can save your work and access it from anywhere since it's online. Click [here](https://stackedit.io/app#) to explore. Learn more with Markdown [Cheat Sheet](https://www.markdownguide.org/cheat-sheet/) and [Basic Syntax](https://www.markdownguide.org/basic-syntax/).

By blending the simplicity of Logseq with the advanced features of StackEdit, I've found a comfortable workflow for learning and using Markdown, especially in the context of GitHub projects.

Now let's proceed with creating a repository for a project.

## Steps to Writing a Project in Markdown on GitHub

### Step 1: Create a Repository
Creating a repository is your first step in setting up a new project on GitHub. It serves as a container where all files related to your project, including code, documentation, and other resources, are stored. Here's how to do it:

**Log into your GitHub account**: If you don't have one, you can sign up [here](https://github.com/).
As soon as you login to your account (and if you've just created an account), you'll be greeted with the dashboard (or your home screen) and it probably looks like this:
![image](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/015f374d-4f65-4ab5-aead-5e5d76e63be7)

My dashboard looks like this
![image](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/84b45958-105a-4338-ac9e-24d284bf1221)

There are few ways to create new repository. One way is, on the upper-right side of the screen, click on the green "Create repository" button to start the process of creating a new repository.
![image](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/1b66d4e4-78f2-41a4-8fc6-e3bf72da32db)

Another way is, on the top-left tabs pane you'll see the "+" with the down arrow (right next to the search bar)
![image](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/d6128b9c-b2f4-48ce-9760-b8d43197fc60)

and click on it. This will pop up and click on "New repository".

![image](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/9d7b6801-1aea-469f-95b5-89fff120ca1d)

The last option is, on the top-left most you'll see your account button and if you click on it, this pop-up will show:

![image](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/77af0a5a-623b-4391-a577-e848ce56b6a8)

Click on "Your repositories" and this page shows up:
![image](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/95b9a5ad-8956-4828-b6e2-99ecea0c5faa)

And click ont the "New" green button.

Whichever way you do it, you will be directed to this page:
![image](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/f0c7114f-ea7a-4491-adcf-c9d2e4cf6d1c)

**Fill in Repository Details**:

***Repository Name***: Choose a relevant name for your project. Choosing a good repository name is crucial for making your project easily discoverable and understandable.

![Screenshot 2023-10-17 at 6 11 09 pm](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/35a0e97d-ef7d-479a-9248-697943aa1b05)

***Description (Optional)***: Add a brief description for better understanding.

***Visibility***: Choose between public and private visibility.

![Screenshot 2023-10-17 at 6 11 24 pm](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/f95908fc-42ca-4c94-89c5-44749c6dc820)

Make sure you click on "Public", as this will be your project portfolio, it will be easily accessible for anyone, or everyone can see your projects.

***Initialize with README***: Check the box to initialize your repository with a README file. This step is crucial when you're setting up a new repository.

![Screenshot 2023-10-17 at 6 12 05 pm](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/e47836f5-05db-4c54-8755-d48ebbd17533)

***Create Repository***: Click the green "Create repository" button to finalize the process (it's blue button on my account).

### Step 2: Clone the Repository (Optional)
You can clone the repository to your local machine if you prefer to work offline. This step is optional. If you're always online, you can skip it. But if you'd like to work offline, follow this step. Open your terminal and run:

```bash
git clone [URL_of_your_repository]
```

### Step 3: Open README.md
As soon the click on the "Create repository" button. it will immediately redirect you to the repository page and it will look like this:
![image](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/db857eb5-de28-499b-a892-454c4b562f16)

Navigate to the repository and open the README.md file in a text editor by clicking on the "Pen" symbol on the left side of the READme.md. You'll see it's a blank canvas, ready for Markdown formatting.
![image](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/51d18bd5-04e8-4d6e-936a-4df51e39856a)

### Step 4: Start Writing in Markdown
Here are some basic Markdown syntax you can use:

#### Headers: 
Use # for a top-level header, ## for a second-level header, and so on.
```markdown
# Header 1
## Header 2
```
It will show like this:
# Header 1
## Header 2

#### Lists: 
Use `-` or `*` for bullet points and `1.` for numbered lists.
```markdown
- Item 1
- Item 2
```
It will show like this:
- Item 1
- Item 2
  
#### Links: Use `[text](URL)` to create a hyperlink.
```markdown
[Visit GitHub](https://github.com)
```

#### Images: 
Use `![alt text](image_URL)` to insert an image.
```markdown
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```
Or you can copy-paste the location or URL of the image. What I usually do is, take a screenshot and copy the URL of the image and paste it straight onto here.

#### Code: 
Use backticks to surround inline code and triple backticks for blocks of code, for SQL, Python, Excel.
![image](https://github.com/jef-fortunahamid/Github-and-Markdown-Beginners-Guide/assets/125134025/39ca78f1-7a4f-4a1f-a9cd-e84e691f58c2)

It will show up like this:
```sql
-- Fetch details of total sales from each customer
SELECT
    c.customer_id
  , c.name
  , ROUND(SUM(s.total_amount), 2) AS total_amount_purchase
FROM sales s 
  JOIN customer c
    ON s.customer_id = c.customer_id
GROUP BY
    c.customer_id
  , c.name
;
```
With your code (after the triple backticks), you need to specify what type of code you are using, like SQL, Python or Text for Excel equations, to make it colourful, as you can see from the example above.

For inline code, I use this to hightlight table and column names, functions and formulas. For example:
```markdown
`RANK()`
```
it will show up like this:
`RANK()`

### Step 5: Save Changes
After editing the README.md file, save it. If you're working locally, push the changes back to GitHub.

```bash
git add README.md
git commit -m "Updated README"
git push origin master
```
### Step 6: Review on GitHub
Go back to your GitHub repository and refresh the page. You should see the beautifully formatted README.md file.

## Conclusion

For those just starting out, GitHub is an incredible resource for showcasing your skills through a project portfolio. With the help of Markdown, you can easily document your projects, making them more accessible and professional. Whether you are developing software or simply want to display your work, GitHub and Markdown are tools that can help you achieve your goals.
