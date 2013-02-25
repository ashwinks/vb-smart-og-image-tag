vb-smart-og-image-tag
=====================

Smart OG Image Tag

Currently vBulletin's facebook open graph image tag uses what's entered in Options -> Facebook Options -> Image URL. If you leave this field blank, the <og:image> meta tag is omitted and Facebook's crawler will try to use any image found on the page. 

This mod looks for the first [img] or [attach] tags in a post and uses that image for the <og:image> meta tag. This will tell facebook's crawler to use that image for the post. 

This mod requires the Facebook Platform to be enabled on vBulletin (Options -> Facebook Options -> Enable Facebook Platform). 

It will first look for an [img] tag is the post, if none is found, it will look for an [attach] tag. If neither is found, it will use the Image you entered in the facebook options (Options -> Facebook Options -> Image URL). If that field was left empty, it will omit the <og:image> tag which is default vBulletin behavior. 

This was only tested on 4.2.0 (PL3).

Installation:
Admin -> Plugin & Products -> Manage Products -> Add/Import Product
