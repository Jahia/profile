# profile Changelog

## 0.0.1

* Hardened the user profile component so every profile field it displays is shown as the text it contains, and so the link to edit your own profile is encoded consistently.

  The About me field is now shown as plain text. Its words are kept, and anything the rich-text editor applied to them is not: bold, italics and links are dropped, and separate paragraphs, line breaks and list items run together into a single block of text.

* Changed the Twitter link on user profiles to open x.com directly, without a redirect through twitter.com.
