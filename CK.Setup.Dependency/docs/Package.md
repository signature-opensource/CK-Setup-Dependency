The model of the dependent items (items, groups and containers that require, or are required by, other items) and
the algorithm that orders them according to their dependencies.

An item is an `IDependentItem` (`IDependentItemGroup` and `IDependentItemContainer` for the composites);
`DependencySorter.OrderItems` orders them and returns an `IDependencySorterResult` with the `ISortedItem` list, or the
cycle and the missing dependencies.
