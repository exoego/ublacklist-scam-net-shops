# How to contribute

If you want to add a domain, add the new line(s) to the end of `source.txt` without sorting lines.
 
Do not directly edit `uBlacklist.txt`.
GitHub Actions will sort the file automatically when PRs get merged.

## How to determine whether to accept

We use the following criteria to determine if we should add a new domain to the exclusion list.

- The page shown in search results redirects to another domain.
- The domain and shop name are too unrelated.
- The domain appeared to be a net shop / e-commerce, selling products at an unlikely low price.
- They appeared to be plagiarizing another website's contents, on description of products, user reviews, etc.
- Names of users in their user reviews are not natural.


## Japanese-contents only?

Though this exclusion list is initially created for Japanese websites,
domains in other languages are also welcome.

## "I do not think this domain should be excluded"

We may exclude a new domain regardless it consists of other useful contents.
Since uBlacklist offers "allow-list" mechanism, users can allow some domains to be displayed regardless of exclusion lists.
