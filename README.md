# RMedicine_website

This is Quarto-based and updates and supersedes the website [here:](https://events.linuxfoundation.org/r-medicine/)

## Contributing to this website

This website is being built live, bit-by-bit by members of the R/Medicine organizing committee and other volunteer contributors. The idea is to get information about the conference up as soon as it comes in. It is unlikely that the website will not be finalized until shortly before the conference. If you follow the progress of the website you will likely see information go up initially with modest formatting and little aesthetic charm. It is our hope that subsequent contributions will produce something worth saving for next year. This is an exercise in what the Japanese call ["Kaizen"](https://kaizen.com/what-is-kaizen/) or continuous improvement.

### The workflow for making contributions

#### 1. **Fork this website repository to your own github site**

on Github.com, navigate to the RMedicine website repo - <https://github.com/RConsortium/RMedicine_website/>

a\. In the top-right corner of the page, click **Fork**.

b\. Under "Owner," select the dropdown menu and click an owner for the forked repository.

By default, forks are named the same as their upstream repositories. Optionally, to further distinguish your fork, in the "Repository name" field, type a name.

Optionally, in the "Description" field, type a description of your fork.

c\. Unselect the box for **Copy the DEFAULT branch only**.

d\. Click the 'Create fork' button

#### **2. Now clone this forked repository to your own Github site**

a\. On GitHub.com, navigate to **your fork** of the RMedicine website repository

b\. Above the list of files, click **Code**.

c\. Copy the URL for the repository.

d\. Go to your local RStudio

e\. Select File/New Project/From Version Control/Select Git

f\. Paste in the URL, Open the Project

#### **3. Now configure your forked repo to sync with the upstream repo**

a\. Copy the https web URL for the upstream repository belonging to Rconsortium

b\. Go to your Rstudio, open the Terminal tab

c\. change your directory to reach the forked repo that you now own

-   To go to your home directory, type just `cd` with no other text.

-   To list the files and folders in your current directory, type `ls`.

-   To go into one of your listed directories, type `cd your_listed_directory`.

To go up one directory, type `cd ..`.

d\. type `git remote -v` and press **enter** - you will see the configured remote repository (on github) for your fork

e\. type `git remote add upstream` then paste in the URL to the Rconsortium upstream repo and press **enter**. It will look something like this:\`

```         
git remote add upstream https://github.com/RConsortium/RMedicine_website/
```

f\. to verify that you are connected, type `git remote -v` again. You should now see the origin and the upstream.

#### 3. Select the appropriate branch

Go to your local RStudio, and make sure you are in the RMedicine_website project. Clik on the Git tab in the top right pane. Underneath the Git tab, at top right, you will see a branch dropdown, which will start on tbe `operations` branch. Select a branch that is appropriate for your contribution.

You will see that there are branches that correspond to each page listed on the tab bar at the top of the website:

| Website Page    | Corresponding Branch |
|-----------------|----------------------|
| Home            | home                 |
| Register        | register             |
| Program         | program              |
| Code of Conduct | Code_of_Conduct      |
| Competition     | competition          |
| Contact us      | Contact_us           |
| Past Events     | Past_events          |

Do not work on or edit whie on the "operations" branch. This is the main branch that drives the GitHub Actions code that publishes the website at https://rconsortium.github.io/RMedicine_website/.

#### 4. Git Pull the Current State of the Branch

Do a pull request from your local copy to make sure branch is in sync with the website branch, just to be sure that you are on the current version.

#### 5. Edit, Write, Add Content

Create.

#### 6. Git Commit your changes

Make your changes locally save them and commit them. Be sure to make your commit message descriptive of the work you did.

#### 7. Open a pull request

a\. Go to **your** github.com website, and find your RMedicine_website repo.

b\. Select the branch you were working on in the branch menu ("switch branches").

c\. Above the list of files, in the yellow banner, click **Compare & pull request** to create a pull request for the associated branch.

d\. Use the *operations (base)* branch dropdown menu to select the branch you'd like to merge your changes into, then use the *compare* branch drop-down menu to choose the topic branch you made your changes in.

e\. Type a title and description for your pull request.

f\. To create a pull request that is ready for review, click **Create Pull Request**.

If your changes are accepted they will be merged by a website administrator

**Note**: to look at the website locally you can execute it in your **terminal**:

```         
quarto preview
```
