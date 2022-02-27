# Welcome to Learn JavaScript on the Now Platform!

This repository contains examples used in the video series in folders corresponding to the lessons. 
You can find the video series on the ServiceNow Developer 
[YouTube channel](https://www.youtube.com/watch?v=62Nabpb94Jw&list=PL3rNcyAiDYK2_87aRvXEmAyD8M9DARVGK&index=1)

Scripts use the naming structure **L(lesson#)S(script#).js**. 
Example, L09S01.js refers to Lesson 9, script example 1. 
Solutions to lab exercises can also be found in the *Lab Solutions* folder.

# Helpful resources mentioned in this series

* [Codecademy.com (JavaScript)](https://www.codecademy.com/catalog/language/javascript)
* [W3Schools.com (Javascript)](https://www.w3schools.com/js/default.asp)
* [ServiceNow Developer Program](https://developer.servicenow.com)
* [Scripting in ServiceNow Fundamentals](https://www.servicenow.com/services/training-and-certification/scripting-in-servicenow-training.html)
* [ServiceNow Docs](https://docs.servicenow.com)
* [ServiceNow Technical Best Practices](https://developer.servicenow.com/dev.do#!/guides/quebec/now-platform/tpb-guide/scripting_technical_best_practices)
* [TechNow webinars](https://devlink.sn/technow)
* [ServiceNow Community](https://community.servicenow.com)
* [Stephen Bell's Scripting Best Practices Videos](https://www.youtube.com/user/ServiceNowCommunity/search?query=scripting+best+practices)


# Scripting

## Common Scripting Locations

```
Business Rules -- A server-side script that runs when a RECORD is 
                  displayed, inserted, updated, or deleted, or when a table is queried.
               -- Triggered by database operations
               
Script includes -- Stores Javascript Classes & functions/methods
                -- Reusable code
                -- only run when invoked
                -- Server-side Javascript
                -- Can be called from Server-side or Client-side

Client Scripts -- Client scripts run on the client. You can use client script to define 
                  custom behaviors that run when event occur such as when a 
                  FORM is loaded or submitted, or a cell changes value.
               -- Triggered by Field changes, Page Loads, Form submission, cell edits
               -- Form Views
               
UI Actions -- UI actions add buttons, links, and context menu items on form lists, 
              making the UI more interactive, customizable, and specific to user activities.
           -- UI action can be BUTTON, MENU ITEMS, LINKS
           -- Server-side or client-side, or Both
           -- Typically configured for FORM VIEW
           
UI Policies -- Used to set fields to READ-ONLY, MANDATORY, SHOW/HIDE.

Scheduled Jobs -- Scheduled jobs are automated pieces of work that can be 
                  performed at either a particular time, or on a recurring schedule.
               -- Server-side Javascript
               
Workflows -- Automated sequence of activities
          -- Server-side JavaScript
          --  Many locations to script in a workflow


Transform Maps
Web Services
UI Pages & UI Macros
Service Portal Widgets

```

# GlideAjax

```
GlideAjax -- Enable a client script to call server-side code in a script include
          -- Client-side
          -- Stands for Asynchronous JavaScript and XML
          -- Uses browser's XMLHttpRequest API
          -- ga

```

