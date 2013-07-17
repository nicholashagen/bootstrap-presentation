Sample 3
======================

The third sample further extends the FIFA championship site adding the page the required HTML and page layout that Bootstrap suggests.

# Getting Started

Open the ``index.html`` file in your favorite browser.  You may also open the ``schedule.html`` page.

# What Changed

This sample first ensures the page is HTML5 compliant via the required doctype.  

It also adds a meta tag for the viewport so that mobile devices and tablets know how to handle the page given the size.

Next, we add the header and navigation block to the top of the page.  This is mostly copy/paste from the Twitter samples updating the links and titles accordingly.  The links essentially moved the static navigation in sample1 into the header as an unordered navigation list.

It then adds the containers, rows, and spans to ensure the fluidity of the design.  Bootstrap uses those three core constructs to layout the page.  Containers act as a grouping metaphor of rows and columns.  The rows create physical rows that may consume one or more spanned columns.  Columns use the 12-column grid structure to span columns accordingly.  In this sample, we span the main page content over 9 columns and include a new right hand navigation consuming the remaining 3-columns.

The main body is also organized into a separate row that groups the standings into a 2x2 grid spanning 6 columns a piece.  Rows may be embedded inside each other and each row contains its own 12-column grid, even when it is inside another separate column span.

Everything else is mostly unchanged from the previous samples.  However, viewing this sample provides a drastically improved flow.  The navigation stands out now.  The page no longer requires scrolling.  Overall, it just feels better already.
