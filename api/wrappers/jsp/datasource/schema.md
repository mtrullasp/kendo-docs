---
title: dataSource-schema
slug: jsp-dataSource-schema
tags: api, java
publish: true
---

# \<kendo:dataSource-schema\>
A JSP tag representing Kendo Schema.

#### Example
    <kendo:dataSource>
        <kendo:dataSource-schema></kendo:dataSource-schema>
    </kendo:dataSource>


## Configuration Attributes


### aggregates `String`

Specifies the field from the response which contains the aggregate results. If set to a function - the function will be called to
return the aggregate results for the current response.

#### Example
    <kendo:dataSource-schema aggregates="aggregates">
    </kendo:dataSource-schema>



### data `String`

Specifies the field from the response which contains the data items. If set to a function - the function will be called to
return the data items for the current response.

#### Example
    <kendo:dataSource-schema data="data">
    </kendo:dataSource-schema>



### errors `String`

Specifies the field from the response which contains any errors. If set to a function - the function will be called to
return the errors for the current response (if present). If there are any errors the

#### Example
    <kendo:dataSource-schema errors="errors">
    </kendo:dataSource-schema>



### groups `String`

Specifies the field from the response which contains the groups. If set to a function - the function will be called to
return the groups for the current response.

#### Example
    <kendo:dataSource-schema groups="groups">
    </kendo:dataSource-schema>



### model `Object`

Describes the

#### Example
    <kendo:dataSource-schema model="model">
    </kendo:dataSource-schema>



### parse `String`

Executed before the server response is used. Appropriate for preprocessing or parsing of the server response.

#### Example
    <kendo:dataSource-schema parse="handle_parse">
    </kendo:dataSource-schema>
    <script>
        function handle_parse(e) {
            // Code to handle the parse event.
        }
    </script>



### total `String`

Specifies the field from the response which contains the total number of data items. If set to a function - the function will be called to
return the total number of data items for the current response.

#### Example
    <kendo:dataSource-schema total="total">
    </kendo:dataSource-schema>



### type `String`

Specify the type of the response - XML or JSON. The only supported values are

#### Example
    <kendo:dataSource-schema type="type">
    </kendo:dataSource-schema>



## Child JSP Tags
 
