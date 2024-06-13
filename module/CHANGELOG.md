# Change log

## [4.2.1] - 2024.06.11:
### Fixed
- Ignore the module status if SEO URLs disable in the store settings.

## [4.2.0] - 2024.06.10:
### Added
- Ability to display language tag in URL even for one language.
### Fixed
- Removed brand tags from direct product SEO URLs.
- Error when multiple languages ​​are installed but only one is enabled.
- Static pagination for only numerical SEO URLs.
### Internal
- Admin view slightly changed.
- Minor code improvement.

## [4.1.2] - 2024.03.18:
### Fixed
- Processing an erroneous request.

## [4.1.1] - 2023.09.28:
### Internal
- Fix compatibility with the **SEO Redirect** module.

## [4.1.0] - 2023.09.01:
### Changed
- Determining correct URL language for further redirection if necessary.
### Fixed
- Adding of keywords for geeral SEO URLs (account/login, checkout/cart, etc.)
### Internal
- Code restyling and improvements.
- Part of OCMOD code moved to events.

## [4.0.1] - 2021.06.25:
### Added
- Hide module from the modules list on "Design > Layouts".
### Fixed
- Removed redundant event.

## [4.0.0] - 2021.06.24:
### Changed
- Renamed to "SEO Path" and merged with "SEO Path - Breadcrumbs".
### Added
- Caching of SQL-queries.
### Internal
- Code improvements.

## [3.3.1] - 2021.05.24:
### Fixed
- Empty $this->request->get['_route_'].

## [3.3.0] - 2021.05.20:
### Changed
- Use numerical static pagination (example.com/cat/2).
### Internal
- Changed variables in settings.

## [3.2.0] - 2021.05.19:
### Fixed
- Product SEO links generation for non-direct path.

## [3.1.0] - 2021.05.18:
### Fixed
- Category redirection.

## [3.0.0] - 2021.04.04:
### Changed
- Renamed to SEO Path - Links.
- Link generation method.
- Merged settings of category path and category canonical.
### Added
- SEO pagination (/page-n instead of ?page-n).
- Page number on paginated pages title and in description.
- All category links redirect to path type defined in the module.

## [2.2.0] - 2021.03.11:
### Fixed
- Pagination links in header.

## [2.1.0] - 2021.02.26:
### Fixed
- Minor issues in unexpected cases.
### Internal
- Renamed some events and functions.

## [2.0.1] - 2021.02.23:
### Fixed
- Skip products without id (e.g in orders).

## [2.0.0] - 2020.04.14:
### Changed
- Module renamed to "SEO Path - Links".
- Code refactored to compatibility with the "SEO Path - Breadcrumbs" module.

## [1.0.0] - 2019.12.11:
- First release.
