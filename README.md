# HCM Study Lab

A self-contained Workday HCM study app, ready for GitHub Pages.

## Files

| File | Purpose |
| --- | --- |
| index.html | Complete app, including its questions, lessons, flashcards, styles, and scripts. |
| .nojekyll | Publishes the static files without Jekyll processing. |
| README.md | These setup instructions. |

No installation, build command, database, or API key is required.

## Put the app on GitHub

1. Extract **HCM_Study_Lab_GitHub_Pages.zip** on your computer.
2. Create a new GitHub repository. A suggested name is **hcm-study-lab**. Use a public repository if you use GitHub Free.
3. On the repository's Code page, use the upload-files option. For an empty repository, use the link to upload existing files.
4. Upload the extracted files directly into the repository's top level. The app must be named **index.html**, in lowercase. Do not upload the ZIP itself or place the files inside an extra enclosing folder.
5. Commit the uploaded files to the **main** branch.
6. In repository settings, open Pages. Choose branch-based publishing, select **main**, select the root folder, and save.
7. Once deployment completes, use the site link shown in Pages settings.

The repository's top level should contain the three files listed above. If your file picker hides **.nojekyll**, enable hidden-file display when selecting files.

## What is included

- 340 questions: 300 weighted core questions, 20 foundation questions, and 20 clearly marked original sample questions.
- 21 topic lessons and 340 flashcards.
- Immediate correctness feedback and explanations in learning practice.
- Six 50-question core practice sets, random weighted exams, sample exams, and custom exams.
- Timed exams with results after submission.
- Persistent mistake history, recovered-mistake markers, saved questions, and exam history.
- Searchable concept references and Workday documentation links.
- Progress export and import.

The supplied sample marked 15 answers confirmed and 5 inferred. Those distinctions and wording caveats are retained in the app. This is independent study material, not an official Workday exam.

## Using and updating the app

You can also open **index.html** directly in a browser. Its embedded lessons and questions work without internet access. External Workday reference links need internet access and may require sign-in.

Progress is saved in the browser. Before moving from a downloaded copy to the hosted site, use **Back up progress** in the old copy. In the new site, open **Your progress**, choose **Import progress**, and select that backup. Do the same when changing devices or browsers.

To update the app later, replace the repository's **index.html** and commit the change. Keep the same filename. GitHub Pages republishes changes from the configured source.

This package opens the HCM app itself as the site's homepage. The separate certification-app launcher from the earlier conversation is not needed for this new standalone site.

## If the page does not open

- Confirm **index.html** is at the top level of the selected publishing folder.
- Confirm Pages settings use the branch containing your uploaded files and the root folder.
- Check the repository's Actions page if deployment reports an error.
- If an old version appears, reload the browser after deployment finishes.

## Official GitHub instructions

- [Create a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [Configure the publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

Instructions checked on November 2, 2026.
