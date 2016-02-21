## Grid ##

### Fixed gap grid ###

``` .grid-flex-fixed-gap ( @cols: 4, @gapCol: 20px, @gapRow: 20px ) ```

- @cols   - Default 4       - number of grid items per row
- @gapCol - Default 20px    - horizontal margin between grid items 
- @gapRow - Default 20px    - vertical margin between grid items

### Percent gap grid block ###

``` .grid-block-percent-gap ( @cols: 4, @gapCol: 20px, @gapRow: 20px ) ```

- @cols   - Default 4       - number of grid items per row
- @gapCol - Default 20px    - horizontal margin between grid items 
- @gapRow - Default 20px    - vertical margin between grid items

### Percent gap grid inline-block ###

``` .grid-inline-block-percent-gap ( @verticalAlign: top, @gridAlign: left, @textAlign: left, @cols: 4, @gapCol: 2%, @gapRow: 2% ) ```

- @verticalAlign:    - Default top               - vertical alignment of elements within a row
- @gridAlign    - Default left               - items' alignment within a row 
- @textAlign - Default left - text alignment within a grid item
- @cols             - Default 4                 - number of grid items per row
- @gapCol           - Default 2%              - horizontal margin between grid items 
- @gapRow           - Default 2%              - vertical margin between grid items

#### Samples ####

- [Fixed gaps](../../samples/grid/fixed-gap.html)
- [Block percent gap](../../samples/grid/block-percent-gap.html)
- [Inline-block percent gap](../../samples/grid/inline-block-percent-gap.html)