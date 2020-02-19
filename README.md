# ember-bootstrap-bs-form-performance

This project uses a blank Ember 3.16 and ember-bootstrap 3.1.1 with a page that renders 1, 10, 25, 100 <BsForm> elements.

The numbers I'm getting on **first time render** with Chrome on production build (`ember s` will be slower!):

- 1 element ~20ms
- 10 elements - ~50ms
- 25 element - ~100ms
- 100 elements - ~300-350ms

## Install

* `git clone git@github.com:aalimovs/ember-bootstrap-bs-form-performance.git`
* `cd ember-bootstrap-bs-form-performance`
* `npm install`
* `ember serve`
* Visit [http://localhost:4200](http://localhost:4200).