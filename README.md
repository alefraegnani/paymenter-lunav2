# 由于正版是付费的，因此不直接放出源码，可自行在release中下载
# paymenter-lunav2
luna v2 theme for paymenter 1.4 or latter

Please follow this guide to install:
- Run `npm install @alpinejs/anchor --save` or 'yarn add @alpinejs/anchor' to install anchor
- Place the `theme` folder within the `/var/www/paymenter` folder, and "Merge" the folders/files together (important you DONT overwrite/replace/skip)
- Follow this guide to build assets & dependencies: https://paymenter.org/development/theme/assets (Make sure you run `npm run build luna`)
- Run `php artisan app:settings:change theme` and select `luna` or change theme in your admin panel

Paymenter Discord (better & quicker support) - Feel free to tag me in support requests @buzzthedev
https://discord.gg/MV3NqndsCy

If you require other support, please join our Discord and make a ticket:
https://discord.gg/buzz

If you have any suggestions, we'd love to hear them in our Discord too in the `#-luna` channel!

Guides:
- How do upload images to checkout options?
To upload images to checkout options, you simply need to drag and drop the image with the same name as the option into "public/config_options" folder. For example, for the Ubuntu option for "Operating System" option, you would upload "ubuntu.png"

安装步骤
- 运行`npm install @alpinejs/anchor --save` 或 'yarn add @alpinejs/anchor'安装依赖
- 将luna文件夹放置在paymenter/themes/目录下
- 使用`npm run build luna`或根据https://paymenter.org/development/theme/assets进行编译
- 使用`php artisan app:settings:change theme`并选择luna或者在admin面板更换主题
