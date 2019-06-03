# Rappo Theme
Rappo Corporate Template [original html5 theme](//themefisher.com/products/rappo-corporate-template/). 

![Hugo Rappo Theme screenshot](https://themefisher.com/wp-content/uploads/edd/2019/04/rappo-theme-thumb.jpg)

## Installation

Inside the folder of your Hugo site run:

    $ cd themes
    $ git clone https://github.com/fermarval/hugo-theme-rappo

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.

## Getting started

After installing the Rappo Theme successfully it requires a just a few more steps to get your site running.


### The config file

Take a look inside the [`exampleSite`](//github.com/fermarval/hugo-theme-rappo/tree/master/exampleSite) folder of this theme. You'll find a file called [`config.toml`](//github.com/fermarval/hugo-theme-rappo/blob/master/exampleSite/config.toml). To use it, copy the [`config.toml`](//github.comfermarval/hugo-theme-rappo/blob/master/exampleSite/config.toml) in the root folder of your Hugo site. Feel free to change the strings in this theme.

### Make the contact form working

Since this page will be static, you can use [formspree.io](//formspree.io/) as proxy to send the actual email. Each month, visitors can send you up to one thousand emails without incurring extra charges. Begin the setup by following the steps below:

1. Enter your email address under 'email' in the [`config.toml`](//github.com/fermarval/hugo-theme-rappo/blob/master/exampleSite/config.toml)
2. Enable form by setting `enable` to `true` in contact settings
3. Upload the generated site to your server
4. Send a dummy email yourself to confirm your account
5. Click the confirm link in the email from [formspree.io](//formspree.io/)
6. You're done. Happy mailing!

### Nearly finished

In order to see your site in action, run Hugo's built-in local server. 

    $ hugo server

Now enter [`localhost:1313`](http://localhost:1313/) in the address bar of your browser.


## Contributing

Did you find a bug or have an idea for a new feature? Feel free to use the [issue tracker](//github.com/fermarval/hugo-theme-rappo/issues) to let me know. Or make directly a [pull request](//github.com/fermarval/hugo-theme-rappo/pulls).

## License

This theme is released under The MIT License (MIT). For more information read the [License](//github.com/fermarval/hugo-theme-rappo/blob/master/LICENSE.md).

## Acknowledgements

Thanks to 

- [themefisher.com](//themefisher.com) for creating this theme
- [Steve Francia](//github.com/spf13) for creating Hugo and the awesome community around the project.
