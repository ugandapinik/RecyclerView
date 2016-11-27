# RecyclerView
The RecyclerView is a new ViewGroup that is prepared to render any adapter-based view in a similar way. It is supposed to be the successor of ListView and GridView, and it can be found in the latest support-v7 version. One of the reasons is that RecyclerView has a more extensible framework, especially since it provides the ability to implement both horizontal and vertical layouts. Use the RecyclerView widget when you have data collections whose elements change at runtime based on user action or network events.


# Using the RecyclerView

## Using a RecyclerView has the following key steps:
  
  <ol>
  <li>Add RecyclerView support library to the gradle build file</li>
  <li>Define a model class to use as the data source</li>
  <li>Add a RecyclerView to your activity to display the items</li>
  <li>Create a custom row layout XML file to visualize the item</li>
  <li>Create a RecyclerView.Adapter and ViewHolder to render the item</li>
  <li>Bind the adapter to the data source to populate the RecyclerView</li>

The steps are explained in more detail below.
