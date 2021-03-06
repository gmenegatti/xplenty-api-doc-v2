### Segment Connection Attributes

|Name|Read-Only?|Required?|Default|Description|
|----|---------|---------|-------|-----------|
|id|Y| | |the connection's numeric identifier
|type|Y| | |`segment`
|name|N|Y| |the descriptive name given to the connection
|username|N|Y| |the database user name
|password|N|Y| |the database user password
|unique_id|Y| | |the unique connection's identifier
|created_at|Y| | |the date and time the connection was created
|updated_at|Y| | |the date and time the connection was last updated
|database|N|N|"events"|the name of database
|host|N|Y| |the name of the host to connect to
|port|N|N|5439|the TCP Port to connect to
|tunnel_type|N|N|"direct"|the method to use for accessing the database. Possible values: **direct**, **reverse**. In case of **reverse** type, **host** will be empty and **port** will be set to default.
|ssl|N|N|true|determines whether to connect to the database using SSL
|region|N|N|"amazon-web-services::us-west-2"|the geographical location of your Segment cluster
|url|Y| | |the connection resource URL (API)
