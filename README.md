
# AngularIvyFlexLayoutIssue

@angular/flex-layout causes build to fail when Ivy is enabled

## Steps to recreate

Run `ng build` whilst `enableIvy` is set to true fails with the following error:  

>ERROR in ./node_modules/@angular/flex-layout/__ivy_ngcc__/esm5/extended.es5.js 156:578
Module parse failed: Unexpected token (156:578)
You may need an appropriate loader to handle this file type.
|         return _this;
|     }
 DefaultImgSrcDirective.ngDirectiveDef = ?ngcc0.??defineDirective({ type: DefaultImgSrcDirective, selectors: [["img", "
src.xs", ""], ["img", "src.sm", ""], ["img", "src.md", ""], ["img", "src.lg", ""], ["img", "src.xl", ""], ["img", "src.l
t-sm", ""], ["img", "src.lt-md", ""], ["img", "src.lt-lg", ""], ["img", "src.lt-xl", ""], ["img", "src.gt-xs", ""], ["im
g", "src.gt-sm", ""], ["img", "src.gt-md", ""], ["img", "src.gt-lg", ""]], factory: function DefaultImgSrcDirective_Fact
ory(t) { return ?DefaultImgSrcDirective_BaseFactory((t || DefaultImgSrcDirective)); }, inputs: { src.xs: "src.xs", src.s
m: "src.sm", src.md: "src.md", src.lg: "src.lg", src.xl: "src.xl", "src.lt-sm": "src.lt-sm", "src.lt-md": "src.lt-md", "
src.lt-lg": "src.lt-lg", "src.lt-xl": "src.lt-xl", "src.gt-xs": "src.gt-xs", "src.gt-sm": "src.gt-sm", "src.gt-md": "src
.gt-md", "src.gt-lg": "src.gt-lg" }, features: [?ngcc0.??InheritDefinitionFeature] });
| const ?DefaultImgSrcDirective_BaseFactory = ?ngcc0.??getInheritedFactory(DefaultImgSrcDirective);
| /*@__PURE__*/ ?ngcc0.?setClassMetadata(DefaultImgSrcDirective, [{
ERROR in ./node_modules/@angular/flex-layout/__ivy_ngcc__/esm5/flex.es5.js 195:653
Module parse failed: Unexpected token (195:653)
You may need an appropriate loader to handle this file type.
|         return _this;
|     }
> DefaultLayoutDirective.ngDirectiveDef = ?ngcc0.??defineDirective({ type: DefaultLayoutDirective, selectors: [["", "fxL
ayout", ""], ["", "fxLayout.xs", ""], ["", "fxLayout.sm", ""], ["", "fxLayout.md", ""], ["", "fxLayout.lg", ""], ["", "f
xLayout.xl", ""], ["", "fxLayout.lt-sm", ""], ["", "fxLayout.lt-md", ""], ["", "fxLayout.lt-lg", ""], ["", "fxLayout.lt-
xl", ""], ["", "fxLayout.gt-xs", ""], ["", "fxLayout.gt-sm", ""], ["", "fxLayout.gt-md", ""], ["", "fxLayout.gt-lg", ""]
], factory: function DefaultLayoutDirective_Factory(t) { return ?DefaultLayoutDirective_BaseFactory((t || DefaultLayoutD
irective)); }, inputs: { fxLayout: "fxLayout", fxLayout.xs: "fxLayout.xs", fxLayout.sm: "fxLayout.sm", fxLayout.md: "fxL
ayout.md", fxLayout.lg: "fxLayout.lg", fxLayout.xl: "fxLayout.xl", "fxLayout.lt-sm": "fxLayout.lt-sm", "fxLayout.lt-md":
 "fxLayout.lt-md", "fxLayout.lt-lg": "fxLayout.lt-lg", "fxLayout.lt-xl": "fxLayout.lt-xl", "fxLayout.gt-xs": "fxLayout.g
t-xs", "fxLayout.gt-sm": "fxLayout.gt-sm", "fxLayout.gt-md": "fxLayout.gt-md", "fxLayout.gt-lg": "fxLayout.gt-lg" }, fea
tures: [?ngcc0.??InheritDefinitionFeature] });
| const ?DefaultLayoutDirective_BaseFactory = ?ngcc0.??getInheritedFactory(DefaultLayoutDirective);
| /*@__PURE__*/ ?ngcc0.?setClassMetadata(DefaultLayoutDirective, [{
ERROR in ./node_modules/@angular/flex-layout/__ivy_ngcc__/esm5/grid.es5.js 98:719
Module parse failed: Unexpected token (98:719)
You may need an appropriate loader to handle this file type.
|         return _this;
|     }
> DefaultGridAlignDirective.ngDirectiveDef = ?ngcc0.??defineDirective({ type: DefaultGridAlignDirective, selectors: [[""
, "gdGridAlign", ""], ["", "gdGridAlign.xs", ""], ["", "gdGridAlign.sm", ""], ["", "gdGridAlign.md", ""], ["", "gdGridAl
ign.lg", ""], ["", "gdGridAlign.xl", ""], ["", "gdGridAlign.lt-sm", ""], ["", "gdGridAlign.lt-md", ""], ["", "gdGridAlig
n.lt-lg", ""], ["", "gdGridAlign.lt-xl", ""], ["", "gdGridAlign.gt-xs", ""], ["", "gdGridAlign.gt-sm", ""], ["", "gdGrid
Align.gt-md", ""], ["", "gdGridAlign.gt-lg", ""]], factory: function DefaultGridAlignDirective_Factory(t) { return ?Defa
ultGridAlignDirective_BaseFactory((t || DefaultGridAlignDirective)); }, inputs: { gdGridAlign: "gdGridAlign", gdGridAlig
n.xs: "gdGridAlign.xs", gdGridAlign.sm: "gdGridAlign.sm", gdGridAlign.md: "gdGridAlign.md", gdGridAlign.lg: "gdGridAlign
.lg", gdGridAlign.xl: "gdGridAlign.xl", "gdGridAlign.lt-sm": "gdGridAlign.lt-sm", "gdGridAlign.lt-md": "gdGridAlign.lt-m
d", "gdGridAlign.lt-lg": "gdGridAlign.lt-lg", "gdGridAlign.lt-xl": "gdGridAlign.lt-xl", "gdGridAlign.gt-xs": "gdGridAlig
n.gt-xs", "gdGridAlign.gt-sm": "gdGridAlign.gt-sm", "gdGridAlign.gt-md": "gdGridAlign.gt-md", "gdGridAlign.gt-lg": "gdGr
idAlign.gt-lg" }, features: [?ngcc0.??InheritDefinitionFeature] });
| const ?DefaultGridAlignDirective_BaseFactory = ?ngcc0.??getInheritedFactory(DefaultGridAlignDirective);
| /*@__PURE__*/ ?ngcc0.?setClassMetadata(DefaultGridAlignDirective, [{