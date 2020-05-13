# RecyclerView


## Summary

-   [`RecyclerView`](https://developer.android.com/reference/android/support/v7/widget/RecyclerView.html)  is a resource-efficient way to display a scrollable list of items.
-   To create a  `View`  for each list item, the adapter inflates an XML layout resource for a list item using  [`LayoutInflator`](http://developer.android.com/reference/android/view/LayoutInflater.html).
-   [`LinearLayoutManager`](https://developer.android.com/reference/android/support/v7/widget/LinearLayoutManager.html)  is a  `RecyclerView`  layout manager that shows items in a vertical or horizontal scrolling list.
-   [`GridLayoutManager`](https://developer.android.com/reference/android/support/v7/widget/GridLayoutManager.html)  is a  `RecyclerView`  layout manager that shows items in a grid
-   [`StaggeredGridLayoutManager`](https://developer.android.com/reference/android/support/v7/widget/StaggeredGridLayoutManager.html)  is a  `RecyclerView`  layout manager that shows items in a staggered grid.
-   Use  [`RecyclerView.Adapter`](https://developer.android.com/reference/android/support/v7/widget/RecyclerView.Adapter.html)  to connect your data to the  `RecyclerView`. It prepares the data in a  [`RecyclerView.ViewHolder`](https://developer.android.com/reference/android/support/v7/widget/RecyclerView.ViewHolder.html)  that describes a  `View`  item and its position within the  `RecyclerView`.
-   Implement  [`View.onClickListener`](https://developer.android.com/reference/android/view/View.OnClickListener.html)  to detect mouse clicks in a  `RecyclerView`.
