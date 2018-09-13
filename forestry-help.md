---

---
## Creating new articles with Forestry

1. Go to the `For review` section of the sidebar.
2. Click `Add new` on the top of the screen.
3. Choose a Front Matter Template. In most cases, the **basic template** works perfectly.
4. Add some content to the editor on the right, and click `Save draft`.

You can come back and edit the article any time. Please remember that every time you click `Save`, Forestry pushes a commit to GitHub. You can view your file in the DevCenter repository.

{% include message_box.html type="important" title="GitHub commits" content="Please make sure when your article is ready for review that a single commit on GitHub will make all changes visible. With a new article, that means you should:

1. Cut its entire content (keep it on the clipboard!) and then click Save draft. 
2. Once it is saved (the little circle is green), paste the content back in and click Save draft. "%} 

**ALTERNATIVE OPTION**: Edit your article on Forestry as much as you want. Once you are done:

1. Cut the entire content (keep it on the clipboard).
2. Save the empty article.
3. Paste the content back, and save again.

This way you will have a commit that will show the entire content of the article as new content. Voilá!

## Updating an existing article

1. Create a new article in the `For review` section.
2. Copy the contents of the existing article into the new article.
3. Add your changes.

NOTE: Once again, it is recommended to edit the existing article in an external editor until it is ready for review. Once you are finished (the article is ready for review), copy the contents into the new article you created in the `For reviews` section. This is to ensure all changes are visible in a single commit.

See the alternative option above!

## Getting an article reviewed

1. Save the article on Forestry - this creates a commit on GitHub so only save on Forestry when your content is ready for review.
2. Go to the [commits page of the DevCenter repository](https://github.com/bitrise-io/devcenter/commits/master) and find the commit or commits created when you saved the article. Its commit message should be "Updated article-name.md" or "Created article-name.md".

NOTE: if you have several articles ready for review, you will find each article in a separate commit.

1. Select and copy the links of the commits in your browser's address bar and add them to the review task(s) in ClickUp.
2. Move your writing tasks to _Blocked_ status.