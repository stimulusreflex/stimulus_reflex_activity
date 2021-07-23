
# StimulusReflex Activity Indicator

Uses the Turbo(links) progress bar to display activity while morphing.



https://user-images.githubusercontent.com/4352208/126767394-e0fcefb5-3ac4-484e-bec2-c585e8f5bbc7.mp4




## Installation

Install my-project with npm

```bash
$ yarn add @stimulusreflex/activity  
```

In your (for example) `app/javascripts/packs/application.js` do:
```javascript
import "@stimulusreflex/activity"
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

  
