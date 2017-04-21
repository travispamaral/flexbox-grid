# README #

### What is this repository for? ###

* Simple CSS Flexbox Grid
* Version 1.0

### How do I get set up? ###

```
git clone https://travisamaral@bitbucket.org/travisamaral/flex-grid-framework.git
cd flex-grid-framework
npm install
```
The run gulp and the index page should launch at http://localhost:3000 automatically.

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
		<div class="col md-6 lg-3"> <!-- Column will be 50% on medium and 33% on large+ -->
			Your content
		</div>
	</div>

</div>
```