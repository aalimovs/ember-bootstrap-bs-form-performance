# ember-bootstrap-bs-form-performance

This project uses a blank Ember 3.16 and ember-bootstrap 3.1.1 with a page that renders 1, 10, 25, 100 <BsForm> elements.

Initial render performance after clicking the `Show` button with Ember Inspector 3.13.1:

- 1 element ~30ms
- 10 elements - ~100ms
- 25 element - ~210ms
- 100 elements - ~800ms

## Install

* `git clone git@github.com:aalimovs/ember-bootstrap-bs-form-performance.git`
* `cd ember-bootstrap-bs-form-performance`
* `npm install`
* `ember serve`
* Visit [http://localhost:4200](http://localhost:4200).