---
title: add_client_monitoring
index: true
noTitle: true
no_edit: true
---



<div class="vql_item"></div>


## add_client_monitoring
<span class='vql_type label label-warning pull-right page-header'>Function</span>



<div class="vqlargs"></div>

Arg | Description | Type
----|-------------|-----
artifact|The name of the artifact to add|string (required)
parameters|A dict of artifact parameters|LazyExpr
label|Add the artifact to this label group (default all)|string

Required Permissions: 
<span class="linkcolour label label-success">COLLECT_CLIENT</span>

### Description

Adds a new artifact to the client monitoring table.

