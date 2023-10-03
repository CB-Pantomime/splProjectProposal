
# Frontend feature requirements:

## 1. Wire-frame a React application that fits within the FOLIO application style. 

## Features required in UI:
# Records Management
-People, property and vehicle tracking. See all of a record details
at a glance along with their history time-line. 

# Reporting
Events date & time logging
File attachments
Record linking and search
Report emailing schedule

# Location tracking
Sub-locations

# Reference
Image storage and reference. Images of incident(s) captured by staff and uploaded. Images associated with customers/users stored in the db/referenced in the report. 

Please see: 
/wireFrames/wireFrames.md

## 2. Some details on fitting React application within the FOLIO application style:

Understand and implement how Stripes fits together such as -> stripes-connect (provides the connection to FOLIO's services), stripes-components (provides re-usable UI components such as checkboxes, search forms and multi-pane layouts), stripes-logger (simple facilities logging), and stripes-core (a web app that controls a set of UI modules and helps them work together). 


Underlying Tech -> Stripes UI modules are written in JavaScript, specifically ES6. The UI is built using React. Note - The promise of React is it "will efficiently update and render just the right components when your data changes." THe goal of stripes-connect is to ensure that module's React components are given the right data. 


Understand and utilize JSX, syntax for embedding XML into JavaScript. 

Be familiar with UI components, including the ones available from stripes-components. 

Modules
A Stripes UI module is a self-contained chunk of UI that can be loaded into Stripes, which means there are requirements to which it must conform. 
Note - The source code for a module is generally held in a git project whose name begins 'ui-'


Understand and implement equired information to be provided in a stripes top level key for a module's package file. For example, there is the actsAs - a short string, or array of them, indicating how Stripes should consume the module. Some acceptable values are: app, settings, plugin, handler. 
[See here](https://github.com/folio-org/stripes/blob/master/doc/dev-guide.md#modules)


Define all of your routes at the top (prefer to contain all routes in the top-level index.js) 

Certainly there are more. 
Please reference the [Stripes Module Developer's Guide](https://github.com/folio-org/stripes/blob/master/doc/dev-guide.md#modules)