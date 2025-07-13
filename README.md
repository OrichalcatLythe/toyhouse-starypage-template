# toyhouse-starypage-template

# Toyhouse Starypage Template by OrichalcatLythe!
A custom userpage template code to be used in the website toyhou.se, including variations with and without custom css code.

Usage of version with css version (glow on hover over link, etc)
1) Copy&Paste the contents of userpage_with_css.html to your text editor, front-end editor or directly to toyhou.se page code editor. (MAKE SURE TO DISABLE WYSIWYG before copying it into your userpage code's editor)
2) Edit the values to your needs (eg. replace USERNAME with your actual username or use @@YOUR_USERNAME for an username with link, text below about me to what you want, basic html editing/code editing knowledge should be enough for this)
3) Once done with everything save the pagecode in toyhou.se page code editor. (MAKE SURE TO DISABLE WYSIWYG before copying it into your userpage code's editor) , it should be in settings/Profile Content! (But you can also use this direct link: https://toyhou.se/~account/profile )
4) Copy&Paste userpage.css ' contents to Settings/Profile CSS & Blurbs/Profile CSS (Direct link to Settings/Profile CSS & Blurbs if you need it : https://toyhou.se/~account/profile/advanced )

Usage of version **WITHOUT** css version (no special effects, glow on link hover, etc)
1) Copy&Paste the contents of userpage_without_css.html to your text editor, front-end editor or directly to toyhou.se page code editor. (MAKE SURE TO DISABLE WYSIWYG before copying it into your userpage code's editor)
2) Edit the values to your needs (eg. replace USERNAME with your actual username or use @@YOUR_USERNAME for an username with link, text below about me to what you want, basic html editing/code editing knowledge should be enough for this)
3) Once done with everything save the pagecode in toyhou.se page code editor. (MAKE SURE TO DISABLE WYSIWYG before copying it into your userpage code's editor) , it should be in settings/Profile Content! (But you can also use this direct link: https://toyhou.se/~account/profile )

Some tips for code editing for TH, it has some markups which you can use, to link usernames without a full html a tag you can just include @@TARGET_USER to have their link in the code fully formatted! Same  goes with characters but for them you need to include their numerical id (eg. @@33994934 , a character's numerical ID should be in their link as you enter their page, like for Placeholder Bob it's right after toyhou.se/ (eg. toyhou.se/33994934.placeholder-bob ) make sure to only include the numbers after @@ !
This also can create confusion eg. if you include a youtube link to https&#58;//www.youtube.com/@OrichalcatLythe the link will be malformed cause TH will automatically try to parse @OrichalcatLythe to a TH userpage link, you can fix this by using a html escape character! (Eg. https&#58;//www.youtube.com/&#64;OrichalcatLythe ) , using the escape character \&#64; will put a @ in the code while preventing toyhou.se's markup to convert it into a TH userlink.
