# Laravel 5.5 demo: uploading videos to Amazon S3

![Larancer screenshot](https://laraveldaily.com/wp-content/uploads/2018/11/s3-videos-demo.png)

## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Don't forget to enter your Amazon credentials in __.env__ file - as AWS_KEY / AWS_SECRET / AWS_REGION / AWS_BUCKET
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL and login with default credentials __admin@admin.com__ - __password__

## Credits

- [Spatie Laravel MediaLibrary](https://github.com/spatie/laravel-medialibrary)
- [BlueIMP jQuery File Upload](https://blueimp.github.io/jQuery-File-Upload/)

## License

Basically, feel free to use and re-use any way you want.

---

## More from our LaravelDaily Team

- Read our [Daily Blog with Laravel Tutorials](https://laraveldaily.com)
- FREE E-book: [50 Laravel Quick Tips (and counting)](https://laraveldaily.com/free-e-book-40-laravel-quick-tips-and-counting/)
- Check out our adminpanel generator QuickAdminPanel: [Laravel version](https://quickadminpanel.com) and [Vue.js version](https://vue.quickadminpanel.com)
- Subscribe to our [YouTube channel Laravel Business](https://www.youtube.com/channel/UCTuplgOBi6tJIlesIboymGA)
- Enroll in our [Laravel Online Courses](https://laraveldaily.teachable.com/)
