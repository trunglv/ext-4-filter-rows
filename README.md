ext-4-filter-rows
=================

Filter rows for Sencha Grid view -  EXT version 4.2.x

Use plugin : <br/>
Add js file : <br/>
var filterRow = Ext.create('Ext.ux.grid.FilterRow'); <br/>
var grid = Ext.create('Ext.grid.Panel', { <br/>
        store: store, <br/>
        stateful: true, <br/>
        stateId: 'stateGrid', <br/>
        plugins : [filterRow], <br/>
        columns: [ <br/>
    	... <br/>
        ]	<br/>
<br/>
