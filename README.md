# row-x-inlb: css inline-block grid system
## use in scss: 
  @import "./scss/mixins.scss"; 
  @include cols_gutter(12, 0.8); //row-x12g col [col-1 ... col-12]
  @include cols_gutter(24, 0.2);
  @include cols_gutter(2, 0.8);  //row-x2g col [col-1, col-2]

## use in html:  
### x12 grid
``<code><div class="row-x12g">
	<div class="col col-3"> 1/4 </div>
	<div class="col col-3"> 1/4 </div>
	<div class="col col-3"> 1/4 </div>
	<div class="col col-3"> 1/4 </div>
</div></code>``

### x2 grid
```<code><div class="row-x2g">
	<div class="col col-1"> 1/2 </div>
	<div class="col col-1"> 1/2 </div>
</div></code>```
