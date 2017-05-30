#Zooka Flexbox Framework

### Details
Author: Travis Amaral  
Version: 1.0

## Set up ##

Navigate into your project src directory (where SCSS should go). Git clone or download into directory.
```
git clone https://github.com/travispamaral/flexbox-grid .
```

Remove `index.html`  
Remove `scss/pages/_home.scss`  

## Usage ##
### Standard Auto Grid ###
```
<div class="container"> <!-- Creates parent wrapper with max width and margin -->
  <div class="row">
    <div class="col"> <!-- Column will automatically flex to equal width -->
      Your content
    </div>
    <div class="col"> <!-- Column will automatically flex to equal width -->
      Your content
    </div>
  </div>
</div>
```
### Column Specific Grid ###
```
<div class="container"> <!-- Creates parent wrapper with max width and margin -->
  <div class="row">
    <div class="col"> <!-- Auto width -->
      Your content
    </div>
    <div class="col col-md-6 col-lg-3"> <!-- Column will be 50% on medium and 33% on large+ -->
      Your content
    </div>
  </div>
</div>
```
