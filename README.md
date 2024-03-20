# RMedicine_website

This is Quarto-based and updates and supersedes the website [here:](https://events.linuxfoundation.org/r-medicine/)

## Contributing to this website

This website is being built live, bit-by-bit by members of the R/Medicine organizing committee and other volunteer contributors. The idea is to get information about the conference up as soon as it comes in. It is unlikely that the website will not be finalized until shortly before the conference. If you follow the progress of the website you will likely see information go up initially with modest formatting and little aesthetic charm. It is our hope that subsequent contributions will produce something worth saving for next year. This is an exercise in what the Japanese call ["Kaizen"](https://kaizen.com/what-is-kaizen/) or continuous improvement.

### The workflow for making contributions

#### 1. Clone this website

#### 2. Select the appropriate branch

From your cloned (local) copy of the repository select a branch that is appropriate for your contribution. If you click on the pull-down branch button in the upper left hand corner of the first main [GitHub page](https://github.com/RConsortium/RMedicine_website) for this website you will see a number of branches.

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

Do not select the "operations" branch for anything. This is the main branch that drives the GitHub Actions code that publishes the website at https://rconsortium.github.io/RMedicine_website/.

#### 3. Do a Pull Request

Do a pull request from your local copy to make sure branch is in sync with the website branch

#### 4. Commit your changes

Make your changes locally save them and commit them. Be sure to make your commit message descriptive of the work you did.

#### 5. Open a pull request

If your changes are accepted they will be merged by a website administrator

Note: to look at the website locally you can execute it in your terminal:

```         
quarto preview
```
