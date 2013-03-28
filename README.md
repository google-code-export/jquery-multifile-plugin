#[jQuery Multiple File Upload](http://www.fyneworks.com/jquery/multiple-file-upload/)

##Overview
This jQuery Multiple File Upload Plugin ($.MultiFile) is a non-obstrusive plugin for jQuery that helps users easily select multiple files for upload quickly and easily on your server whilst also providing some basic validation functionality to help developers idenfity simple errors, without having to submit the form (ie.: upload files).

---
 
##Installation
* Current version: 1.48
* Release date: 2013-02-19
* Download: <a href="http://jquery-multifile-plugin.googlecode.com/svn/trunk/multiple-file-upload.zip"><strong>multiple-file-upload.zip</strong></a>

---
 
##Basic Usage

Just add the `class="multi"` to your file input element:
```html
<input type="file" class="multi"/>
```

Use the `maxlength` property if you want to limit the number of files selected.
<b style="color:red">Server-side validation is always required</b>
```html
<input type="file" class="multi" maxlength="2"/>
```

Use the `accept` if you only want files of a certain extension to be selected Separate valid extensions with a "|", like this: "jpg|gif|png".
<b style="color:red">Server-side validation is always required</b>.
```html
<input type="file" class="multi" accept="gif|jpg"/>
```
