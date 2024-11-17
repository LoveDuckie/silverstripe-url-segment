<div align="center">

# SilverStripe URL Segment

**Automatically generate and inject slugs or URL segments to your DataObjects.**

</div>

Unlike `SiteTree` objects, other `DataObject`s in SilverStripe do not automatically produce a "`URLSegment`". Generating a "`URLSegment`" can be beneficial for navigation purposes on your website, or for search-engine optimization.

This is a simple module that provides a `DataExtension` that can be appended to any `DataObject` that you have in your project. It will ensure that `URLSegment` is populated with a unique name (non-colliding).

It has the added benefit of optimizing discovery with search engine crawlers by having identifiable names and titles attributed with indexed objects.

## License

See [License](LICENSE.md)

## Installation

```sh
composer require loveduckie/silverstripe-url-segment
```

## Documentation

- [Documentation readme](docs/en/README.md)
