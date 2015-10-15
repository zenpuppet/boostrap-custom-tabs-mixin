# boostrap-custom-tabs-mixin
This mixin function allows you to define a specific look, feel, and some animation for a set of basic tabs on a site without having to modify the basic tabs for the entire theme.

## How to use it
	.custom_tabs( @nav-tab-name: super-nav-tabs; 
							
							@tabs_bottom_border_color:rgba(0,0,0,.1);
							@tabs-margin-right:8px;
							
							@tabs-font-family:Code_Pro;
							@tabs-font-size:2em;
							@tabs-font-weight:700;
							@tabs-letter-spacing:-0.0625em;
							@tabs-text-line-height:1.5em;
							@tabs-text-align:left;
							
							@tabs-inactive-border-color:rgba(0,0,0,0);
							@tabs-inactive-background-color:rgba(0,0,0,.1);
							@tabs-border-radius-left: 1em;
							@tabs-border-radius-right: .1em;
							@tabs-padding-top:.5em;
							@tabs-padding-right:1.5em;
							@tabs-padding-bottom:.25em;
							@tabs-padding-left:1.5em;
							
							@tabs-active-link-hover-bg:@nav-tabs-active-link-hover-bg;
							@tabs-active-link-color:@nav-tabs-active-link-hover-bg;
							
							);
