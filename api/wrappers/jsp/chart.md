---
title: chart
slug: jsp-chart
tags: api, java
publish: true
---

# \<kendo:chart\>
A JSP tag representing Kendo Chart.


## Configuration Attributes


### seriesColors `Object`

The default colors for the chart's series. When all colors are used, new colors are pulled from the start again.

#### Example
    <kendo:chart seriesColors="seriesColors">
    </kendo:chart>



### theme `String`

Sets Chart theme. Available themes: default, blueOpal, black.

#### Example
    <kendo:chart theme="theme">
    </kendo:chart>



### transitions `boolean`

A value indicating if transition animations should be played.

#### Example
    <kendo:chart transitions="transitions">
    </kendo:chart>



### axisLabelClick `String`

Fires when an axis label is clicked.

#### Example
    <kendo:chart axisLabelClick="handle_axisLabelClick">
    </kendo:chart>
    <script>
        function handle_axisLabelClick(e) {
            // Code to handle the axisLabelClick event.
        }
    </script>



### dataBound `String`

Fires when the chart has received data from the data source
and is about to render it.

#### Example
    <kendo:chart dataBound="handle_dataBound">
    </kendo:chart>
    <script>
        function handle_dataBound(e) {
            // Code to handle the dataBound event.
        }
    </script>



### dragStart `String`

Fires when the user has used the mouse or a swipe gesture to drag the chart.

#### Example
    <kendo:chart dragStart="handle_dragStart">
    </kendo:chart>
    <script>
        function handle_dragStart(e) {
            // Code to handle the dragStart event.
        }
    </script>



### drag `String`

Fires as long as the user is dragging the chart using the mouse or swipe gestures.

#### Example
    <kendo:chart drag="handle_drag">
    </kendo:chart>
    <script>
        function handle_drag(e) {
            // Code to handle the drag event.
        }
    </script>



### dragEnd `String`

Fires when the user stops dragging the chart.

#### Example
    <kendo:chart dragEnd="handle_dragEnd">
    </kendo:chart>
    <script>
        function handle_dragEnd(e) {
            // Code to handle the dragEnd event.
        }
    </script>



### plotAreaClick `String`

Fires when plot area is clicked.

#### Example
    <kendo:chart plotAreaClick="handle_plotAreaClick">
    </kendo:chart>
    <script>
        function handle_plotAreaClick(e) {
            // Code to handle the plotAreaClick event.
        }
    </script>



### seriesClick `String`

Fires when chart series are clicked.

#### Example
    <kendo:chart seriesClick="handle_seriesClick">
    </kendo:chart>
    <script>
        function handle_seriesClick(e) {
            // Code to handle the seriesClick event.
        }
    </script>



### seriesHover `String`

Fires when chart series are hovered.

#### Example
    <kendo:chart seriesHover="handle_seriesHover">
    </kendo:chart>
    <script>
        function handle_seriesHover(e) {
            // Code to handle the seriesHover event.
        }
    </script>



### zoomStart `String`

Fires when the user has used the mousewheel to zoom the chart.

#### Example
    <kendo:chart zoomStart="handle_zoomStart">
    </kendo:chart>
    <script>
        function handle_zoomStart(e) {
            // Code to handle the zoomStart event.
        }
    </script>



### zoom `String`

Fires as long as the user is zooming the chart using the mousewheel.

#### Example
    <kendo:chart zoom="handle_zoom">
    </kendo:chart>
    <script>
        function handle_zoom(e) {
            // Code to handle the zoom event.
        }
    </script>



### zoomEnd `String`

Fires when the user stops zooming the chart.

#### Example
    <kendo:chart zoomEnd="handle_zoomEnd">
    </kendo:chart>
    <script>
        function handle_zoomEnd(e) {
            // Code to handle the zoomEnd event.
        }
    </script>



### Event Attributes


### axisLabelClick `String`

Fires when an axis label is clicked.

#### Example
    <kendo:chart axisLabelClick="handle_axisLabelClick">
    </kendo:chart>
    <script>
        function handle_axisLabelClick(e) {
            // Code to handle the axisLabelClick event.
        }
    </script>



### dataBound `String`

Fires when the chart has received data from the data source
and is about to render it.

#### Example
    <kendo:chart dataBound="handle_dataBound">
    </kendo:chart>
    <script>
        function handle_dataBound(e) {
            // Code to handle the dataBound event.
        }
    </script>



### dragStart `String`

Fires when the user has used the mouse or a swipe gesture to drag the chart.

#### Example
    <kendo:chart dragStart="handle_dragStart">
    </kendo:chart>
    <script>
        function handle_dragStart(e) {
            // Code to handle the dragStart event.
        }
    </script>



### drag `String`

Fires as long as the user is dragging the chart using the mouse or swipe gestures.

#### Example
    <kendo:chart drag="handle_drag">
    </kendo:chart>
    <script>
        function handle_drag(e) {
            // Code to handle the drag event.
        }
    </script>



### dragEnd `String`

Fires when the user stops dragging the chart.

#### Example
    <kendo:chart dragEnd="handle_dragEnd">
    </kendo:chart>
    <script>
        function handle_dragEnd(e) {
            // Code to handle the dragEnd event.
        }
    </script>



### plotAreaClick `String`

Fires when plot area is clicked.

#### Example
    <kendo:chart plotAreaClick="handle_plotAreaClick">
    </kendo:chart>
    <script>
        function handle_plotAreaClick(e) {
            // Code to handle the plotAreaClick event.
        }
    </script>



### seriesClick `String`

Fires when chart series are clicked.

#### Example
    <kendo:chart seriesClick="handle_seriesClick">
    </kendo:chart>
    <script>
        function handle_seriesClick(e) {
            // Code to handle the seriesClick event.
        }
    </script>



### seriesHover `String`

Fires when chart series are hovered.

#### Example
    <kendo:chart seriesHover="handle_seriesHover">
    </kendo:chart>
    <script>
        function handle_seriesHover(e) {
            // Code to handle the seriesHover event.
        }
    </script>



### zoomStart `String`

Fires when the user has used the mousewheel to zoom the chart.

#### Example
    <kendo:chart zoomStart="handle_zoomStart">
    </kendo:chart>
    <script>
        function handle_zoomStart(e) {
            // Code to handle the zoomStart event.
        }
    </script>



### zoom `String`

Fires as long as the user is zooming the chart using the mousewheel.

#### Example
    <kendo:chart zoom="handle_zoom">
    </kendo:chart>
    <script>
        function handle_zoom(e) {
            // Code to handle the zoom event.
        }
    </script>



### zoomEnd `String`

Fires when the user stops zooming the chart.

#### Example
    <kendo:chart zoomEnd="handle_zoomEnd">
    </kendo:chart>
    <script>
        function handle_zoomEnd(e) {
            // Code to handle the zoomEnd event.
        }
    </script>


## Event Tags
           

### kendo:chart-axisLabelClick

Fires when an axis label is clicked.

#### Example
    <kendo:chart>
        <kendo:chart-axisLabelClick>
            <script>
                function(e) {
                    // Code to handle the axisLabelClick event.
                }
            </script>
        </kendo:chart-axisLabelClick>
    </kendo:chart>

 

### kendo:chart-dataBound

Fires when the chart has received data from the data source
and is about to render it.

#### Example
    <kendo:chart>
        <kendo:chart-dataBound>
            <script>
                function(e) {
                    // Code to handle the dataBound event.
                }
            </script>
        </kendo:chart-dataBound>
    </kendo:chart>

 

### kendo:chart-dragStart

Fires when the user has used the mouse or a swipe gesture to drag the chart.

#### Example
    <kendo:chart>
        <kendo:chart-dragStart>
            <script>
                function(e) {
                    // Code to handle the dragStart event.
                }
            </script>
        </kendo:chart-dragStart>
    </kendo:chart>

 

### kendo:chart-drag

Fires as long as the user is dragging the chart using the mouse or swipe gestures.

#### Example
    <kendo:chart>
        <kendo:chart-drag>
            <script>
                function(e) {
                    // Code to handle the drag event.
                }
            </script>
        </kendo:chart-drag>
    </kendo:chart>

 

### kendo:chart-dragEnd

Fires when the user stops dragging the chart.

#### Example
    <kendo:chart>
        <kendo:chart-dragEnd>
            <script>
                function(e) {
                    // Code to handle the dragEnd event.
                }
            </script>
        </kendo:chart-dragEnd>
    </kendo:chart>

 

### kendo:chart-plotAreaClick

Fires when plot area is clicked.

#### Example
    <kendo:chart>
        <kendo:chart-plotAreaClick>
            <script>
                function(e) {
                    // Code to handle the plotAreaClick event.
                }
            </script>
        </kendo:chart-plotAreaClick>
    </kendo:chart>

 

### kendo:chart-seriesClick

Fires when chart series are clicked.

#### Example
    <kendo:chart>
        <kendo:chart-seriesClick>
            <script>
                function(e) {
                    // Code to handle the seriesClick event.
                }
            </script>
        </kendo:chart-seriesClick>
    </kendo:chart>

 

### kendo:chart-seriesHover

Fires when chart series are hovered.

#### Example
    <kendo:chart>
        <kendo:chart-seriesHover>
            <script>
                function(e) {
                    // Code to handle the seriesHover event.
                }
            </script>
        </kendo:chart-seriesHover>
    </kendo:chart>

 

### kendo:chart-zoomStart

Fires when the user has used the mousewheel to zoom the chart.

#### Example
    <kendo:chart>
        <kendo:chart-zoomStart>
            <script>
                function(e) {
                    // Code to handle the zoomStart event.
                }
            </script>
        </kendo:chart-zoomStart>
    </kendo:chart>

 

### kendo:chart-zoom

Fires as long as the user is zooming the chart using the mousewheel.

#### Example
    <kendo:chart>
        <kendo:chart-zoom>
            <script>
                function(e) {
                    // Code to handle the zoom event.
                }
            </script>
        </kendo:chart-zoom>
    </kendo:chart>

 

### kendo:chart-zoomEnd

Fires when the user stops zooming the chart.

#### Example
    <kendo:chart>
        <kendo:chart-zoomEnd>
            <script>
                function(e) {
                    // Code to handle the zoomEnd event.
                }
            </script>
        </kendo:chart-zoomEnd>
    </kendo:chart>

 

## Child JSP Tags

### kendo:chart-categoryAxis

The category axis configuration options.

More documentation is available at [kendo:chart-categoryAxis](/api/wrappers/jsp/chart/categoryaxis).

#### Example

    <kendo:chart>
        <kendo:chart-categoryAxis></kendo:chart-categoryAxis>
    </kendo:chart>
 
### kendo:chart-title

The title of the category axis.

More documentation is available at [kendo:chart-title](/api/wrappers/jsp/chart/title).

#### Example

    <kendo:chart>
        <kendo:chart-title></kendo:chart-title>
    </kendo:chart>
 
### kendo:chart-chartArea

The chart area configuration options.
This is the entire visible area of the chart.

More documentation is available at [kendo:chart-chartArea](/api/wrappers/jsp/chart/chartarea).

#### Example

    <kendo:chart>
        <kendo:chart-chartArea></kendo:chart-chartArea>
    </kendo:chart>
 
### kendo:chart-legend

The chart legend configuration options.

More documentation is available at [kendo:chart-legend](/api/wrappers/jsp/chart/legend).

#### Example

    <kendo:chart>
        <kendo:chart-legend></kendo:chart-legend>
    </kendo:chart>
 
### kendo:chart-panes

The chart panes configuration.

More documentation is available at [kendo:chart-panes](/api/wrappers/jsp/chart/panes).

#### Example

    <kendo:chart>
        <kendo:chart-panes></kendo:chart-panes>
    </kendo:chart>
 
### kendo:chart-plotArea

The plot area configuration options. This is the area containing the plotted series.

More documentation is available at [kendo:chart-plotArea](/api/wrappers/jsp/chart/plotarea).

#### Example

    <kendo:chart>
        <kendo:chart-plotArea></kendo:chart-plotArea>
    </kendo:chart>
 
### kendo:chart-series

Array of series definitions.

More documentation is available at [kendo:chart-series](/api/wrappers/jsp/chart/series).

#### Example

    <kendo:chart>
        <kendo:chart-series></kendo:chart-series>
    </kendo:chart>
 
### kendo:chart-tooltip

The data point tooltip configuration options.

More documentation is available at [kendo:chart-tooltip](/api/wrappers/jsp/chart/tooltip).

#### Example

    <kendo:chart>
        <kendo:chart-tooltip></kendo:chart-tooltip>
    </kendo:chart>
 
### kendo:chart-valueAxis

The value axis configuration options.

More documentation is available at [kendo:chart-valueAxis](/api/wrappers/jsp/chart/valueaxis).

#### Example

    <kendo:chart>
        <kendo:chart-valueAxis></kendo:chart-valueAxis>
    </kendo:chart>
 
### kendo:chart-xAxis

Scatter charts X-axis configuration options.
Includes

More documentation is available at [kendo:chart-xAxis](/api/wrappers/jsp/chart/xaxis).

#### Example

    <kendo:chart>
        <kendo:chart-xAxis></kendo:chart-xAxis>
    </kendo:chart>
 
### kendo:chart-yAxis

Scatter charts Y-axis configuration options.
Includes

More documentation is available at [kendo:chart-yAxis](/api/wrappers/jsp/chart/yaxis).

#### Example

    <kendo:chart>
        <kendo:chart-yAxis></kendo:chart-yAxis>
    </kendo:chart>
            
