# WordPress API Plugin Boilerplate

A OOP plugin template for API plugins

Originally built from Tom McFarlin's [OOP plugin template](https://github.com/DevinVinson/WordPress-Plugin-Boilerplate).

## Getting Started

This plugin features a gulp file to process & minify your Sass & JavaScript. In your console, run:

```
npm install
```
After the various dependancies have loaded, you can activate gulp:
```
gulp
```
Gulp will now be watching for any changes to you Sass or JavaScript files and will automatically update them as required.

###Prerequisites

You need to be able to access the files and folder structure of your WordPress site.

### Installing

1. Upload this plugin to your plugin folder.
2. Navigate to the plugins area of your WordPress Admin & *activate* the plugin

## Deployment

Once the plugin is activated, 2 new endpoints will appear by default:

`<your domain>/wp-json/example/v1/first-example`
`<your domain>/wp-json/example/v1/second-example`

Each contains a confirmation message.

You'll also see a new options page with an example field:

*Settings > API Boilerplate*
## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. 

## Authors

* [**Sean Blakeley**](http://www.seanblakeley.co.uk) - *Initial work*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details
