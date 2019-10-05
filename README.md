# Not maintaned

# ng2-datetime
[![npm version](https://badge.fury.io/js/ng2-datetime.svg)](https://badge.fury.io/js/ng2-datetime)

Datetime picker (plugins wrapper) for Angular.

##### Demo and docs: https://nkalinov.github.io/ng2-datetime

## Dependencies
- [Bootstrap3 (__CSS only__)](http://getbootstrap.com/)
- [jQuery 2+ (supports v3)](http://jquery.com/)
- [Bootstrap-datepicker __(JS+CSS)__](http://eternicode.github.io/bootstrap-datepicker/)
- [Bootstrap-timepicker __(JS+CSS)__](http://jdewit.github.io/bootstrap-timepicker/)

## Installation
`npm install --save ng2-datetime`

## Usage
1. import some way or another the required dependencies in the following order:
   - Bootstrap CSS
   - jQuery
   - bootstrap-timepicker + bootstrap-datepicker
   
   See [this example](https://github.com/nkalinov/ng2-datetime/blob/master/src/vendor.ts#L8)
2. `import { NKDatetimeModule } from 'ng2-datetime/ng2-datetime';`
3. Add it to your app module's `imports` property
```
@NgModule({
    ...
    imports: [NKDatetimeModule, ...],
    ...
})
```
4. Use it: `<datetime [(ngModel)]="date"></datetime>`

See the [__DEMO__](https://nkalinov.github.io/ng2-datetime) and it [__source__](https://github.com/nkalinov/ng2-datetime/tree/master/demo) for more info and available options.

## Contributing
Fork > Create > Pull request

## Thanks to
- @jdewit for the [timepicker plugin](https://github.com/jdewit/bootstrap-timepicker)
- @eternicode for the [datepicker plugin](https://github.com/eternicode/bootstrap-datepicker)
- you
