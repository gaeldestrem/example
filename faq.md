# F.A.Q

This page gathers common questions and answers concerning GitBook.com.

Questions about Markdown and the GitBook format are gather into the [Toolchain's FAQ](http://toolchain.gitbook.com/faq.html).

## My book is not being updated / I can't see any updates

If you linked your book to a GitHub repository but editing content doesn't trigger any content update, Verify that the webhook has been correctly added to your GitHub repository \(in your GitHub repository's settings -&gt; Webhook\). If the webhook is not present or invalid, add it back from your book's settings.

If you **changed the book's name or its owner's name** \(it happens when transferring your book to a new owner\), the webhook is now invalid, you need to add it back.

## Can I limit the GitHub integration to one specific branch?

Books on GitBook.com can be configured to accept content from only whitelisted branches.

## Can I give read-only access to a private book?

Yes, [read-only collaborators](books/access.md#collaborators) can be added to books, or you can use [Access Keys](books/access.md#keys) to grant read access programmatically.

## Duplicate account

When you register with a Social \(Facebook, Twitter, GitHub or Google\), then register again using the form, it creates two distinct accounts \(one associated with your email, and another with your Social Account\).

You need to remove one of these account, to do so:

1. Logout from the account associated with your email
2. Login back using the social account
3. Delete this account at [www.gitbook.com/settings](https://www.gitbook.com/settings)
4. Login back using your email
5. Associate the Social Account to your email account at [www.gitbook.com/settings](https://www.gitbook.com/settings)

## An user is already associated to this GitHub account

See [Duplicate account](faq.md#duplicate-account).

