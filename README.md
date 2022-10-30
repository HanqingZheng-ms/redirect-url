A Pull Request has been made from the Learn Platform’s Metadata Management System. Please review and merge this Pull Request within 5 days. If you have any questions or concerns about the purpose of these metadata updates, please contact {0}. If you are not the correct contact for this content and repository, please notify {1}         
If this Pull Request is not merged within 14 days, it will be automatically merged by our system to ensure the timeliness of the metadata update. This includes bypassing the Repository’s Branch Policy, including if Review Required is enabled. Please notify {1} if you have questions or concerns or would like Pull Requests for metadata updates to merge automatically in future.

Fixing[#{2} {3}]({4})

**Why we make metadata updates**

It’s important that metadata is appropriately managed to ensure its ongoing relevancy, usefulness, and reflects the current business. For example, metadata is updated to reflect a product rebrand. Because some metadata values (slugs) are included in the YAML header, metadata updates require changes to the content itself.

For metadata used internally, these updates make reports cleaner, easier to use, more consistent, and more reflective of current business. Once changes to allowlist-driven metadata are merged, standard dashboards and reports will reflect new values. You’ll need to use new filter values in those dashboards and reports. If you have custom dashboards or Kusto queries, you might need to update those as well.

For customer-facing metadata, these updates ensure our customers are seeing the most up-to-date metadata on Learn content that matches what they see elsewhere in the Microsoft universe.

**Why we make header/navigation updates**

Header changes and other site navigation updates are crucial for improving content findability and are made in support of the navigation model strategy driven by the Learn Information Architecture and Content Architecture teams.

After you accept the header/navigation changes, you may now see a new or different product-level header used on content in your repo, revised breadcrumbs, or other navigation-related changes, which will be specified in the commit message.

**Frequently Asked Questions**

*Why does this Pull Request appear to be made by the Repository Owner?* We open Pull Requests two different ways.

- For Git Repos with a permissioned Service Account, we open the PR from our Document Build Service Account.
- For Git Repos that we either do not have Service Account permission for or the repo is in Azure Repos (ADO)  we open the Pull Requests in an automated way with the PR creator as the Repo owner. 
- 
*How can I revert a Pull Request that has been merged and created an unexpected issue?* Whether a PR has been merged manually or automatically, you can revert it if an issue arises. See [Reverting a pull request - GitHub Docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/reverting-a-pull-request).
