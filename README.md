# Mastodon share button

## Setup using Beautiful Jekyll
Copy _includes/social-share.html to your _includes directory.

Copy assets/js/mastodon.js to your assets/js directory.

To enable the Mastodon share button, you need to add some code in _config.tml. In the "General Options" section, you need to add a share-links-active entry for mastodon.

## Set a default Mastodon instance in the modal's msb-address text field
In social-share.html, on line 34, you can set a default instance address by editing the value.

## Customize the message included in your post that comes before the URI
In social-share.html, on line 17, you can customize the message included in your post that comes before the URI by adding a value for "data-name".

## Cookie information
In social-share.html, on line 37, there is a checkbox that you can check to remember your instance's address. If you check the checkbox, in mastodon.js, on line 38, it creates a cookie. The cookie appears to be valid for 7 days.
