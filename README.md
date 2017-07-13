# Fix for MiniCart dont reset on success page on Magento 2

__Installation__
 
  1. Create the directory (if it does not exist) that will hold the module contents
    `$ mkdir -p silici0/DefaultFix` on app/code directory

  2. Upload files to silici0/DefaultFix files

  3. Execute Magento setup upgrade

    $ bin/magento setup:upgrade

  4. Clean cache and generated code

    $ bin/magento cache:clean
    