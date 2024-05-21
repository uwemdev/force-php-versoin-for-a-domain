# force-php-versoin-for-a-domain
To set a PHP version other than the one assigned to your domain on your cPanel account, you need to add a special code to your .htaccess file. The .htaccess file is a hidden file which is read by the web server.


    Log in to your control panel. You can do this by reading this article.
    Navigate to the section Files -> File Manager. If you wish to edit the .htaccess file for your addon domain, find the .htaccess for the addon domain in question, and go to the public_html/youraddondomain.com folder.
    Once in the File Manager, You can check if hidden files are enabled in Settings ( upper right corner )
    To set a custom PHP version for your desired directory/addon domain, either select the .htaccess file and click on Edit from the toolbar, or click the file to create a new .htaccess file if it does not exist.
    Once you are inside the .htaccess file, enter the PHP handler for the version you wish to use. If there is already a handler in the file, it should be deleted or replaced with your new handler. Depending on the desired PHP version you want to use for your specific application, modify the SetHandler line in the code.

