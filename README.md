
# StimulusReflex Activity Indicator

Uses the Turbo(links) progress bar to display activity while morphing.




## Installation

Install my-project with npm

```bash
$ yarn add @stimulus_reflex/activity  
```

In your `app/javascripts/packs/application.js` do:
```javascript
import "@stimulus_reflex/activity"
```    

## Usage/Examples

The progress indicator is opt-in on a per-element basis. To activate it, add `data-reflex-display-progress` to your reflex element's dataset:

```html
<button data-reflex="click->Filter#filter" data-reflex-display-progress />
```
  
## Authors

- [@julianrubisch](https://www.github.com/julianrubisch)

  
## License

[MIT](https://choosealicense.com/licenses/mit/)

  
