
# Learn how to use UITableView to develop iOS App UI

## Official Documents

* [UITableView](https://developer.apple.com/documentation/uikit/uitableview)

## Basic Concepts

### UITableView Diagram

![UITableView Diagram](http://wx4.sinaimg.cn/mw690/006RF1rrgy1fiximklmmpj30vs0omk67.jpg)

## UITableView Series

* [UITableView Series Pt 1/10: Introduction to UITableView and UITableViewController Tutorial in Swift](https://www.youtube.com/watch?v=NQpvABzgIeU)
* [UITableView Pt 2: Create Data Model Classes to Display On UITableView & UITableViewController](https://www.youtube.com/watch?v=IohAGvQj6TE)
* [UITableView Pt 3: Create Basic UITableView and UITableViewController, UITableViewCell](https://www.youtube.com/watch?v=KRFpB-uLPOA)
* [UITableView Pt 4: Create Custom Table View Cell, Dynamic Table View Cell Height, Self-Sizing Cell](https://www.youtube.com/watch?v=nwnRmw_rjBM)
* [UITableView Pt 5/10: CREATE MULTIPLE SECTIONS IN TABLE VIEW](https://www.youtube.com/watch?v=GHTwGi4L_58)
* [UITableView Pt 6/10: DELETE ROWS FROM TABLE VIEW SWIFT TUTORIAL](https://www.youtube.com/watch?v=iRZq_igJlOA)
* [UITableView Pt 7/10: DRAG AND DROP TO MOVE CELL IN TABLE VIEW SWIFT TUTORIAL](https://www.youtube.com/watch?v=8T6yOrUJseE)
* [UITableView Pt 8/10 CREATE STATIC UITABLEVIEW AND UITABLEVIEWCONTROLLER](https://www.youtube.com/watch?v=Nbx44G0oVBg)
* [UITableView Pt 9/10 USE SHOW SEGUE TO TRANSITION FROM MASTER TO DETAIL VIEW CONTROLLER](https://www.youtube.com/watch?v=OPe0XPhi5Bg)


### Quick Start

1. Drag a Table View Controller on Story board
2. Click "Table View Controller" button, and then choose Editor -> Embed in -> Navigation Controller
3. The Story board shows "Navigation Controller" => "Table View"
4. Click "Navigation Controller", check **"Is initial view controller"**
5. Ceate a Cocoa touch class "XXXTableViewController"
6. Click "Table View Controller", and click "Table View Controller" button, set its **class** as new created "XXXTableViewController" class
7. On "Table View Controller", click **seperator line**, and input **Table View Cell identifier** and set its style as "Basic"
8. Implement UITableViewDataSource methods:

* numberOfSectionsin tableView
* numberOfRrows in section
* cellForRow at indexPath
* dequeue Table View Cell (show data in current Table view cell)
9. Design the Table View Cell in Story board:
* Add image view
* Add title label
* Add description label
* Add contraint for above UI components
* Fix the auto layout issue (red line) to avoid component layout overlap, change content hugging and content compression
10. Create a subclass of UITableViewCell, to implement how to udpate UI in table view cell:
* Link TableViewCell class with the new created class
* Link image view, title label and description label UI components with code
11. Update cell with UITableViewDataSource in custom UITableViewController


