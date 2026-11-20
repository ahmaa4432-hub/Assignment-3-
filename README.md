# This is the repository for your writing assignments.


# Check (and enable) GitHub Pages

GitHub Pages should already be enabled for your repository. Use these steps to confirm and to enable it if it isn't.

1. Navigate to your repository.
2. Click the **Settings** tab.
3. Click **Pages** in the left sidebar.
4. In the **Build and deployment** section, check that:
   - **Source** is set to **Deploy from a branch**, and
   - **Branch** is set to **main**, with the folder dropdown beside it on **/ (root)**.

**If those are already set** and you see a message near the top like *"Your site is live at …"* , you're all set. No changes needed.

**If they are not set** (for example, the Branch dropdown shows **None**), enable Pages now:

1. Set **Source** to **Deploy from a branch**.
2. Choose **main** from the **Branch** dropdown.
3. Set the folder dropdown to **/ (root)**.
4. Click **Save**. After you click Save, it can take a minute or two for the site to go live. Refresh the page to see your live URL appear.

* Every time you edit `index.html` and commit the changes, the deployment flow will run.
* This flow will probably take less than a minute.
* Once the deployment flow has finished running for the first time, you will be able to view `index.html` as a website hosted at `https://luiza-s-classes.github.io/[repository-name]`.


# Edit and save your HTML files.

In this lab you'll add a sentence about yourself and a picture to your about.html page. You don't need to know HTML, just follow the steps and copy the examples, replacing the parts in your own words.

One thing to know first: everything a visitor sees on the webpage you are creating goes between the two tags `<body>` and `</body>`. When these steps say "inside the body," that's the spot between those two tags. Your file already has them.

## Part 1 — Add a sentence about yourself
1. **Find the file.** Navigate to about.html and click on it.
2. **Open the editor.** Click the pencil icon (Edit this file) in the upper-right corner of the file view.
3. **Find the body.** In the editing box, look for the line `<body>` and the line `</body>` further down. You'll add your sentence between them. Add your sentence. On a new line inside the body, type a sentence wrapped in `<p>` and `</p>` tags (these mark a paragraph). For example: ``` <p>Hi, I'm a first-year student who loves rock climbing and video games.</p>``` Replace the text with your own. Keep the `<p>` at the start and `</p>` at the end.
4. **Write a commit message.** Scroll down to the Commit changes box and type a short note, e.g., "Add a sentence about myself".
5. **Save your work.** Click the green **Commit changes** button to save your updates to the main branch.

## Part 2 — Add a picture
A picture lives in a separate file, so this takes two steps: first upload the image into your repository, then tell the page to show it.

### Step A — Upload your image
1. **Get your image ready.** Use a .jpg or .png file. Rename it to something simple with no spaces, for example myphoto.jpg.
2. **Go to the right folder.** Open the same folder that contains your about.html file.
3. **Start an upload.** Click the Add file button (top-right of the file list) and choose Upload files.
4. **Add the image.** Drag your image into the box, or click choose your files and select it.
5. **Commit.** Scroll down, type a message like "Add profile picture", and click Commit changes.

### Step B — Show the picture on your page
1. **Find the file and open the editor.** Open about.html again with the pencil icon.
2. **Add the picture.** Inside the body, where you want the picture to appear, add this line: `<img src="myphoto.jpg" alt="A photo of me" width="300">`, **src** is the file name of your image, it must match exactly, including capital letters and the .jpg/.png ending. **alt** is a short description of the picture (shown if the image can't load). **width="300"** keeps the picture a reasonable size. You can change the size.
3. **Commit.** Add a message like "Show profile picture on About page" and click Commit changes.


# HTML
* [learnxinyminutes.com](https://learnxinyminutes.com/html/) provides a highly succinct introduction to HTML syntax.
