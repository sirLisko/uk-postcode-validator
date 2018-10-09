# uk-postcode-validator [![Build Status][travis-image]][travis-url]

> Validate UK postcodes.

## Installation

```bash
$ npm install uk-postcode-validator
```

## Example

```js
const isValid = require("uk-postcode-validator");

isValid("N7 7AJ");
//=> true

isValid("N7 A7J");
//=> false

isValid("90210");
//=> false
```

## API

### isValid(input)

Returns the `true` or `false` based on the postcode validity.

#### input

Type: `string`

## Inspired by

This [stack overflow discussion](https://stackoverflow.com/questions/164979/uk-postcode-regex-comprehensive) and [this gov.uk document](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/488478/Bulk_Data_Transfer_-_additional_validation_valid_from_12_November_2015.pdf).

[travis-image]: https://travis-ci.org/sirLisko/uk-postcode-validator.svg?branch=master
[travis-url]: https://travis-ci.org/sirLisko/uk-postcode-validator
