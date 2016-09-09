# ios10UICollectionViewLayoutBug
When implementing a UICollectionViewLayout. If you invalidate the layout, then recreate the attributes in prepare(), the cells are still rendering the old layers in when they are reused. It only happens in iOS10. It rendered correctly in prior versions.
